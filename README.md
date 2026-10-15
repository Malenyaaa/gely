# Gely

**Geländer-Berechnung nach RiZ-ING**

Brückengeländer nach **RiZ-ING** (Straßenbrücken, Gel 3–7) oder **DB Ril 804.9060A01**
(Eisenbahnbrücken, A-GEL 1–6) teilen, prüfen und als **IFC 4** oder **DXF** nach Allplan
geben — auf geradem Bauwerk oder auf einer gekrümmten, geneigten Trasse.

**Im Browser öffnen: https://malenyaaa.github.io/gely/**

Alles steckt in einer einzigen HTML-Datei. Sie lädt nichts nach, schickt nichts weg und
rechnet vollständig im Browser; Ausgaben landen im Download-Ordner. Wer das Werkzeug ohne
Internet braucht, speichert `index.html` und öffnet sie lokal — sie läuft genauso.

## Was es kann

- Pfosten- und Füllstabteilung aus Gesamtlänge und Randabständen, mit Sonderfeldern
  (eigene Länge, ohne Füllung, Dehnfuge, anderer Typ)
- Prüfungen gegen die Vorgaben des gewählten Blatts: Pfostenabstand, Höhe, Holmabstände,
  Füllstabteilung, Endausbildung — jede Abweichung wird benannt, nichts wird stillschweigend
  angepasst
- Verankerung nach Gel 12 (einbetoniert), Gel 13 (Pfostenschuh) oder Gel 14 (Fußplatte
  gedübelt), samt Mörtelfuge
- Ergänzungen einzelner Bundesländer zur RiZ-ING (derzeit Hessen, Brandenburg)
- Export als IFC 4 (Volumenkörper je Bauteil), DXF-Ansicht und DXF-Schrägansicht in
  wählbarer Parallelprojektion
- Trasse: Achse aus einem Allplan-TCL-Export, selbst eingegeben oder aus gespeicherter JSON;
  das Geländer folgt Krümmung und Längsneigung

Die Richtzeichnungen selbst sind nicht enthalten. Das Werkzeug nennt bei jeder Vorgabe das
Blatt und den Abschnitt, aus dem sie stammt; gebaut wird nur, was dort bemaßt ist.

## Quellen

- RiZ-ING, Richtzeichnungen für Ingenieurbauten, Gruppe Gel (Bundesanstalt für Straßenwesen)
- DB Ril 804.9060A01, Konstruktionsgrundsätze für Geländer (DB InfraGO), gültig ab 01.10.2024
- Landesregelungen: Hessen Erg-ZTV-ING 11/2005, Brandenburg Merkblatt Bauwerksentwurf 08/2023

## Hinweis

Das Werkzeug ist eine Arbeitshilfe. Es ersetzt weder die Richtzeichnung noch die Prüfung
durch eine fachkundige Person; Ergebnisse sind vor der Verwendung zu kontrollieren. Keine
Gewähr.

Hier liegt nur die jeweils aktuelle Fassung des Werkzeugs; die Entwicklung läuft an anderer
Stelle. Fehler und Wünsche gern als Issue.

## Nutzung und Rechte

Das Werkzeug darf über die Website frei benutzt werden. Der Code darf nicht weiterverwendet
werden — nicht kopiert, verändert, eingebunden oder anderweitig veröffentlicht.

© 2026 Malenya. Alle Rechte vorbehalten.
