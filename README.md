# Zählerblick Website

Website: https://deewayner.github.io/zaehlerblick/
App Store: https://apps.apple.com/de/app/z%C3%A4hlerblick/id6796361270

## Änderungen veröffentlichen
Dieses Repository ist die Quelle der öffentlichen Website. Jeder Push auf `main` veröffentlicht die Website automatisch über den vorhandenen GitHub-Pages-Workflow. Den Fortschritt zeigt der Reiter **Actions** auf GitHub.

Mit GitHub Desktop: Repository klonen, Dateien bearbeiten, Änderungen committen und **Push origin** wählen. Danach erscheint die Änderung automatisch online, sobald der Pages-Lauf erfolgreich beendet ist. Änderungen nur auf deinem Computer werden erst nach dem Push veröffentlicht.

Direkt auf GitHub: Datei öffnen, bearbeiten und nach `main` committen.

## Lokal ansehen
`index.html` im Browser öffnen oder im Website-Ordner `python3 -m http.server 8080` starten und http://localhost:8080 aufrufen. Kein Build und keine Installation nötig.

## Dateien
- index.html: Startseite inklusive App-Store-Links
- styles.css: Farben, Layout und mobile Darstellung
- script.js: interaktive App-Ansichten mit Tastatursteuerung
- assets/: Original-App-Icon und Screenshots
- support.html / datenschutz.html: Support und Datenschutz der App
- ANALYSE.md: Funktionsbelege aus dem Quellprojekt

Keine externen Fonts oder Analyse-Skripte im Website-Code. Vor der weiteren öffentlichen Nutzung Betreiberangaben/Impressum und eine auf das tatsächliche Hosting abgestimmte Website-Datenschutzerklärung prüfen/ergänzen; die enthaltene Datenschutzerklärung beschreibt die App.
