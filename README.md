# Die Gestirne – Orakel der Kritischen Theorie

**→ [lepettre.github.io/Halbbildung](https://lepettre.github.io/Halbbildung/)**

Ein Horoskop, das keines ist: Statt Sternzeichen-Prognosen liefert *Die Gestirne* bei jedem Aufruf ein Zitat von Theodor W. Adorno, Max Horkheimer, Walter Benjamin oder Herbert Marcuse – mit Quellenangabe, Pixel-Porträt und einer kreisenden 1-Bit-Planetenanimation. Der Mond steht dann zum Beispiel „im Zeichen Adorno“.

Der Witz liegt im Widerspruch: Adorno hat Astrologie und Okkultismus in den *Thesen gegen den Okkultismus* (Minima Moralia, Aph. 151) und in *The Stars Down to Earth* (1957) als Symptom gesellschaftlicher Regression beschrieben. Der Repository-Name verweist auf seine *Theorie der Halbbildung* (1959).

## Status

**Experimentell und nicht kommerziell.** Ein privates Spaß- und Bastelprojekt ohne Werbung, ohne Tracking und ohne Gewinnabsicht. Inhalte und Code können sich jederzeit ändern.

## Funktionen

- **Zufallsorakel:** 32 Zitate mit Quellenangabe, nie zweimal dasselbe hintereinander.
- **Planetenanimation:** neun Planeten auf gepunkteten Bahnen, als Pixelgrafik in einem Canvas gezeichnet. Die Stellung ist zufällig, nicht astronomisch.
- **Mondphase:** näherungsweise aus dem synodischen Monat berechnet.
- **Tag- und Nachtmodus:** Die Auswahl wird nur lokal im Browser gespeichert.
- **Web-App:** über das Manifest auf dem Homescreen installierbar.
- **Druckansicht für Thermodrucker** (Phomemo T02, 203 dpi, 48 mm Druckbreite): Über das Druck-Symbol unten links öffnet sich das aktuelle Orakel als 1-Bit-Bild in 384 px Breite. Unten steht ein QR-Code, der zurück zur Web-App führt, damit ein Horoskop auch als Sticker funktioniert.
- **Datensparsam:** eine einzige HTML-Datei ohne externe Bibliotheken, Schriften, Cookies oder Tracker. Eine strenge Content-Security-Policy verhindert, dass Inhalte nachgeladen werden.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | die komplette App (HTML, CSS, JavaScript) |
| `manifest.webmanifest` | Web-App-Manifest |
| `die-gestirne-icon-192.png`, `die-gestirne-icon-512.png`, `apple-touch-icon.png` | App-Icons |

Zum lokalen Testen genügt es, `index.html` im Browser zu öffnen. Veröffentlicht wird die Seite über GitHub Pages aus dem Branch `main`.

## Fremde Werke, Inspiration und Lizenzen

### Inspiration

Konzept und Gestaltung sind inspiriert von **[Hiro.Report](https://www.instagram.com/hiro.report/)** und seinem E-Ink-Gerät *The Heavens*. Code und Grafiken dieses Projekts wurden unabhängig neu erstellt; es wurden keine Dateien von Hiro.Report übernommen.

### Zitate

Die Zitate werden als kurze Belegstellen im Sinne von **§ 51 UrhG (Zitatrecht)** zum Zweck der Kulturkritik und Satire verwendet. Urheber und Quelle sind jeweils angegeben (§ 63 UrhG). Alle Rechte an den Originaltexten liegen bei den jeweiligen Rechteinhabern.

| Autor | Lebensdaten | Urheberrechtlicher Status (DE, 70 Jahre p. m. a.) |
|---|---|---|
| Walter Benjamin | 1892–1940 | gemeinfrei seit 2011 |
| Theodor W. Adorno | 1903–1969 | geschützt bis Ende 2039 |
| Max Horkheimer | 1895–1973 | geschützt bis Ende 2043 |
| Herbert Marcuse | 1898–1979 | geschützt bis Ende 2049 |

Die Marcuse-Zitate stammen aus der deutschen Übersetzung von *One-Dimensional Man* (*Der eindimensionale Mensch*, 1967, übersetzt von Alfred Schmidt). Einige Zitate sind gekürzt oder sinngemäß wiedergegeben. Hinweise auf Fehler sind willkommen.

### Grafiken

Planetenanimation, Porträts und Icons sind eigene, stark vereinfachte Pixelgrafiken. Die Porträts sind bewusst schematisch gehalten und keine Nachbildungen bestimmter Fotografien.

### Schrift

Die Seite verweist im Stylesheet auf **VT323** (© The VT323 Project Authors, [SIL Open Font License 1.1](https://openfontlicense.org)), bettet die Schrift aber nicht ein und liefert sie nicht aus. Ist sie auf dem Gerät nicht installiert, wird die Systemschrift Courier New bzw. eine Monospace-Schrift verwendet.

### QR-Code

Die QR-Code-Matrix in der Druckansicht wurde einmalig mit der Python-Bibliothek [segno](https://github.com/heuer/segno) (BSD-3-Clause) erzeugt und als Daten in `index.html` eingebettet. Code von segno ist nicht Bestandteil des Projekts.
„QR Code“ ist eine eingetragene Marke der DENSO WAVE INCORPORATED.

### Hosting

Die Seite wird über [GitHub Pages](https://pages.github.com) gehostet (GitHub, Inc., USA). Details stehen in der Datenschutzerklärung der Seite.

## Lizenz des Projekts

Für den eigenen Code und die eigenen Grafiken ist derzeit keine Open-Source-Lizenz vergeben, es gelten die gesetzlichen Regeln (alle Rechte vorbehalten). Die oben genannten fremden Werke unterliegen ihren eigenen Bedingungen.

## Kontakt

J. Petter, 20457 Hamburg – info[at]jan-petter.de
Impressum und Datenschutz: auf der [Website](https://lepettre.github.io/Halbbildung/#impressum)
