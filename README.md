# 🌾 Vikrant Satish Kadam — Personal Website

> *"Against the Odds — One Man Will Rise"*

Personal homepage of **Vikrant Satish Kadam** — MBBS student at Bashkir State Medical University, Ufa, Russia. Son of a farmer from चिकमहूद, सांगोला, Maharashtra.

---

## 📁 Project Structure

```
vikrant-website/
│
├── vikrant_homepage_v3.html   # Main homepage (this file)
├── farmers.html               # Farmers section — AI tools & playlists
└── README.md                  # You are here
```

---

## 🖥️ Website Sections

### 1. Navigation Bar
- Fixed top navbar with name **विक्रांत सतीश कदम** in Marathi (Tiro Devanagari Marathi font)
- Nav links: माझ्याबद्दल · प्रकल्प · संपर्क
- Glassmorphism effect (backdrop blur)

### 2. Hero Section
- Full-screen split layout (text + photo)
- Floating background marquee text: *"AGAINST THE ODDS ONE MAN WILL RISE"* + Marathi text
- Name in **Cinzel Decorative** font — bold, impressive
- Quote: *"Against the Odds — One Man Will Rise"*
- Location tag: चिकमहूद, सांगोला → उफा, रशिया

### 3. About Section (माझ्याबद्दल)
- Personal story in Marathi
- Family background — political roots, farmer father
- Photo from university (НОЦ building, Ufa)

### 4. Projects Section (माझे Projects)
Six project cards — all "Coming Soon", ready to be filled:

| # | Project | Description |
|---|---------|-------------|
| 1 | 🌾 Farmers | AI content for farmers in Marathi |
| 2 | 🇷🇺 About Russia | Student life guide for Indian students |
| 3 | 📱 Content Creation | Instagram Reels & YouTube Shorts |
| 4 | ⚖️ Politics | System analysis & civic education |
| 5 | 🗣️ Languages | Multilingual content & learning resources |
| 6 | 💼 Business | Entrepreneurship & consultancy |

### 5. Connect Section (संपर्क)
Direct tap-to-open links:

| Platform | Link |
|----------|------|
| 💬 WhatsApp | +91 77578 37271 |
| 📸 Instagram | @vikrantkadam295 |
| 👻 Snapchat | @Vikrantkadam295 |
| ✉️ Email | Vikrantkadam7071@gmail.com |

### 6. Footer
> © 2025 विक्रांत सतीश कदम · चिकमहूद, सांगोला → उफा, रशिया

---

## 🎨 Design System

### Color Palette
| Name | Hex | Usage |
|------|-----|-------|
| Black | `#0a0a0a` | Background |
| Soil | `#111008` | Alt sections |
| Charcoal | `#141414` | Cards |
| Gold | `#c8960a` | Accent lines, labels |
| Wheat | `#e8c96a` | Name highlight, hover |
| Offwhite | `#f0ede4` | Body text |
| Muted | `#888880` | Secondary text |

### Typography
| Role | Font | Usage |
|------|------|-------|
| Display | Cinzel Decorative | Name, quote |
| Marathi | Tiro Devanagari Marathi | All Marathi text, nav |
| Body | Space Grotesk | General text, UI |

### Animations
- **Marquee** — floating background text scrolling left/right
- **Fade-up** — scroll-triggered reveal on all sections (IntersectionObserver)
- **Hover** — subtle lift on connect cards

---

## 🚀 How to Host (Free)

### Option 1 — Netlify (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop `vikrant_homepage_v3.html`
3. Live URL ready in 2 minutes

### Option 2 — GitHub Pages
```bash
# 1. Create a new repo: vikrantkadam295.github.io
# 2. Upload the HTML file as index.html
# 3. Go to Settings → Pages → Enable
# 4. Your site: https://vikrantkadam295.github.io
```

### Option 3 — Custom Domain (Later)
Buy `vikrantkadam.in` (~₹500/year) from GoDaddy or BigRock and connect to Netlify/GitHub Pages.

---

## 📱 Mobile Responsive

| Breakpoint | Layout |
|------------|--------|
| `> 900px` | 2-column grid (text + photo) |
| `≤ 900px` | Single column, photo on top |
| `≤ 560px` | Nav links hidden, compact text |

---

## ✏️ How to Update Content

### Change your photo
Replace the base64 image string in the `<img class="hero-img"...>` tag with a new base64-encoded image.

### Add project links
Find the project card you want to update:
```html
<div class="project-card fade-up">
  <div class="project-icon">🌾</div>
  <h3>Farmers</h3>
  ...
</div>
```
Add an `<a href="farmers.html">` link inside the card.

### Update contact info
Search for your phone number or social handle and replace directly in the HTML.

---

## 🔗 Related Pages

- [`farmers.html`](farmers.html) — Full farmers section with AI tools, 8 YouTube playlists, and farmer resources

---

## 👤 About the Creator

**Vikrant Satish Kadam**
- 📍 From: चिकमहूद, सांगोला, Maharashtra, India
- 🎓 Currently: MBBS Year 2, Bashkir State Medical University, Ufa, Russia
- 🌾 Background: Son of a farmer, family with political roots
- 🎯 Mission: Education, AI for farmers, and building from the ground up

---

*Built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.*
