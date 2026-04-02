# 🌿 Relux Massage & Spa — Official Website

> A premium, high-converting spa website built with pure HTML, CSS, and JavaScript. No frameworks. No dependencies. Just fast, beautiful, and ready to deploy.

---

## 🌐 Live Site

**[View Website →](https://yourusername.github.io/relux-spa)**
*(Replace with your actual GitHub Pages URL after deployment)*

---

## ✨ Features

- ⚡ **Zero dependencies** — pure HTML/CSS/JS, no npm or build tools needed
- 📱 **Fully responsive** — mobile, tablet, and desktop optimized
- 🎨 **Majestic color palette** — Royal Navy, Gold, and Cream White
- 🔤 **Luxury typography** — Cormorant Garamond + Jost font pairing
- 🧭 **Sticky navigation** — transparent to glass-dark on scroll
- 🎬 **Scroll animations** — smooth reveal effects on every section
- ⏱️ **Live countdown timer** — for promotional offers
- 💬 **Interactive FAQ** — expandable accordion
- 📦 **Packages & Gift Cards** — with visual gift card component
- 🗺️ **Location section** — ready for Google Maps embed
- 🔘 **Floating Book Now button** — appears on scroll

---

## 📁 Project Structure

```
relux-spa/
│
├── index.html        ← Main website file (entire site)
└── README.md         ← You are here
```

> The entire website lives in a single `index.html` file for simplicity and speed.

---

## 🚀 Deployment (GitHub Pages)

This site is hosted for free using **GitHub Pages**.

### Steps to deploy:
1. Upload `index.html` and `README.md` to your repository
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch**
4. Choose `main` branch → `/ (root)` → click **Save**
5. Your site will be live in ~60 seconds at:

```
https://yourusername.github.io/repository-name
```

---

## 🛠️ How to Customize

Open `index.html` in any text editor (VS Code recommended) and update the following:

### 📍 Business Information
Search for these placeholders and replace them:

| Placeholder | Replace With |
|---|---|
| `[Your Street Address]` | Your actual address |
| `[City, Province, ZIP Code]` | Your city and ZIP |
| `+63 (0) XXX-XXX-XXXX` | Your phone number |
| `hello@reluxspa.com` | Your real email |
| `[Your Address]` | Footer address |

### 💰 Pricing
Update all `₱` prices in the Services and Packages sections to match your actual rates.

### 🗺️ Google Maps
Find the `map-placeholder` div and replace it with your Google Maps embed code:
```html
<iframe
  src="https://www.google.com/maps/embed?pb=YOUR_MAP_ID"
  width="100%" height="400" style="border:0;"
  allowfullscreen="" loading="lazy">
</iframe>
```

### 📅 Booking Button
Replace `#final-cta` links with your actual booking URL (Calendly, Square, etc.):
```html
<a href="https://calendly.com/your-link" class="btn-primary">Book Now</a>
```

### 🖼️ Photos
Replace emoji placeholders in service cards and about section with real `<img>` tags:
```html
<img src="your-photo.jpg" alt="Swedish Massage at Relux Spa" />
```

---

## 🎨 Color Palette

| Name | Hex | Usage |
|---|---|---|
| Royal Navy Deep | `#0c1a35` | Primary backgrounds |
| Navy Mid | `#14285a` | Gradient sections |
| Gold | `#c9a84c` | Accents, CTAs, highlights |
| Gold Bright | `#f5d677` | Hover states, shimmer |
| Gold Dim | `#9a7c32` | Price tags, links |
| Cream White | `#faf7f0` | Light section backgrounds |
| White | `#ffffff` | Cards, clean sections |

---

## 🔗 Connect a Custom Domain

To use a domain like `reluxspa.com`:

1. Buy a domain from [Namecheap](https://namecheap.com) or [GoDaddy](https://godaddy.com)
2. In GitHub → **Settings → Pages → Custom Domain** → enter your domain
3. In your domain registrar's DNS settings, add:
   ```
   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```
4. Wait 24–48 hours for DNS to propagate

---

## 📬 Contact

**Relux Massage & Spa**
- 📍 [Your Address]
- 📞 +63 (0) XXX-XXX-XXXX
- ✉️ hello@reluxspa.com
- 🌐 [reluxspa.com](https://reluxspa.com)

---

## 📄 License

This website was custom-built for **Relux Massage and Spa**. All rights reserved © 2025 Relux Massage and Spa.

---

*Built with care. Designed for calm.*
