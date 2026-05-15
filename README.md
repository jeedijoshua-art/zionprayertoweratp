# ✝ Zion Prayer Tower ATP — Church Website

> **"I am the vine; you are the branches."** — John 15:5

Official website for **Zion Prayer Tower, Avinashi Town Panchayat, Tamil Nadu, India**.  
A Spirit-filled, community-rooted church website built as a Single Page Application (SPA).

---

## 🌐 Live Site

Hosted via **GitHub Pages**:  
👉 `https://zionprayertoweratp.github.io/chruchpage`

---

## 📁 File Structure

```
webpage/
├── index.html      ← Main SPA (all pages live here)
├── styles.css      ← All shared styles / design tokens
└── README.md       ← This file
```

> All content (About, Services, Sermons, Events, Prayer, Give, Contact) is inside `index.html`.  
> Clicking nav links shows/hides sections **without any page reload**.

---

## 🗂️ Pages / Sections

| Section | Hash URL | Description |
|---|---|---|
| Home | `#home` | Hero banner with animated particles and quick-link cards |
| About | `#about` | Church story and core belief pillars |
| Services | `#services` | Weekly service times (Sunday, Wednesday, Friday) |
| Sermons | `#sermons` | YouTube sermon embeds |
| Events | `#events` | Upcoming events list + Google Calendar embed |
| Prayer | `#prayer` | WhatsApp & Google Form prayer request links |
| Give | `#give` | Google Pay / PhonePe / UPI donation links |
| Contact | `#contact` | Address, phone, email, map, and Formspree contact form |

---

## 🎨 Design

- **Fonts:** Cormorant Garamond (display) + Crimson Pro (body) via Google Fonts
- **Icons:** Font Awesome 6
- **Color palette:** Deep vine, grape purple, leaf green, gold — a vineyard-inspired theme
- **Animations:** Floating leaf particles (hero), scroll-reveal fade-ups, glowing cross
- **Responsive:** Mobile hamburger menu, fluid grids, `clamp()` typography

---

## ⚙️ How to Customize (Placeholders to Replace)

Open `index.html` and search for these strings — replace each with your real data:

| Placeholder | What to replace with |
|---|---|
| `G-XXXXXXXXXX` | Your Google Analytics Measurement ID |
| `VIDEO_ID_1` / `VIDEO_ID_2` / `VIDEO_ID_3` | YouTube video IDs (the part after `v=`) |
| `YOUR_CALENDAR_ID` | Google Calendar embed ID (from Calendar → Settings → Integrate) |
| `91XXXXXXXXXX` | WhatsApp number with country code, no `+` (e.g. `919876543210`) |
| `YOUR_GOOGLE_FORM_ID` | Full Google Form URL |
| `YOUR_UPI_ID` | Church UPI ID (e.g. `churchname@upi`) |
| `YOUR_FORM_ID` | Formspree form ID (from formspree.io) |
| `YOUR_MAPS_EMBED_URL` | Google Maps embed URL for the church address |
| `+91 XXXXX XXXXX` | Actual phone number |
| `REPLACE # with actual social media URLs` | Facebook, YouTube, Instagram, WhatsApp URLs in footer |

---

## 🚀 Deployment (GitHub Pages)

1. Go to **Settings → Pages** in this repository
2. Set **Source** to `Deploy from a branch`
3. Select **branch:** `main` | **folder:** `/ (root)`
4. Click **Save** — the site will be live in ~1 minute

---

## 🛠️ Local Development

No build tools needed. Just open `index.html` in your browser:

```bash
# Option 1 — Direct open
open index.html

# Option 2 — Local server (recommended, avoids CORS issues with iframes)
npx serve .
# then visit http://localhost:3000
```

---

## 📞 Contact

**Zion Prayer Tower ATP**  
Avinashi Town Panchayat, Tamil Nadu – 641 654  
✉️ info@zionprayertoweratp.org  

---

*Built with ❤️ for the glory of God.*
