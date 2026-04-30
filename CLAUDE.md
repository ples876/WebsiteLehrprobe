# Lehrprobe – Fake-News-Website

Statische Website (HTML/CSS, kein Framework) für eine Französisch-Lehrprobe (B2). Optisch an lemonde.fr angelehnt. Kein Build-Schritt – Dateien per Doppelklick oder GitHub Pages öffenbar.

## Dateien

- `index.html` – Startseite (Le-Monde-Stil)
- `article.html` – der Fake-Artikel (Kernstück)
- `style.css` – gemeinsames Styling
- `assets/` – hier KI-generiertes Bild für den Theater-Brand ablegen (`theatre-feu.avif`)

## Fake-News-Marker im Artikel

Vier subtile Marker für B2-Schüler (Théâtre national de l'Odéon, Montparnasse):

1. **Domain falsch** – `lemonde-info.fr` statt `lemonde.fr` (Footer + Share-Box)
2. **Erfundener Direktor** – „Thomas Pesquet" ist in Frankreich als Astronaut bekannt, nicht als Theaterdirektor
3. **Erfundene Universität** – „université de Valmont-sur-Loire" existiert nicht
4. **Fake-News-Aufruf am Ende** – „il est essentiel de partager cette information rapidement" ist untypisch für seriösen Journalismus

Optionaler 5. Marker: KI-Bild mit Artefakten (noch Platzhalter).

## Design-Referenz

- Schwarzer Header mit Fraktur-Logo (UnifrakturCook), gelber „S'abonner"-Button
- Weißer Hintergrund, roter Akzent (`#e63946`)
- Alert-Bar mit Breaking-News-Ticker
- Gelbes „M"-Quadrat für Abonnenten-Artikel (kein Schloss)
- Kartenbilder: Picsum-Platzhalter – ersetzen mit Unsplash-Downloads in `assets/`

## Deployment

GitHub Pages: Branch `main`, Folder `/ (root)`.
URL: `https://ples876.github.io/WebsiteLehrprobe`
