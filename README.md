# 💕 For Bhavya — A Pookie-Core Apology Website

Made with love, apologies, and a little bit of overthinking — **Parth ❤️**

---

## 🚀 Quick Start

Just open `index.html` in any web browser. That's it!

---

## 🎵 Adding Background Music (Ishq Wala Love)

1. Obtain the audio file for "Ishq Wala Love" from Student of the Year.
2. Name the file exactly: **`ishq-wala-love.mp3`**
3. Place it in the **same folder** as `index.html`.
4. Open `index.html` in a text editor.
5. Find this line (around line 280):
   ```html
   <!-- <source src="ishq-wala-love.mp3" type="audio/mpeg" /> -->
   ```
6. **Uncomment it** by removing the `<!--` and `-->`:
   ```html
   <source src="ishq-wala-love.mp3" type="audio/mpeg" />
   ```
7. Save and refresh the browser. The 🎵 button will now play music!

---

## 📁 File Structure

```
apology-website/
├── index.html          ← The entire website (all-in-one file)
├── ishq-wala-love.mp3  ← ADD THIS yourself (see above)
└── README.md           ← This file
```

---

## 🌐 Deploy on GitHub Pages

1. Create a new **public** GitHub repository (e.g., `for-bhavya`).
2. Upload both `index.html` (and your `.mp3` if desired).
3. Go to **Settings → Pages**.
4. Under "Source", select **Deploy from a branch** → `main` → `/ (root)`.
5. Click **Save**.
6. Your site will be live at: `https://yourusername.github.io/for-bhavya/`

> 💡 **Tip for music on GitHub Pages:** GitHub has a 100MB file limit. If your MP3 is large, compress it or host it elsewhere and update the `src` attribute to the direct URL.

---

## ✨ Features

| Feature | Description |
|---|---|
| 💕 Loading Screen | "Preparing something special for Bhavya..." |
| 🌟 Twinkling Stars | Canvas-based animated star field |
| 🌸 Falling Hearts | Continuous rain of hearts, stars & flowers |
| 🎵 Music Player | Toggle button with pulsing ring animation |
| ✍️ Typewriter | Animated text on the landing page |
| 🃏 3 Cards | Apology, Love, and Future — each with a modal |
| 💌 Apology Letter | Glassmorphism card with floating hearts |
| 💖 Love Messages | Staggered-reveal romantic messages + CSS heart |
| 🌈 Future Promises | Numbered list with smooth reveal animation |
| 🥺 Forgiveness Buttons | Heart explosion, hug response, runaway button |
| 📱 Mobile-First | Designed primarily for phones |

---

## 🎨 Customization

All text content is in easy-to-find JavaScript arrays at the bottom of `index.html`:

```js
const LOVE_MESSAGES = [ ... ]   // Edit love messages
const FUTURE_ITEMS  = [ ... ]   // Edit future promises
```

Colors use CSS custom properties at the top of the `<style>` block — easy to tweak!

---

*Built with pure HTML, CSS & Vanilla JavaScript. No dependencies, no frameworks, no build tools.*
