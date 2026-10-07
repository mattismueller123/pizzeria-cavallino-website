# Pizzeria Cavallino by Ory - Website

Eine moderne, responsive Website für die Pizzeria Cavallino in Niestetal Heiligenrode.

## Features

- **Modernes, minimalistisches Design** - Orientiert am eleganten Logo-Design
- **Responsive** - Funktioniert perfekt auf Desktop, Tablet und Smartphone
- **Vollständige Speisekarte** - Alle Gerichte übersichtlich kategorisiert
  - Vorspeisen
  - Salate
  - Pasta
  - Pizza
  - Fleischgerichte
  - Fischgerichte
  - Beilagen & Desserts
- **Bildergalerie** - Zeigt die Atmosphäre des Restaurants
- **Kontaktbereich** - Mit eingebetteter Google Maps Karte
- **Smooth Scrolling** - Elegante Navigation zwischen Sektionen
- **Animationen** - Subtile Fade-in Effekte für bessere UX

## Design-Elemente

- **Schriftarten**:
  - Cormorant Garamond (Serifen-Schrift für Überschriften)
  - Montserrat (Sans-Serif für Fließtext)
- **Farbschema**:
  - Primärfarbe: Dunkelgrau (#2c2c2c)
  - Akzentfarbe: Gold (#c9a961)
  - Hintergründe: Weiß und Creme-Töne
- **Layout**: Clean, luftig, fokussiert auf Inhalte

## Struktur

```
pizzeria-cavallino-website/
├── index.html          # Hauptseite
├── styles.css          # Styling
├── script.js           # JavaScript für Interaktivität
├── assets/
│   └── images/         # Bilder und Logo
└── README.md           # Diese Datei
```

## Installation & Nutzung

1. Alle Dateien auf einen Webserver hochladen
2. Die Website ist sofort einsatzbereit
3. Öffnen Sie `index.html` im Browser

### Lokales Testen

Sie können die Website lokal testen, indem Sie:
- Einfach die `index.html` im Browser öffnen, oder
- Einen lokalen Webserver starten:
  ```bash
  python -m http.server 8000
  ```
  Dann im Browser: `http://localhost:8000`

## Anpassungen

### Preise hinzufügen
Viele Gerichte haben aktuell noch keine Preise (-). Diese können in der `index.html` bei den entsprechenden Gerichten ergänzt werden:
```html
<span class="price">12,00 €</span>
```

### Kontaktdaten ergänzen
Im Kontaktbereich können Telefonnummer und genaue Öffnungszeiten hinzugefügt werden.

### Weitere Bilder
Einfach weitere Bilder im `assets/images/` Ordner ablegen und in der Galerie-Sektion einbinden.

## Browser-Kompatibilität

- Chrome/Edge (aktuell)
- Firefox (aktuell)
- Safari (aktuell)
- Mobile Browser (iOS Safari, Chrome Mobile)

## Technologien

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts

## To-Do / Erweiterungen

- [ ] Online-Bestellsystem integrieren
- [ ] Reservierungssystem hinzufügen
- [ ] Newsletter-Anmeldung
- [ ] Social Media Links
- [ ] Impressum & Datenschutzerklärung erstellen
- [ ] Mehrsprachigkeit (Deutsch/Englisch)
- [ ] Blog für News & Events

## Support

Bei Fragen oder Anpassungswünschen einfach melden!

---

Erstellt für Pizzeria Cavallino by Ory | Kleine Gasse 1, 34266 Niestetal
