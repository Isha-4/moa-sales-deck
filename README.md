# Mall of America - Interactive Sales Deck

## 🎯 Project Overview

An interactive, cinematic web-based sales presentation for Mall of America, designed to engage prospective retail tenants, sponsors, and event partners. This deck serves as a standalone tool that can be shared on video calls or sent as a direct link for independent exploration.

**Live Demo:** [https://moa-sales-deck-eight.vercel.app/](https://moa-sales-deck-eight.vercel.app/)

---

## ✨ Features

- **Fully Responsive Design** — Optimized for desktop, tablet, and mobile devices
- **Smooth Scroll Animations** — Cinematic transitions between sections with fade-in effects
- **Interactive Elements** — Hover effects, button animations, and smooth scroll progress bar
- **Professional Typography** — Bebas Neue for headings (bold, impactful) + Inter for body text
- **Premium Color Scheme** — Black background (#0A0A0A), red accents (#E31837), gold highlights (#C9A84C)
- **Performance Optimized** — Fast-loading, smooth animations, optimized CSS
- **Accessibility** — Semantic HTML, proper contrast ratios, keyboard navigation support

---

## 📋 Sections

1. **Opening** — Cinematic introduction with brand promise
2. **Why This Mall** — Scale, reach, and competitive advantages with key statistics
3. **Retail** — 520+ retailers, new tenants, visitor traffic, and leasing opportunities
4. **Luxury** — Premium brand positioning and upscale shopping experience
5. **Dining & Lifestyle** — 50+ restaurants and extended-visit drivers
6. **Entertainment** — Nickelodeon Universe and SEA LIFE Aquarium as major differentiators
7. **Events & Platform** — Global platform for concerts, activations, and corporate events

---

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3 (with modern animations and transitions)
- **Fonts:** 
  - [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) — Headings
  - [Inter](https://fonts.google.com/specimen/Inter) — Body text
- **Deployment:** [Vercel](https://vercel.com)
- **Version Control:** Git & GitHub

---

## 🎨 Design Decisions

### Color Palette
- **Primary Dark:** #0A0A0A (deep black for cinematic feel)
- **Accent Red:** #E31837 (energetic, action-oriented CTAs)
- **Gold:** #C9A84C (luxury sections, premium feel)
- **Text:** #FFFFFF and #E0E0E0 (readable on dark backgrounds)

### Typography
- **Headlines:** Bebas Neue (uppercase, tight letter-spacing, bold presence)
- **Body:** Inter (clean, readable, modern, weighted variants)
- **Size Scaling:** Responsive clamp() for fluid scaling across devices

### Animations
- Fade-in on page load with staggered delays
- Smooth scroll progress bar at top
- Hover effects: lift, scale, shadow enhancement
- Button press feedback with click animations
- Section transitions: smooth scroll behavior

---

## 📱 Responsive Breakpoints

- **Desktop:** 1024px+ (full experience with all animations)
- **Tablet:** 768px - 1024px (optimized spacing and typography)
- **Mobile:** 480px - 768px (compact layout, touch-friendly buttons)
- **Small Mobile:** < 480px (minimal padding, essential content only)

---

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/Isha-4/moa-sales-deck.git
cd moa-sales-deck
```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (VS Code Live Server extension recommended)

3. Make changes and save — browser will refresh automatically if using Live Server

### Deployment

This project is deployed on Vercel and automatically updates on every GitHub push.

To deploy your own version:
1. Push code to GitHub
2. Connect your repo to Vercel
3. Vercel automatically deploys on every commit

---

## 📊 Performance Metrics

- **Lighthouse Score:** 90+ (Performance, Accessibility, Best Practices)
- **Load Time:** < 2 seconds
- **CSS:** Single file, minified animations
- **JavaScript:** Lightweight Intersection Observer for scroll tracking
- **Animations:** GPU-accelerated (transform & opacity only)

---

## 🎬 Animation Details

### Section Entrance
- Each section fades in on page load
- Staggered delays (0.2s increments) create cascading effect
- Subtle slide-up from bottom for cards and content

### Interactive Hover States
- **Stat Cards:** Lift with shadow enhancement (+8px), border color brightens
- **CTA Buttons:** Lift (+4px), shadow expands, shimmer effect across button
- **Attraction Items:** Slide right, background brightens, border color animates
- **Content Boxes:** Lift and brighten on hover, shadow expands

### Scroll Progress
- Gradient bar (red to gold) at top of page
- Fills as user scrolls through deck
- Box-shadow glow for subtle emphasis

---

## 🔧 Customization

### To Change Colors
Edit the CSS variables in the `<style>` section:
```css
/* Change red accent color */
#E31837 → your-color

/* Change gold accent color */
#C9A84C → your-color

/* Change background */
#0A0A0A → your-color
```

### To Modify Content
Edit text in each `<section>` directly. Structure is semantic and easy to update.

### To Add Sections
Copy an existing section `<section>` block and:
1. Change the `id` attribute
2. Update heading and content
3. Add animation delay if needed

---

## 📝 File Structure

```
moa-sales-deck/
├── index.html          # Main HTML file (all content, CSS, JS)
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

All CSS and JavaScript are contained within `index.html` for easy deployment.

---

## 🤝 Contributing

This is a static presentation deck. To suggest improvements:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is proprietary to Mall of America. All rights reserved.

---

## 👤 Created By

**Isha Vesvikar**
- Email: ishavesvikar@gmail.com
- LinkedIn: [Isha Vesvikar](https://linkedin.com/in/isha-vesvikar)
- Portfolio: [View Portfolio](https://moa-sales-deck-eight.vercel.app/)

---

## 🙏 Acknowledgments

- **Design Inspiration:** Digideck, Apple.com, Tesla.com
- **Typography:** Google Fonts (Bebas Neue, Inter)
- **Deployment:** Vercel
- **Data Source:** Official Mall of America statistics and press materials

---

## 📞 Support

For questions or technical issues with the deck, please reach out to ishavesvikar@gmail.com

---

**Last Updated:** May 9, 2026  
**Status:** Production Ready ✅