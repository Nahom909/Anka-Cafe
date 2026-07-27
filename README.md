# Anka Café – Website

Website für das **Anka Café** – türkisches Café &amp; Patisserie, Hauptstraße 43, 63303 Dreieich.

Statische Seite ohne Build-Step (eine HTML-Datei je Seite), deutschsprachig.

## Struktur

- `index.html` – Startseite (cinematischer Header, Über uns, Highlights, Speisekarte, Galerie, Kontakt &amp; Öffnungszeiten)
- `impressum.html` · `datenschutz.html` – Rechtsseiten (`noindex`)
- `images/` – Bildmaterial (aktuell repräsentative Platzhalter, vor dem Launch durch echte Fotos ersetzen)
- `images/icons/favicon.svg` – Favicon

## Technik

- Schriften: Google Fonts (Fraunces + Work Sans) – einzige externe Einbindung
- Keine Cookies, kein Tracking, keine eingebetteten Widgets/Karten (DSGVO-freundlich, kein Consent-Banner nötig)
- Animationen mit `prefers-reduced-motion`-Fallback

## Noch zu ergänzen

- Echte Fotos des Cafés in `images/`
- E-Mail-Adresse, Gästestimmen, Inhaber-Angaben in Impressum/Datenschutz (im Code mit `[ ]` markiert)

---
Vorschau: `index.html` im Browser öffnen.
