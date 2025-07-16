# 🎯 HeimZeiger - Zufällige Namensauswahl

Eine interaktive Web-App, die einen zufälligen Namen aus einer Liste von 25 Namen auswählt. Die Person im Zeiger-Bild zeigt auf den ausgewählten Namen, der in der linken oberen Ecke erscheint.

## ✨ Features

- **Zufällige Auswahl**: Aus 25 vordefinierten Namen
- **Animierte Auswahl**: Namen laufen durch bis zur finalen Auswahl
- **Visueller Zeiger**: Transparentes Zeiger-Bild zeigt auf den ausgewählten Namen
- **Responsive Design**: Funktioniert auf Desktop und Mobile
- **Moderne UI**: Mit Tailwind CSS und Vue.js

## 🚀 Schnellstart

1. Öffne `index.html` in einem Webbrowser
2. Klicke auf "Start" um die Namensauswahl zu beginnen
3. Schaue zu, wie die Namen durchlaufen und der Zeiger auf das Ergebnis zeigt

## 🛠 Technologie

- **Vue.js 3** (über CDN)
- **Tailwind CSS** (über CDN)
- **Vanilla HTML/CSS/JS**
- Keine Build-Tools erforderlich

## 📦 Vercel Deployment

Diese App ist bereit für die Bereitstellung auf Vercel:

1. Pushe das Repository zu GitHub/GitLab
2. Verbinde es mit Vercel
3. Deploy - keine weitere Konfiguration nötig!

Oder verwende Vercel CLI:
```bash
npx vercel --prod
```

## 📁 Projektstruktur

```
HeimZeiger/
├── index.html      # Haupt-App-Datei
├── Zeiger.png      # Zeiger-Bild (Person mit transparentem Hintergrund)
├── README.md       # Dokumentation
└── vercel.json     # Vercel-Konfiguration
```

## 🎮 Verwendung

1. **Start**: Klicke auf den "Start" Button
2. **Animation**: Namen laufen durch (3-5 Sekunden)
3. **Ergebnis**: Der finale Name wird hervorgehoben
4. **Wiederholen**: Klicke "Nochmal" für eine neue Auswahl

## 📝 Namen anpassen

Die Namen können in der `index.html` Datei im `names` Array angepasst werden:

```javascript
names: [
    'Anna Schmidt', 'Max Müller', 'Lisa Weber',
    // ... weitere Namen hinzufügen
]
```

## 🎨 Design-Anpassungen

- Farben können über Tailwind CSS Klassen angepasst werden
- Animationsgeschwindigkeit ist im JavaScript konfigurierbar
- Zeiger-Bild kann durch Ersetzen von `Zeiger.png` geändert werden

## 📱 Browser-Kompatibilität

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Beitrag

Verbesserungen und Erweiterungen sind willkommen! Erstelle einfach einen Pull Request.

## 📄 Lizenz

MIT License - Freie Nutzung für alle Zwecke. 