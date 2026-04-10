# 🏔️ Alpine Power Tracker — PWA

**16-Wochen Rad-Vorsaison für alpine Rennläufer · FTP 270W · Slalom & Riesenslalom**

Eine Progressive Web App (PWA) — funktioniert **offline**, kann als App auf dem Handy installiert werden.

---

## 📱 Auf dem Handy installieren (nach dem Deployment)

### iPhone / Safari
1. Seite im Safari öffnen
2. Teilen-Symbol tippen (☐↑)
3. „Zum Home-Bildschirm" wählen
4. „Hinzufügen" tippen → App erscheint auf dem Startbildschirm

### Android / Chrome
1. Seite in Chrome öffnen
2. Banner erscheint automatisch: „App installieren" tippen
3. Oder: Menü (⋮) → „App installieren"

---

## 🚀 GitHub Pages Setup (Schritt für Schritt)

### 1. Repository erstellen
1. Gehe zu [github.com](https://github.com) und melde dich an
2. Klicke auf **„New"** (grüner Button oben rechts)
3. Repository Name: `alpine-tracker` (oder beliebig)
4. Sichtbarkeit: **Public** (für GitHub Pages kostenlos)
5. Klicke **„Create repository"**

### 2. Dateien hochladen
1. Im neuen Repository: **„Add file" → „Upload files"**
2. Lade alle Dateien hoch:
   - `index.html` ← **Pflicht**
   - `sw.js` ← **Pflicht** (Offline-Funktion)
   - `manifest.json` ← **Pflicht** (App-Installation)
   - `icon-192.svg` ← Empfohlen (App-Icon)
   - `icon-512.svg` ← Empfohlen (App-Icon)
3. Klicke **„Commit changes"**

### 3. GitHub Pages aktivieren
1. Im Repository: **Settings** (Zahnrad-Tab oben)
2. Linke Sidebar: **Pages**
3. Unter „Source": **„Deploy from a branch"**
4. Branch: **`main`**, Ordner: **`/ (root)`**
5. Klicke **„Save"**
6. Nach 1–2 Minuten erscheint die URL:
   `https://DEIN-USERNAME.github.io/alpine-tracker/`

### 4. App öffnen & installieren
- URL im Handy-Browser öffnen
- Als App installieren (siehe oben)
- **Fertig!** 🎿

---

## ✅ Features

| Feature | Status |
|---------|--------|
| Alle 16 Wochen / 5 Phasen | ✅ |
| Einheiten abhaken (Checkbox) | ✅ |
| Fortschritt wird gespeichert | ✅ LocalStorage |
| Offline-Funktion | ✅ Service Worker |
| Als App installierbar | ✅ PWA Manifest |
| iPhone / Android | ✅ |
| Ernährungshinweise | ✅ |
| Regenerationshinweise | ✅ |
| Zonen-Referenz (Z1–Z6) | ✅ |

---

## 🔧 Trainingsparameter

- **FTP:** 270 W (3,0 W/kg bei 90 kg)
- **Sportart:** Radfahren (Ergometer / Outdoor)
- **Ziel:** Optimale Vorbereitung für Slalom & Riesenslalom
- **Struktur:** 3:1 Belastung/Regeneration

### Intensitätszonen (FTP 270 W)
| Zone | Bereich | Beschreibung |
|------|---------|--------------|
| Z1 | < 162 W | Regeneration |
| Z2 | 162–216 W | Grundlage |
| Z3 | 216–243 W | Sweetspot |
| Z4 | 243–297 W | Schwelle (FTP) |
| Z5 | 297–351 W | VO₂max |
| Z6 | > 351 W | Anaerob |

---

## 📂 Dateistruktur

```
alpine-tracker/
├── index.html      ← Haupt-App (alles drin)
├── sw.js           ← Service Worker (Offline)
├── manifest.json   ← PWA-Manifest (App-Installation)
├── icon-192.svg    ← App-Icon klein
├── icon-512.svg    ← App-Icon groß
└── README.md       ← Diese Datei
```

---

*Erstellt mit Claude · Anthropic*
