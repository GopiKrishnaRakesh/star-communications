# Star Communications — 142 High Street, Hounslow, London

A premier, professional static HTML website for **Star Communications**, Hounslow's trusted destination for smartphone sales, certified gadgets, accessories, express repairs, and instant cash device trade-ins.

---

## 🌿 Brand Identity & Design System

- **Bespoke Vector Logo**: Custom designed vector brandmark (**The Orbital Nexus**) combining telecommunication signal orbit rings with a precision four-point nexus star (`images/logo-icon.svg` and `images/logo.svg`).
- **Natural & Professional Luxury Theme**:
  - **Base Palette**: Earthy slate, charcoal basalt, and warm mineral stone (`#0c1113`, `#0f1518`, `#162024`).
  - **Botanical Accents**: Nordic forest sage and refined jade (`#3eb489`, `#52c99a`), replacing harsh neon tones with calm, trustworthy organic luxury.
  - **Warm Highlights**: Subtle champagne gold and oyster titanium (`#c9ab7a`, `#d1e5dd`).
- **Zero Price Mentions**: Completely free of prices, currency symbols, and speculative pricing tags. Focuses purely on turnaround times (20–30 mins), 12-Month Guarantee, condition grades, and instant reservations.
- **Pure HTML Project**: Clean, standard HTML5, CSS3, and JavaScript architecture with zero React boilerplate or node-lock. Can be served via any HTTP server or deployed instantly to any host.

---

## 🌟 Sections & Interactive Capabilities

1. **Header & Navigation**:
   - Single-line, non-wrapping desktop menu (`Home`, `Repairs & Services`, `Phones & Gadgets`, `Sell & Trade-In`, `Why Us`, `Location & Hours`).
   - Responsive mobile navigation with automated smooth collapse on anchor click.
   - Click-to-call store phone link (`020 8570 8899`) and instant repair reservation button.

2. **Hero Showcase**:
   - High Street credibility pill (`EST. 2012 • 142 High Street, Hounslow • 18,500+ Repaired`).
   - Headline and quick action buttons.

3. **Quick Action Strip**:
   - Walk-in convenience banner and landmark locator (*Opposite Treaty Shopping Centre*).

4. **Technical Capabilities & Hardware Issues**:
   - 6 core services: Precision Screen Replacement, Certified Battery Renewal, Charging Port & Audio Fix, Laser Rear Glass Repair, Ultrasonic Liquid Recovery, and Network Unlocking.
   - Highlights 20–30 min turnarounds, OEM-grade panels, and 12-month warranty.

5. **Phones, Gadgets & Accessories Showcase**:
   - Certified Pre-Owned iPhones (Grade A+), brand new sealed Samsung Galaxy models, Google Pixels, AirPods Pro, 9H tempered glass (free in-store fitting), and 65W GaN fast chargers.
   - Direct WhatsApp reservation links.

6. **Instant Cash Trade-In Guide**:
   - 3-step walk-in appraisal workflow with transparent valuation standards and Faster Payments / cash payout options.

7. **Express Repair Reservation Form**:
   - Interactive client-side booking generator creating unique reference codes (`REF: SC-XXXX`).
   - Automatically pre-fills a formatted WhatsApp message to send directly to store technicians.
   - "Book Another Device" reset handler and date validation preventing past-date selection.

8. **Location, Transit Guide & Real Interactive Map**:
   - Embedded interactive OpenStreetMap centered directly at **142 High Street, Hounslow (51.4687, -0.3644)**.
   - Transit directions for Hounslow Central Tube (Piccadilly Line), local bus routes, and Treaty Shopping Centre parking.

---

## 🚀 Running Locally & Deploying

### Option 1: Development Server (Vite)
```bash
# Start local dev server
npm run dev
```
Open [http://localhost:5173](http://localhost:5173).

### Option 2: Production Build
```bash
# Generate production bundle in dist/
npm run build
```

### Option 3: Pure Static Hosting
Because this is pure HTML, CSS, and JS, you can drop the root folder into **any** web server:
- **Netlify / Vercel / GitHub Pages**: Deploy directory `dist` or root.
- **Apache / Nginx / cPanel**: Upload all files directly to `public_html`.
