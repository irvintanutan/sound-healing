# The Resonance Experience

A production-ready landing page for a sound bath & body energy wellness event.

## 📁 Project Structure

```
resonance-experience/
├── index.html        ← Main landing page (self-contained)
├── README.md         ← This file
└── .gitignore        ← Git ignore rules
```

## 🚀 Getting Started

### View Locally
Just open `index.html` in any browser — no build tools or installs needed.

### Deploy to GitHub Pages
1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at `https://yourusername.github.io/repository-name`

## ✏️ Customization

| What to change | Where to find it in `index.html` |
|---|---|
| Event title / copy | Search for text inside `<h1>`, `<h2>`, `<p>` tags |
| Price | Search for `₱3,000` |
| Seats available | Search for `slot taken` / `slot open` divs |
| Colors | CSS variables inside `:root { }` at the top of `<style>` |
| CTA button links | Search for `href="#"` and replace with your booking link |
| Facilitator name/bio | Search for `Your Facilitator` section |

## 🎨 Color Variables

```css
--gold: #C9A96E
--gold-light: #E8D5A3
--beige: #F5ECD7
--warm-dark: #1A1410
```

## 📌 Notes
- No external dependencies except Google Fonts (loaded via CDN)
- All images are embedded as base64 — no broken image links
- Fully responsive for mobile and desktop
- Smooth scroll animations included

## 📬 Booking Link
Replace all `href="#"` on the CTA buttons with your actual booking/payment link (GCash, Google Form, Calendly, etc.)
