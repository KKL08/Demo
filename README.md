# Demo

[中文版](./README.zh.md)

AI demos built with Google Gemini, deployed on Google Cloud Run.

> **Note:** These demos are live for exploration only — no longer actively maintained or updated. Links may go offline at any time.

---

## 🌸 Cyber Anime Pilgrimage (赛博圣地巡礼)

> Drop your favorite anime characters into their real-world locations — no plane ticket required.

Upload a character image and enter an anime title. The app looks up real-world pilgrimage sites (*seichi*, 聖地) from that series and generates a photo of your character actually there.

**Features**
- 🗺️ AI site research — surfaces real-world locations and the stories behind them
- 📸 Character scene integration — seamlessly blends 2D characters into real-world scenery
- 💾 Saved history — keeps your last 5 pilgrimages
- ⬇️ One-click download

---

## 📷 AI Travel Camera

> Pick anywhere on Earth, get a photo that matches the real weather there — or jump to a different century entirely.

Choose a location on the map (or hit "Random"), and the app pulls live weather for that spot. Gemini generates an image grounded in those actual conditions.

**Features**
- 🌍 Explore anywhere — search or randomly discover destinations on an interactive map
- 🌤️ Live weather integration — current temperature, sky conditions, and time of day shape every image
- 🎨 Three modes:
  - **Scenery** — a realistic shot of the location right now
  - **Travel Selfie** — upload a photo of yourself and get dropped into the scene
  - **Time Machine** — see the same spot in another era (e.g. 1920s Paris, year 3000 New York)
- 📖 Travel diary — every trip is saved locally and can be revisited, downloaded, or deleted

---

## Built With

| | |
|---|---|
| **AI** | Google Gemini API |
| **Framework** | Next.js (App Router) · React |
| **UI** | Tailwind CSS · shadcn/ui · Lucide Icons |
| **Animation** | Motion (Framer Motion) |
| **Map** | Leaflet · React Leaflet |
| **Data** | OpenStreetMap · Open-Meteo |
| **Deploy** | Google Cloud Run |
