# 🌲 Collaborative Vancouver, Whistler & 3-Day Orca Expedition Web App

A high-performance, real-time, interactive web dashboard for managing, editing, and optimizing your 9-day trip to Vancouver, Whistler, and Hanson Island / Johnstone Strait Orca Glamping.

Built with **Pacific Northwest Dark Mode Glassmorphism**, real-time collaborator audit logging, protected anchor locks, and an **Autonomous Gemini AI Trip Guardian** that evaluates every change for the **strict 8-hour sleep rule** and drive logistics.

---

## 🚀 Free Deployment Guide (Step-by-Step)

### Option A: 1-Click Vercel Deployment (Recommended - $0/mo)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Vancouver Orca Itinerary Dashboard"
   git remote add origin https://github.com/YOUR_USERNAME/vancouver-orca-itinerary.git
   git push -u origin main
   ```

2. **Deploy on Vercel:**
   * Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
   * Import your `vancouver-orca-itinerary` repository.
   * Click **"Deploy"** (Vercel automatically detects the static frontend and `/api/ai-optimize.js` serverless function).

3. **Add Free Gemini API Key to Vercel:**
   * Get a free API key at [aistudio.google.com](https://aistudio.google.com).
   * In Vercel, go to **Project Settings ➔ Environment Variables**.
   * Add `GEMINI_API_KEY` = `your_actual_key_here`.
   * Redeploy. Now Gemini 2.0 Flash will autonomously analyze every edit made by anyone with the link!

---

### Option B: Optional Free Firebase Realtime Database (Multi-Device Live Sync)

If you want live WebSocket updates across multiple devices simultaneously (when Person A makes an edit, Person B's screen updates instantly without refreshing):

1. Go to [console.firebase.google.com](https://console.firebase.google.com) and create a free project.
2. Click **Build ➔ Realtime Database ➔ Create Database**.
3. Set rules to public read/write for your trip group:
   ```json
   {
     "rules": {
       ".read": true,
       ".write": true
     }
   }
   ```
4. Copy your Database URL (`https://your-app-default-rtdb.firebaseio.com/`).
5. Open the web app ➔ Navigate to **⚙️ Sync & Deployment** tab ➔ Paste your Database URL and click **Save Settings**.

---

## 🛠️ Local Development

To run the web application on your local machine:

```bash
# Start local server
npm start
```
Then open `http://localhost:3000` in your browser.

---

## 📌 Features Included

* 🔒 **Protected Anchor Locks:** Non-negotiable flights and race start cannot be accidentally overwritten.
* 🌙 **Strict 8-Hour Sleep Rule Engine:** Verifies 8.0 hours of continuous rest for all 8 nights.
* 📜 **Collaborator Audit Changelog & 1-Click Revert:** Tracks editor name, timestamp, reason, and supports instant rollback.
* 🛶 **Interactive Seasickness Protocol Tracker:** 6-step checklist for Hanson Island Orca Glamping.
* 🤖 **Autonomous Gemini AI Guardian:** Evaluates logistics and suggests 1-click schedule optimizations.
