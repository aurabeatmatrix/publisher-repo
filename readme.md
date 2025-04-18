# Publisher Repository für Musikprojekte

**Copyright © Aura Beat Matrix. All rights reserved.**

Dieses Repository dient als zentrales Publisher-Repo für meine Musikprojekte, in dem **Songtexte**, **Album-Cover**, **Social-Media-Thumbnails** sowie die zugehörigen **Audio- (MP3)** und **Video-Releases (MP4)** organisiert werden. Die Lyrics stammen teils aus eigenen Kreativprozessen, teils werden sie mithilfe von KI generiert. Die eigentlichen Songs werden mit Suno AI produziert.

## 📁 Ordnerstruktur

Jedes Lied erhält einen eigenen Unterordner mit folgendem Aufbau:

```
/                      # Wurzelverzeichnis
├── song-1/            # Ordner für Song 1
│   ├── lyrics/        # Songtexte
│   │   ├── displayed.md    # Anzeigeversion (Markdown)
│   │   └── original.txt    # Rohtext
│   ├── covers/        # Album-Cover in verschiedenen Formaten
│   │   ├── cover-16-9.jpg
│   │   ├── cover-2-3.jpg
│   │   ├── cover-3-4.jpg
│   │   └── …
│   ├── thumbnails/    # Social-Media-Thumbnails
│   │   ├── thumb-instagram-1080x1080.jpg
│   │   ├── thumb-youtube-1280x720.jpg
│   │   └── thumb-tiktok-1080x1920.jpg
│   └── releases/      # Veröffentlichungen
│       ├── song1.mp3
│       └── song1.mp4
└── song-2/            # Ordner für Song 2 (analog zu song-1)
    └── …
```

## 📝 Lyrics

- **displayed.md**: Ausformatiert in Markdown für schnelle Vorschau und Veröffentlichung auf Webplattformen.
- **original.txt**: Rohfassung der Lyrics, inkl. KI-generierter und selbstgeschriebener Passagen.

## 🎨 Cover und Thumbnails

- **covers/** enthält unterschiedliche Seitenverhältnisse für diverse Plattformen (Spotify, Apple Music, etc.).
- **thumbnails/** enthält optimierte Vorschaubilder für Instagram, YouTube, TikTok und andere Social-Media-Kanäle.

## ▶️ Releases

- **songX.mp3**: Audio-Datei in hoher Qualität (320 kbps).
- **songX.mp4**: Video-Release mit einfachem Visual (z.B. Cover-Slide mit Audio-Hintergrund).

## 🚀 Verwendung

1. Klone das Repository:
   ```bash
   git clone https://github.com/DEIN_USER/publisher-repo.git
   ```
2. Navigiere in den gewünschten Song-Ordner:
   ```bash
   cd publisher-repo/song-1
   ```
3. Öffne die Markdown-Datei oder teste die Releases lokal.

## 🤝 Beiträge

Beiträge sind willkommen! Bitte öffne Pull Requests für:

- Korrekturen oder Optimierungen der Lyrics
- Neue Cover-Designs und Thumbnails
- Weitere Formate oder Plattform-Anpassungen

## 📜 Lizenz

> **Copyright © Aura Beat Matrix. All rights reserved.**

> Für die mit Suno AI erstellten Werke gelten zusätzlich die Nutzungsbedingungen von Suno.
