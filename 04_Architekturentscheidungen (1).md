# Architektur- und Projektentscheidungen

Format: Datum | Thema | Optionen | Entscheid | Begründung

## 2026-09-10 – Ablage der Projektdokumentation

**Optionen geprüft:**
- A) Privates GitHub-Repo
- B) OneNote/SharePoint im Verlingue-Tenant
- C) Lokale Dateien

**Entscheid:** Option A – privates GitHub-Repo

**Begründung:** Versionierter Änderungsverlauf, kostenlos, lässt sich direkt mit Coding-Tools verbinden. Enthält ausschliesslich fiktive/synthetische Daten (siehe Risiken).

## 2026-09-10 – Umgang mit Verlingue-Daten während der Prototyp-Phase

**Entscheid:** Bis zur offiziellen Freigabe durch IT/Compliance werden ausschliesslich frei erfundene, aber realistisch strukturierte Beispieldaten verwendet – keine echten, auch keine "anonymisierten" Kunden-, Fahrzeug- oder Schadendaten.

**Begründung:** Formal fehlt die Erlaubnis; zudem lässt sich bei kleinen, spezifischen Datensätzen (z.B. Flotte mit 5 Fahrzeugen) eine echte Anonymisierung kaum garantieren (Re-Identifikationsrisiko).

## 2026-09-10 – Erweiterung der Prozesslandkarte

**Entscheid:** Aufnahme von drei zusätzlichen Prozessen: Reklamations-/Beschwerdemanagement, Regressbearbeitung bei Schäden, Mahnwesen bei nicht bezahlten Prämien.

**Nicht aufgenommen (weiterhin offen):** Kundenreporting, ausserordentliche Kündigung durch Versicherer, Zusammenarbeit mit Garagen/Werkstätten, Auskunftsbegehren/Datenschutzanfragen, Onboarding neuer Mitarbeitender.

## Noch zu entscheiden

- Wahl des technischen Zugangs zu Claude Code (Terminal / IDE-Erweiterung / Web) – zurückgestellt, bis Datenmodell und erster Prozess (Ausschreibung bzw. Schadenbearbeitung) genauer feststehen
- Ob/wie eine Anbindung an winVS next technisch überhaupt möglich ist (API? Export?) – Rückfrage an IT/Anbieter nötig
