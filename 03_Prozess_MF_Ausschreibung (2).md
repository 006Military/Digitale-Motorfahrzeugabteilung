# Prozess: MF-Flotten-Ausschreibung

**Status:** In Arbeit (Auslöser und Eingangsdaten erfasst, Arbeitsschritte noch nicht zerlegt)

## 1. Fachliches Ziel (Annahme – bitte bestätigen)

Am Ende des Prozesses liegen eine oder mehrere vergleichbare Offerten von Versicherern vor, auf deren Basis der Kunde eine fundierte Entscheidung treffen kann.

## 2. Auslöser (zwei Wege)

**Weg 1 – Sanierung durch Versicherer**
Versicherer meldet, dass ein Vertrag (MF-Flotte oder MF-Einzel) nicht wie gewünscht verläuft → Verlingue informiert den Kunden über die anstehende Sanierung per 01.01.20xx → Kunde entscheidet, auch basierend auf Empfehlung von Verlingue: Vertrag ausschreiben ODER Sanierung akzeptieren.

**Weg 2 – reguläres Vertragsende (Jahresgespräch)**
Am Jahresgespräch wird besprochen, dass der Vertrag per 31.12.20xx ausläuft → Kunde entscheidet: (a) ausschreiben/neuen Versicherer suchen, (b) beim bisherigen Versicherer bleiben, Erneuerung ohne Gegenofferten, (c) ggf. weitere Optionen – noch zu klären.

**Vorlaufzeit und Bestätigung (geklärt):**

*Vorlaufzeit – Unterschied Flotte vs. Einzel:*
- **MF-Flotte:** in der Regel 6–12 Monate Vorlauf. Der Kunde teilt am Jahresgespräch (findet meist Februar–Juli statt, in der ersten Jahreshälfte) mit, ob er ausschreiben möchte. Verlingue weist den Kunden bei schlechtem Schadenverlauf proaktiv darauf hin, dass eine Sanierung durch den Versicherer möglich ist – geht dazu aber **nicht proaktiv auf den Versicherer zu**, sondern wartet grundsätzlich zurückhaltend ab, bis der Versicherer die Sanierungslisten von sich aus versendet.
- **MF-Einzel:** deutlich kürzerer Vorlauf möglich – Sanierungen oder eine PAK (Prämienanpassungsklausel) können auch erst 1–3 Monate vor Vertragsablauf vom Versicherer mitgeteilt werden, was zeitlich knapp werden kann.

*Schriftliche Bestätigung:*
- Der Kundenentscheid wird grundsätzlich immer schriftlich festgehalten: Der Kunde muss schriftlich bestätigen, dass er mit Wechsel/Sanierung/Ausschreibung einverstanden ist – entweder per E-Mail, oder durch Unterzeichnen und Rücksendung eines von Verlingue mitgesendeten Antrags/Formulars

## 3. Benötigte Eingangsdaten/Unterlagen

### Fahrzeugliste (idealerweise Excel) – Pflichtfelder
- Halterfirma – **wichtig bei Holding-Strukturen**: einzelne Fahrzeuge einer Flotte können auf unterschiedliche Tochtergesellschaften laufen (Beispiel zur Illustration: Fahrzeug SG 123 auf Tochter A, Fahrzeug SG 234 auf Tochter B, beide gehören zur selben Holding)
- Kontrollschild je Fahrzeug
- Stammnummer
- Deckungen je Fahrzeug
- Katalogpreis
- Zubehörpreis
- Datum der 1. Inverkehrssetzung

### Schadenrendement / Einzelschadenliste
- Kommt **vom Versicherer**, wird nicht von Verlingue selbst berechnet
- Verlingue wertet die gelieferten Daten aus, zieht Schlüsse und bereitet sie kundenverständlich auf
- Betrachtungszeitraum: 5 Jahre (sofern der Vertrag so lange besteht)

### Weitere Unterlagen
- Bestehende Bedingungen (AVB, Police)
- Deckungskonzept, falls vorhanden (zeigt, wie die Fahrzeuge aktuell versichert sind)

## Wichtige fachliche Erkenntnis: Sanierungsschwelle ist NICHT einheitlich

*Korrektur einer zu vereinfachten Annahme (ursprünglich ">60% = schlecht" angenommen – das war falsch/zu pauschal).*

Tatsächlich:
- Schwellenwerte, ab denen ein Versicherer saniert, variieren je Gesellschaft: z.B. 68%, 70%, 80% oder höher
- Faustregel: Versicherer kalkulieren mit ca. 20% Verwaltungskosten (Tendenz steigend)
- Weitere Einflussfaktoren: 1-Policen-Kunde (tendenziell frühere Sanierung) vs. Mehrfachpolicen-Kunde bei derselben Gesellschaft; Höhe der Gesamtprämie, die der Kunde der Gesellschaft insgesamt schuldet

**Einordnung für die künftige Wissensbank:**
- Wissensart: Erfahrungswissen aus bisherigen Fällen (keine offiziell dokumentierte Regel)
- Quelle: Erfahrungswert Silvan Keller
- Status: Kandidat für einen der ersten Wissenseinträge, sobald das Wissensmodell steht – konkrete Schwellenwerte je Versicherer sind noch zu sammeln

## 4. Grober Ablauf nach Kundenzusage ("bitte ausschreiben")

*Grobgerüst – Details zu jedem Schritt (Systeme, Dauer, weitere Beteiligte) folgen in der nächsten Runde.*

1. In WinVS wird die Entität "Ausschreibung MF-Flotte per 01.01.20xx" angelegt
2. Ausschreibungsdokument wird hochgeladen und in SharePoint bearbeitet
3. Parallel: Mail an aktuellen Versicherer – Bestellung tagesaktuelles Fahrzeugverzeichnis und Rendement; bei bekannt schlechtem Verlauf zusätzlich gleich die Einzelschadenliste
4. Dokument wird weiter befüllt (Modalitäten/Anforderungen an den Versicherer)
5. Übergabe an den Mandatsleiter zur Kontrolle
6. Nach Freigabe: Versand des Ausschreibungsdokuments per Mail an ausgewählte Versicherer (typischerweise AXA, Allianz, Generali, Helvetia, Simpego, Smile, Zürich, Mobiliar, Vaudoise), inkl. Deadline für Offertabgabe oder Verzicht
7. Rückmeldungen der Versicherer sammeln
8. Vergleich der Offerten erstellen (detaillierter, zeitintensiver Teil)
9. Empfehlung erarbeiten
10. Mandatsleiter prüft Vergleich und Empfehlung erneut
11. Vergleich inkl. Empfehlung wird dem Kunden zugestellt
12. Kundenrückmeldung abwarten
13. Weitere Schritte einleiten: Kündigung beim bisherigen Versicherer einreichen, unterschriebenen Antrag beim neuen Versicherer einreichen
14. Alles wird als Aktivität in WinVS mit Fälligkeit festgehalten (Beispiel: "Kündigungsbestätigung Allianz da?", Fälligkeit +2 Wochen; falls nicht eingetroffen, aktiv nachfassen)

## 5. Detaillierung der Arbeitsschritte

### Schritt 1: Entität "Ausschreibung MF-Flotte per 01.01.20xx" in WinVS anlegen

- **Eingetragene Felder:** Name, Datum des Vertragsbeginns, Branche (Sparte), auf die sich die Ausschreibung bezieht
- **Zweck der Entität:** dient als eine Art eigener Ordner für alles, was mit dieser Ausschreibung zu tun hat – losgelöst von der Entität "Police", damit diese nicht mit Unterlagen überflutet wird, die z.B. nur 2026 gebraucht werden und danach mehrere Jahre nicht mehr
- **Dauer:** ca. 2–5 Minuten
- **Beteiligte:** nur Silvan (Consultant), kein Vieraugenprinzip an dieser Stelle

### Schritt 2: Ausschreibungsdokument hochladen und in SharePoint bearbeiten

- **Quelle der Vorlage:** fixer "Vorlagen"-Ordner in SharePoint, auf den alle Verlingue-Mitarbeitenden Zugriff haben
- **Ablauf:** leeres Vorlage-Dokument wird in die jeweilige Ausschreibungs-Entität in WinVS hochgeladen (nicht das Original in den Vorlagen-Ordner bearbeiten) und dort umbenannt nach Muster "Ausschreibung – [Kunde] – per [Datum]" (z.B. "Ausschreibung – Kunde – per 01.01.2027")
- **Bearbeitung:** Dokument wird meist lokal heruntergeladen und offline bearbeitet; beim Speichern wird die Datei am ursprünglichen Ort automatisch überschrieben/synchronisiert (vermutlich durch die SharePoint-Verknüpfung), ohne dass explizit wieder hochgeladen werden muss

### Schritt 3: Mail an aktuellen Versicherer – Bestellung Fahrzeugverzeichnis, Rendement, ggf. Einzelschadenliste

- **Vorlage:** aktuell keine Standard-Mailvorlage, wird jedes Mal neu geschrieben (Silvan kennt den Ablauf auswendig). **Automatisierungskandidat:** Silvans eigenes Ziel ist eine Standardvorlage bzw. künftig ein automatisierter Versand.
- **Empfänger:** Versicherer haben für Broker dieser Grösse offiziell eine feste Ansprechperson ("Einflugschneise"), die intern weiterleitet. Silvan schickt die Anfrage teilweise bewusst direkt an den bekannten MF-Flotten-Underwriter, um Verzögerungen durch die interne Weiterleitung zu vermeiden.
- **Frist:** in der Regel 5 Arbeitstage, die der Gesellschaft gesetzt werden
- **Antwortdauer:** variiert stark, saisonal spürbar langsamer zwischen August und Oktober
- **Sonderfall Datenbeschaffung:** Bei manchen Gesellschaften kann das Rendement direkt über die Schnittstelle **Ecohub** heruntergeladen werden, statt es anzufragen. Fahrzeugliste und Einzelschadenliste müssen aber in jedem Fall per Mail bei der Gesellschaft bestellt werden – dafür gibt es keine Schnittstelle.

### Schritt 4: [folgt]

## Offene Punkte
- Weg 2, Option (c): gibt es weitere Möglichkeiten als "ausschreiben" oder "bisherigen Versicherer ohne Gegenofferte erneuern"?
- Tabelle Versicherer → typische Sanierungsschwelle, noch zu erfassen
- Genaue Ausgestaltung des Bestätigungsprozesses (Antrag/Formular): welche Angaben enthält das mitgesendete Formular, wer erstellt es?
- MF-Einzel hat bei Sanierung/PAK einen spürbar knapperen Zeitrahmen (1–3 Monate statt 6–12) – zu prüfen: braucht MF-Einzel später eine eigene, separate Prozessdatei statt nur Erwähnung hier?
- **Ausschreibungsvorlage** wurde als neue, Verlingue-eigene Vorlage aufgebaut (Datei `Ausschreibungsvorlage_Verlingue_MF.docx`), inkl. echtem Verlingue-Briefkopf/Logo (aus der Personal-Merkblatt-Vorlage übernommen) und einer generischen Deckungsvergleichstabelle (Wording/Deckungsbaustein × Versicherer A–D) als Ersatz für die ausgeschlossene Funk-Prisma-Tabelle. Bewusst vereinfacht: Wellen-Musterung des Original-Headers nicht nachgebaut. Silvan will die Vorlage zu einem späteren Zeitpunkt optisch weiter verfeinern – kein aktueller Blocker.
