# Cyber Doctrine Website

Real-world cybersecurity training for businesses and individuals.

## 🚀 Deploy to Vercel

### Option 1 — One-Click Deploy (Recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**
3. Import your GitHub repository
4. Vercel will auto-detect it as a static site — click **Deploy**
5. Your site is live! ✅

### Option 2 — Vercel CLI
```bash
npm install -g vercel
vercel
```

## 📁 Repository Structure

```
cyberdoctrine/
├── index.html        ← Main homepage (all content + 7 tools)
├── style.css         ← All styles
├── vercel.json       ← Vercel deployment config
├── README.md         ← This file
└── public/
    └── logo.png      ← Cyber Doctrine logo
```

## ✏️ How to Update Content

- **Text & Sections**: Edit `index.html`
- **Colors & Fonts**: Edit the `:root` variables at the top of `style.css`
- **Logo**: Replace `public/logo.png` with a new file (keep the same filename)
- **Pricing Links**: Search for `mykajabi.com/offers` in `index.html` to update checkout URLs
- **Calendly Link**: Search for `calendly.com/thecyberdoctrine` to update

## 🔗 Key Links Referenced in Code

| Purpose | URL |
|---|---|
| Enroll / Landing Page | https://thecyberdoctrine.mykajabi.com/joinus |
| Book a Call | https://calendly.com/thecyberdoctrine/30min |
| Startup Tier Checkout | https://thecyberdoctrine.mykajabi.com/offers/LJSAJwrp/checkout |
| Growing Team Checkout | https://thecyberdoctrine.mykajabi.com/offers/DyJBE3NX/checkout |
| Scaling Team Checkout | https://thecyberdoctrine.mykajabi.com/offers/coNhStQ2/checkout |

## 🛠️ Free Tools Included

1. 🎯 Personalized Mini Risk Assessment
2. 📊 Cybersecurity Benchmarking Quiz
3. ✅ Compliance Gap Checklist (NIST / SOC2 / HIPAA / PCI)
4. 💰 Tailored ROI Calculator
5. 🗺️ Security Maturity Roadmap
6. ⚡ Mock Cyberattack Simulation
7. 🔍 Cybersecurity Diagnostic Checklist

## 📝 Custom Domain (Optional)

In your Vercel project dashboard:
1. Go to **Settings → Domains**
2. Add your domain (e.g., `cyberdoctrine.com`)
3. Update your DNS records as instructed by Vercel

## ⚠️ What's NOT Included (Needs Separate Setup)

- **Tawk.to live chat**: Add the script to the `<head>` in `index.html`
- **Google Analytics / tracking**: Add tracking script to `<head>`
- **Email/form backend**: Contact forms need a service like Formspree or Netlify Forms
