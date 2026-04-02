# 🌍 GeoSpeech — Geography Learning App for Children

**GeoSpeech** teaches children geography through natural spoken conversation.
Just say *"travelling from Laos to Thailand then Cambodia"* — and the app plots the journey on a world map, calculates real distances, and reads back Wikipedia facts about each place.

> *"Just speak — and the world appears."*

No accounts. No subscriptions. No ads. Fully offline-capable.

---

## 📲 Download Android App

[![Download APK](https://img.shields.io/badge/Download%20APK-Latest%20Release-brightgreen?style=for-the-badge&logo=android)](https://github.com/wild-coder-ux/GeoSpeech/releases/latest)

> **Installation:** Settings → Security → enable **Install from unknown sources** → open the APK.

---

## 🎯 Who Is It For?

Children aged **7–14** who learn best by doing and talking — not tapping multiple-choice quizzes.
GeoSpeech is the only geography app where children learn by speaking naturally.

---

## 🗺️ How It Works

1. **Speak** — tap the microphone and say any journey e.g. *"from Chennai to London then New York"*
2. **Hear** — the app displays exactly what it heard
3. **Extract** — place names are pulled out using smart pattern matching (no internet AI needed)
4. **Map** — each place is geocoded via OpenStreetMap and plotted on a live map
5. **Route** — a dashed route line connects all stops with distances between each pair
6. **Learn** — Wikipedia facts are fetched and read aloud via text-to-speech

The entire flow from tap to map takes **under 5 seconds**.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎙️ Voice Input | Speak naturally — full journey phrases accepted |
| 🧠 Smart Extraction | NLP-style parsing extracts place names with no API |
| 🗺️ Live Map | Leaflet + OpenStreetMap — auto-fits all stops |
| 🏷️ Place Badges | Classifies each place: Country / State / City / District |
| 📏 Distances | Haversine straight-line distances between every stop |
| 📖 Wikipedia Facts | Auto-fetches child-friendly 2-sentence summaries |
| 🔊 Voice Readback | Reads places and facts aloud via device TTS |
| 🛤️ Journey Summary | Total route distance and ordered stop list |

---

## 🆚 How It Compares

| App | Free | Kids | Natural Speech | Voice | Offline |
|-----|------|------|----------------|-------|---------|
| **GeoSpeech** | ✅ | ✅ | ✅ | ✅ | ✅ |
| Seterra | ✅ | ✅ | ❌ Tap only | ❌ | ⚠️ Limited |
| GeoGuessr | 💰 Paid | ❌ | ❌ Tap only | ❌ | ❌ |
| StudyGe | ✅ | ⚠️ | ❌ Tap only | ❌ | ⚠️ Limited |
| Stack Countries | ✅ | ✅ | ❌ Tap only | ❌ | ✅ |

---

## 🛠️ Tech Stack

| Component | Role |
|-----------|------|
| HTML5 / CSS3 / JS | Core app — single self-contained file, no framework |
| Leaflet.js (local) | Offline-capable map rendering, bundled in assets |
| OpenStreetMap / Nominatim | Free geocoding — converts place names to coordinates |
| Wikipedia REST API | Free summary endpoint — CC BY-SA 4.0 |
| Web Speech API | Browser-native speech recognition, no key required |
| Android TTS | Native TextToSpeech, works fully offline |
| Android WebView | Java shell — handles permissions and JS bridge |

> The entire app is a single HTML file (~27KB) plus a local copy of Leaflet.js. Total APK under 2MB.

---

## 📋 Requirements

- Android 7.0+ (API 24) — covers 99%+ of active devices
- Internet required for: geocoding (Nominatim) and Wikipedia facts
- Speech recognition requires internet on most Android devices
- Map tiles cached locally after first use

---

## 📜 Open Source & Licences

GeoSpeech is dedicated to the open-source community. All code is freely available.

| Component | Licence |
|-----------|---------|
| GeoSpeech source code | MIT |
| Leaflet.js | BSD 2-Clause |
| OpenStreetMap tiles | ODbL |
| Nominatim geocoding | ODbL / Open Use |
| Wikipedia content | CC BY-SA 4.0 |
| Android SDK / WebView | Apache 2.0 |

Attribution is displayed in-app on every screen.

---

## 🔒 Privacy

GeoSpeech collects no personal data. See the full privacy policy at:
👉 [blazarcoder.com/geospeech-privacy.html](https://blazarcoder.com/geospeech-privacy.html)

---

## 🗺️ Roadmap

- Offline tile caching for fully offline school use
- Multi-language speech recognition
- Classroom mode — teacher sets a journey, students discover it
- Quiz mode — auto-generated questions after each journey
- Country flags alongside place cards
- Distance units toggle (km / miles)
- iOS version (same HTML, wrapped in WKWebView)

---

## 👤 Developer

Built by **wildtrain** — part of a suite of free, offline-first tools and apps.
