# Digitaler Nachlass Verwalter

Ihr umfassender Ratgeber für die Verwaltung des digitalen Nachlasses.

## 🚀 Technologie-Stack

- **Framework**: Astro 4.x (Static Site Generation)
- **Styling**: TailwindCSS
- **Hosting**: Firebase Hosting
- **Deployment**: GitHub Actions (CI/CD)
- **Analytics**: Plausible (DSGVO-konform, cookieless)

## 📋 Features

- ✅ Vollständig responsive Design (Mobile-first)
- ✅ SEO-optimiert mit Meta-Tags und Schema.org Strukturdaten
- ✅ Schnelle Ladezeiten und hohe Performance
- ✅ Datenschutzfreundliches Analytics (Plausible)
- ✅ Automatisches Deployment via GitHub Actions
- ✅ Deutsche Sprache und DSGVO-konform

## 🛠️ Lokale Entwicklung

```bash
# Dependencies installieren
npm install

# Dev Server starten
npm run dev

# Build erstellen
npm run build

# Build Preview
npm run preview
```

## 📦 Deployment

Die Website wird automatisch via GitHub Actions bei jedem Push auf den `main` Branch deployed:

1. Build wird erstellt (`npm run build`)
2. Deployment zu Firebase Hosting
3. Live unter: https://digitaler-nachlass-verwalter.de

## 🔧 Konfiguration

- **Astro Config**: `astro.config.mjs`
- **TailwindCSS**: `tailwind.config.mjs`
- **Firebase**: `firebase.json`, `.firebaserc`
- **GitHub Actions**: `.github/workflows/deploy.yml`

## 📄 Struktur

```
src/
├── layouts/          # Layout-Komponenten
│   └── Layout.astro
├── pages/            # Seiten (Routes)
│   ├── index.astro
│   ├── impressum.astro
│   └── datenschutz.astro
├── content/          # Content Collections
│   └── config.ts
└── components/       # Wiederverwendbare Komponenten

public/               # Statische Assets
├── favicon.svg
├── sitemap.xml
└── robots.txt
```

## 📝 Wichtige Themen

Die Website behandelt folgende Hauptthemen:

- Digitale Konten und Zugangsdaten verwalten
- Passwörter sicher aufbewahren
- Social Media Profile regeln
- Cloud-Speicher und digitale Daten
- Rechtliche Aspekte (BGH-Urteil 2018)
- Vorsorgevollmacht und Testament
- Praktische Schritte zur Verwaltung

## 🔐 Sicherheit & Datenschutz

- Keine Cookies für Tracking
- DSGVO-konforme Analytics (Plausible)
- Keine Speicherung personenbezogener Daten
- Privacy-by-Design Ansatz

## 📞 Support

Bei Fragen oder Problemen siehe Impressum auf der Website.

---

**Erstellt mit ❤️ und [Astro](https://astro.build)**
