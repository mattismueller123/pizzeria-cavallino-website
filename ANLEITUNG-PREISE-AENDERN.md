# Anleitung: Preise ändern und neue Gerichte hinzufügen

## 📝 Preise ändern

### Schritt 1: Datei öffnen
Öffne die Datei `index.html` mit einem Text-Editor (z.B. Notepad++, Sublime Text, VS Code)

### Schritt 2: Gericht finden
Suche nach dem Namen des Gerichts, z.B. "Pizza Margherita"

### Schritt 3: Preis ändern
Finde die Zeile mit dem Preis:
```html
<span class="price">8,50 €</span>
```

Ändere den Preis:
```html
<span class="price">9,50 €</span>
```

### Beispiel - Kompletter Eintrag:
```html
<div class="menu-item">
    <div class="menu-item-header">
        <h4>Pizza Margherita</h4>
        <span class="price">8,50 €</span>
    </div>
    <p>Mit Tomatensauce</p>
</div>
```

---

## ➕ Neue Gerichte hinzufügen

### Schritt 1: Richtige Kategorie finden
Finde die Kategorie in der `index.html`, wo das neue Gericht hin soll:
- Vorspeisen: `data-category="vorspeisen"`
- Salate: `data-category="salate"`
- Pasta: `data-category="pasta"`
- Pizza: `data-category="pizza"`
- Fleischgerichte: `data-category="fleisch"`
- Fischgerichte: `data-category="fisch"`
- Beilagen: `data-category="beilagen"`

### Schritt 2: Neues Gericht einfügen
Kopiere einen bestehenden Eintrag und füge ihn in die gewünschte Kategorie ein:

```html
<div class="menu-item">
    <div class="menu-item-header">
        <h4>NEUER GERICHTNAME</h4>
        <span class="price">12,50 €</span>
    </div>
    <p>Beschreibung des Gerichts mit Zutaten</p>
</div>
```

### Beispiel - Neue Pizza hinzufügen:

**Vorher:**
```html
<div class="menu-item">
    <div class="menu-item-header">
        <h4>Pizza Salami</h4>
        <span class="price">9,50 €</span>
    </div>
</div>
```

**Nachher** (neue Pizza darunter):
```html
<div class="menu-item">
    <div class="menu-item-header">
        <h4>Pizza Salami</h4>
        <span class="price">9,50 €</span>
    </div>
</div>
<div class="menu-item">
    <div class="menu-item-header">
        <h4>Pizza Speziale</h4>
        <span class="price">13,50 €</span>
    </div>
    <p>Mit Schinken, Champignons, Paprika und Oliven</p>
</div>
```

---

## 🗑️ Gerichte entfernen

Um ein Gericht zu entfernen, lösche einfach den kompletten Block:

```html
<!-- DIESEN KOMPLETTEN BLOCK LÖSCHEN -->
<div class="menu-item">
    <div class="menu-item-header">
        <h4>Pizza Hawaii</h4>
        <span class="price">10,50 €</span>
    </div>
    <p>Mit Schinken und Ananas</p>
</div>
<!-- BIS HIERHER -->
```

---

## 💡 Tipps

1. **Backup erstellen**: Vor Änderungen immer eine Kopie der `index.html` speichern!
2. **Browser-Cache leeren**: Nach Änderungen ggf. Cache leeren (Strg+F5)
3. **Konsistenz**: Achte auf einheitliche Formatierung
4. **Sonderzeichen**: Umlaute (ä, ö, ü) und ß funktionieren normal

---

## 📞 Öffnungszeiten & Telefon ändern

Suche in der `index.html` nach "Öffnungszeiten" oder "Telefon":

```html
<h3>Telefon</h3>
<p><a href="tel:05617034704">0561 / 70 34 704</a></p>

<h3>Öffnungszeiten</h3>
<p><strong>Montag - Samstag</strong><br>17:00 - 22:00 Uhr</p>
```

Einfach die Texte/Zeiten ändern und speichern.

---

## 🔄 Änderungen hochladen

Nach allen Änderungen:
1. Datei `index.html` speichern
2. Per FTP auf den Webserver hochladen
3. Website im Browser neu laden (F5)

---

## ⚠️ Wichtig

- **HTML-Struktur** nicht kaputt machen (Tags nicht entfernen!)
- **Testen**: Nach Upload immer die Website testen
- Bei Unsicherheit: Professionelle Hilfe holen

---

Bei Fragen oder Problemen einfach melden!
