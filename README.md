# Bild-Teiler

Web-App, die Bilder in der Mitte teilt: Die rechte Hälfte ist die Vorderseite, per Tippen dreht sich die Karte um und zeigt die linke Hälfte.

- Karten lassen sich verschieben, zoomen, mehrfach auf die Fläche legen und in Kästen (auch verschachtelt) sortieren.
- Die Bibliothek ist ein Seitenmenü (ein- und ausklappbar, links oder rechts) mit Ordnern und Unterordner. Klick öffnet einen Ordner, Doppelklick legt alle Bilder darin auf die Fläche.
- „Ordner mit Bildern“ (oder einen Ordner auf die Seite ziehen) legt in der Bibliothek einen Ordner mit gleichem Namen an.
- „Alle Karten“ öffnet per Klick ein Menü: alle auf Bild, alle auf Wort oder alle umdrehen.
- Ein Ordner, der auf die Fläche gezogen wird, legt seine Bilder als Gruppe nebeneinander ab.
- „Hinzufügen“ öffnet ein Auswahlfeld: Bilder, Ordner mit Bildern oder PDF mit Karten (ein PDF lässt sich auch auf die Seite ziehen). Bei einem PDF erkennt die App die Karten (Tabellen und Raster mit Linien, jeweils ein Feld links und eins rechts) und zeigt sie einzeln mit Namen. Der Name ist die erste Textzeile der Karte ohne Artikel und Zeichen und lässt sich ändern. Sind Karten falsch zugeschnitten, öffnet „Karten zuschneiden“ die PDF-Seite, auf der sich die Rahmen verschieben, in der Größe ändern, löschen und neu aufziehen lassen. Die Karten landen als Ordner in der Bibliothek. Alles läuft im Browser.
- „Zurück“ (Strg/Cmd + Z) macht den letzten Schritt rückgängig.
- „Genus“ blendet die frei verschiebbaren Zeichen die~ das^ der° ein und aus.
- Läuft komplett im Browser. Es werden keine Bilder oder Daten an einen Server gesendet.
- Bilder und Anordnung bleiben im Browser des jeweiligen Geräts gespeichert (IndexedDB und localStorage).
- Auf dem iPad: Seite in Safari öffnen, „Teilen“ und „Zum Home-Bildschirm“ wählen. Danach startet sie wie eine App, auch offline.
- Der PDF-Import nutzt pdf.js (Mozilla, Apache License 2.0), das komprimiert in der Datei steckt.
