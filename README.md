# 🌲 Ultimate Vancouver, 2-Night Whistler & At Water's Edge Orca Expedition App

A high-performance, responsive, collaborative web application built for managing and optimizing your 9-day Southwestern British Columbia master expedition (Aug 6 – Aug 15, 2026).

---

## 📌 Verified 7 Non-Negotiable Anchors

1. **Inbound Flight**: Direct flight JFK ✈️ YVR (**Thurs 8/6** arriving 9:55 PM).
2. **Outbound Flight**: Direct flight YVR ✈️ JFK (**Fri 8/14** departing 11:15 PM).
3. **Race Day**: SeaWheeze Half Marathon & Sunset Festival at Stanley Park (**Sat 8/8**).
4. **Whistler Branch**: 2 Full Nights in Whistler (**Sun 8/9 & Mon 8/10**) featuring Peak 2 Peak Gondola, Cloudraker Skybridge, Joffre Lakes Glacial Hike, Lost Lake & Scandinave Spa.
5. **Island Flight Transfers**: Flight YVR ✈️ YQQ Comox (**Tues 8/11 12:30 PM**) and Flight YQQ ✈️ YVR (**Fri 8/14 6:30 PM**).
6. **Orca Expedition**: 3-Day / 2-Night Base Camp with **At Water's Edge Adventures** on Hanson Island / Johnstone Strait (**Wed 8/12 – Fri 8/14**).
7. **Strict 8-Hour Sleep Guarantee**: Minimum **8.0 Hours of Continuous Rest Every Single Night** (8/8 nights pass).

---

## ✨ Features & Architecture

* **📅 Maximally Beautiful Master Timeline**: Rich Pacific Northwest dark glassmorphism design with category filters (Flights, Race, Whistler, Orca, Drives & Transports, Sleep).
* **🗓️ Day Board Dashboard**: 9-column kanban board displaying all 68 detailed events including every rental SUV pickup/return, drive segment (Hwy 99, Hwy 19), water taxi, and check-in window.
* **🤖 Autonomous Gemini AI Guardian**: Serverless function (`/api/ai-optimize.js`) powered by `gemini-2.0-flash` evaluating edit impacts and sleep compliance in real-time.
* **📜 Realtime Audit Changelog**: Every modification requires author name & rationale, with one-click instant state revert.
* **🛶 6-Step Vomit-Free Seasickness Protocol**: Hanson Island Orca kayaking guidelines tailored for seasickness prevention.

---

## 🚀 How to Deploy on Vercel ($0 Free Tier)

1. **Push Repository to GitHub**:
   * Drag & drop the entire folder onto GitHub Web or use `git push`.
2. **Deploy on Vercel**:
   * Log into [Vercel](https://vercel.com).
   * Click **New Project** ➔ Import your `vancouver-orca-itinerary` GitHub repository.
   * Add Environment Variable:
     * `GEMINI_API_KEY`: *(Your Google Gemini API Key from Google AI Studio)*
   * Click **Deploy**.
3. **Done!** Your app will be live with real-time AI reasoning and full mobile responsiveness!
