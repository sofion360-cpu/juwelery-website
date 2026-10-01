# AURA GOLD & CRAFTS — Luxury Boutique Web Application

An ultra-luxury, high-converting single-page web application for **AURA Gold & Crafts (Ceylon Fine Artisanal 22K Jewelry)** built with HTML5, Tailwind CSS, and Vanilla JavaScript.

## 📁 File Structure

```
Jewelry Website/
├── index.html                  # Main Web Application (HTML5 / Tailwind CSS / Vanilla JS)
├── ring.mp4                    # Hero Rotating Ring Video Loop
├── ring-loop.mp4               # Backup video reference
├── 13529793_2160_3840_30fps.mp4# Original raw video source
├── .nojekyll                   # GitHub Pages configuration file
└── README.md                   # Setup & Deployment Guide
```

---

## 🚀 How to Run Locally (Localhost / Live Server)

### Method 1: VS Code Live Server (Recommended)
1. Open **Visual Studio Code**.
2. Go to **File -> Open Folder...** and select the `Jewelry Website` folder.
3. Install the **Live Server** extension (by *Ritwick Dey*) if you haven't already.
4. Right-click on `index.html` and select **"Open with Live Server"** (or press `Alt + L, Alt + O`).
5. Your browser will automatically launch `http://127.0.0.1:5500/index.html`.

### Method 2: Direct Browser Open
Double-click `index.html` inside the `Jewelry Website` folder to open it directly in Google Chrome, Microsoft Edge, or Safari.

---

## 🌐 How to Publish to GitHub Pages

1. **Create a GitHub Repository:**
   - Go to [github.com/new](https://github.com/new) and create a new public repository named `jewelry-website` (or any name you prefer).

2. **Push Files to GitHub:**
   Open terminal inside the `Jewelry Website` folder and run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for AURA Gold website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/jewelry-website.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository **Settings** on GitHub.
   - Click **Pages** in the left sidebar menu.
   - Under **Build and deployment -> Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` / `/ (root)` and click **Save**.
   - Your website will be live at `https://YOUR-USERNAME.github.io/jewelry-website/` within 1–2 minutes!

---

## 💎 Features Included
- **Theme:** Deep Royal Navy Blue (`#0B132B`) & Champagne Gold (`#D4AF37`) palette.
- **Hero Video Loop:** Rotating 22K gold ring video with smooth dark gradient overlay.
- **Price Typography:** Luxury `'Cinzel'` & `'Cormorant Garamond'` tabular numerals for live gold board rates and price cards.
- **Interactive Gold Calculator:** Budget estimator and gram/sovereign karat fee breakdown.
- **WhatsApp Integration:** Instant WhatsApp pre-filled inquiry button connected to `+94 75 806 6423`.
- **Colombo Sea Street Stall Guide:** Step-by-step landmark walkthrough to Stall #14 with Google Maps embed.
