# Sourci Website - GitHub Pages Setup

Diese Dateien sind für GitHub Pages hosting vorbereitet.

## 📁 Struktur

- `index.html` - Hauptseite / Marketing-URL
- `support.html` - Support-Seite / Support-URL
- `privacy.html` - Datenschutzerklärung (erforderlich für App Store)
- `terms.html` - Nutzungsbedingungen
- `README.md` - Diese Datei

## 🚀 GitHub Pages aktivieren

### Schritt 1: GitHub Repository erstellen

1. Gehe zu GitHub.com und logge dich ein
2. Klicke auf "New Repository"
3. Name: `sourci-website` (oder beliebig)
4. Public repository (für kostenloses Pages hosting)
5. Klicke "Create repository"

### Schritt 2: Code hochladen

Im Terminal (im `docs` Ordner):

```bash
# Git initialisieren (falls noch nicht)
cd /Users/macbook/Desktop/Sourci/Sourci/docs
git init

# Dateien hinzufügen
git add .
git commit -m "Initial website for App Store"

# Mit GitHub verbinden (ersetze USERNAME und REPO)
git remote add origin https://github.com/USERNAME/sourci-website.git
git branch -M main
git push -u origin main
```

### Schritt 3: GitHub Pages aktivieren

1. Gehe zu deinem Repository auf GitHub
2. Klicke auf "Settings"
3. Scrolle zu "Pages" (linkes Menü)
4. Bei "Source" wähle: `main` branch und `/ (root)` folder
5. Klicke "Save"
6. Warte 2-3 Minuten

### Schritt 4: URLs erhalten

Deine Website ist jetzt verfügbar unter:

```
https://USERNAME.github.io/sourci-website/
```

**Für App Store Connect nutzen:**

- **Marketing-URL:** `https://USERNAME.github.io/sourci-website/`
- **Support-URL:** `https://USERNAME.github.io/sourci-website/support.html`
- **Privacy Policy:** `https://USERNAME.github.io/sourci-website/privacy.html`

## ✅ Vor dem Hochladen anpassen

1. **E-Mail Adressen ändern:**
   - `support@sourci.com` → Deine echte Support-E-Mail
   - `privacy@sourci.com` → Deine echte E-Mail
   - `legal@sourci.com` → Deine echte E-Mail
   - `business@sourci.com` → Deine echte E-Mail

2. **App Store Link ändern:**
   - Ersetze `https://apps.apple.com` mit deinem echten App Store Link

3. **Copyright anpassen:**
   - Falls du einen Firmennamen hast, ersetze "Sourci"

## 🎨 Anpassungen

Die Webseiten nutzen:
- Gradient-Design in Lila/Blau
- Responsive Design (funktioniert auf allen Geräten)
- Keine externen Dependencies (alles ist self-contained)
- Apple-Style Design

## 📝 Inhalte

### index.html
- Marketing-Seite mit Features
- Download-Links
- Produktkategorien
- Statistiken

### support.html
- FAQ (Häufig gestellte Fragen)
- Kontaktinformationen
- Technischer Support
- Business Inquiries

### privacy.html
- Vollständige Datenschutzerklärung
- GDPR-konform
- App Store Anforderungen erfüllt

### terms.html
- Nutzungsbedingungen
- B2B-spezifische Bedingungen
- Rechtliche Absicherung

## 🔧 Support

Bei Fragen zu GitHub Pages:
https://docs.github.com/en/pages

## ✨ Features

✅ Kostenlos
✅ SSL/HTTPS automatisch
✅ Schnelles Hosting
✅ Professional Design
✅ Mobile-friendly
✅ SEO-optimiert
✅ Alle App Store Anforderungen erfüllt
