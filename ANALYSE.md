# Projektanalyse – Zählerblick

Quelle: bereitgestelltes MeterLog.zip, Stand der enthaltenen Dateien 17.10.2026. Statische Quellcodeanalyse; die iOS-App wurde nicht kompiliert oder auf einem Gerät getestet.

## Produkt und UI
SwiftUI-App mit Übersicht, Zählern, Erfassung, Statistik und Mehr-Bereich. Das Designsystem verwendet Blau/Türkis, abgerundete Karten, systemnahe Typografie und Kategorieakzente (Strom orange, Wasser blau, Gas rot, Auto indigo). Die Website greift diese Gestaltung auf. Originalbilder stammen aus AppStore/Screenshots/1.0.5-real und Assets.xcassets/AppIcon.appiconset.

## Belegte Inhalte
- Zählertypen und eigene Einheiten: Meter.swift, AddMeterView.swift, MeterSupport.swift.
- Manuelle Erfassung: AddEntryView.swift, EditEntryView.swift.
- Dashboard, Kosten und Verlauf: DashboardView.swift, MeterDetailView.swift.
- Jahresverbrauch: MeterStatsView.swift.
- CSV-Import/-Export und JSON-Backup: ContentView.swift, Import-/Exportaktionen.
- Pro: ProSupport.swift (StoreKit und Freischaltung), ProViews.swift (Smart-Auswertung, Komfortfunktionen), MeterScanView.swift (Vision OCR), MeterLogWidget/.
- Lokale Speicherung und derzeit deaktivierter iCloud-Sync: CloudAndWidgetSupport.swift. Kein aktiver Sync beworben.
- Marketing-Abgleich: AppStore/metadata-de.md.
- Kontakt und App-Datenschutz: docs/support.html, docs/datenschutz.html.

## Bewusste Grenzen
Keine Bewertungen, Nutzerzahlen, Einsparversprechen, Preise oder Store-Verfügbarkeit erfunden. Pro-Funktionen sind gekennzeichnet. Screenshot-Werte sind als Beispieldaten markiert. App-Store-Link vom Nutzer am 18.10.2026 bestätigt und als CTA eingebunden. Keine automatische Live-Ablesung behauptet. Datenschutztext aus dem Projekt übernommen, keine juristische Prüfung.
