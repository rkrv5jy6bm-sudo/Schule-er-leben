# Schule (er)leben · LTEtt

Öffentliche Dokumentenseite (GitHub Pages, Branch `main`, `.nojekyll`) zum Pé „Schule (er)leben“, gleicher Stil wie windmobile-erasmus.

- Live: https://rkrv5jy6bm-sudo.github.io/schule-er-leben/
- Dossier de candidature nur als geschwärzte Fassung (Seite 1 ohne IAM-Kennungen und Unterschrift, als Bild neu aufgebaut)

- `index.html` – Projektseite (Unterlagen, Meilensteine, Bausteine, Jahre) in einer Datei (CSS + JS inline, LTEtt-Logo als WebP-Data-URI)
- `docs/` – Unterlagen; PPTX/DOCX zusätzlich als PDF zum direkten Ansehen
- Neues Dokument: Datei nach `docs/`, Eintrag im Array `DOCS` in `index.html` ergänzen (cat: CCPÉ / Präsentation / Vorlage)
- Links relativ (`docs/...`), Breakpoint 900 px, Hell/Dunkel-Modus
- `journee.html` – eigene Seite Journée pédagogique 29.10.2026: Programm (Zeitraster, Array `JP`), Folien-Viewer Kick-off (`docs/kickoff/folie-NN.jpg`, `mini-NN.jpg`), Formulare
- Forms-Links in `journee.html` im Objekt `FORMS` eintragen (`bestand` = Online-Formular 15 Fragen, `modul` = Unterrichtsmodul); leer = „Link zum Formular folgt“
- Beide Seiten teilen Navigation (`.topnav`) und dieselben Tokens; CSS-Änderungen in beiden Dateien nachziehen
