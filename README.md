# 📱 TechSaathi — AdSense-Ready English Tech Blog

A complete static website that fulfills every **Google AdSense approval** requirement:
original English content, all required pages, clean navigation, sitemap, robots.txt,
mobile-friendly design and fast loading — with zero heavy libraries.

---

## 📂 Project Structure

```
TechSaathi/
├── index.html              → Homepage (articles grid + features)
├── about.html              → About Us page
├── contact.html            → Contact page (Formspree form)
├── privacy-policy.html     → Privacy Policy (MUST for AdSense)
├── disclaimer.html         → Disclaimer page
├── terms.html              → Terms & Conditions page
├── sitemap.xml             → Sitemap for search engines
├── robots.txt              → Crawler rules
├── css/
│   └── style.css           → Styling for the entire site (single file)
└── articles/
    ├── smartphone-hang-fix.html    → Fix a hanging phone
    ├── mobile-data-save.html       → Save mobile data
    ├── wifi-speed-increase.html    → Boost WiFi speed
    ├── online-scam-suraksha.html   → Online scam safety
    ├── battery-long-life.html      → Battery tips
    ├── free-fire-lag-fix.html      → Free Fire lag fix
    ├── youtube-data-save.html      → YouTube data tips
    └── google-hidden-features.html → Hidden Google features
```

---

## ✅ AdSense Approval Checklist (what this site already covers)

| Requirement | Status |
|---|---|
| Original, useful content (8 articles, 600+ words each) | ✅ |
| Clear navigation (header + footer menus) | ✅ |
| Privacy Policy (with AdSense/DART cookie section) | ✅ |
| About Us page | ✅ |
| Contact page (working form + email) | ✅ |
| Disclaimer + Terms pages | ✅ |
| sitemap.xml + robots.txt | ✅ |
| Mobile responsive (hamburger menu) | ✅ |
| Fast loading (no frameworks, no external fonts/images) | ✅ |
| Clean design, no broken links | ✅ |
| Content in English (broader audience, higher CPC) | ✅ |

---

## 🚀 Step 1: Local Preview

Just double-click `index.html` to open it in your browser. Or the proper way:

```bash
cd "C:\Users\User\Zcode Project\TechSaathi"
python -m http.server 8000
# Then open: http://localhost:8000
```

---

## 🌐 Step 2: Deploy (pick any one method)

### Option A — GitHub Pages (free, recommended)

1. Create a new public GitHub repo, e.g. `techsaathi`
2. Upload all files (or git push)
3. Repo Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → Save
4. Site goes live in 2-5 minutes: `https://your-username.github.io/techsaathi/`

### Option B — Netlify Drop (easiest, 2 minutes)

1. Open [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the TechSaathi folder
3. You get a live URL instantly — attach a custom domain later

### Option C — Vercel

```bash
npm i -g vercel
cd "C:\Users\User\Zcode Project\TechSaathi"
vercel
```

> **Important:** AdSense *can* approve free subdomains (`.netlify.app` / `.github.io`),
> but attaching a **custom domain** (a `.com` or `.in` for ₹200-800/year) significantly
> improves approval chances. Buy from GoDaddy/Namecheap/Hostinger.

---

## ⚙️ Step 3: Change These 4 Things BEFORE Deploying

1. **Domain URLs:** The site uses the custom domain `techsaathi.publicvm.com`
   (DNSExit → GitHub Pages). `CNAME` file in the repo root tells GitHub Pages
   about it. If the domain ever changes, update the `CNAME` file plus all URLs
   in `sitemap.xml` and `robots.txt`
2. **Contact form:** Create a free account at [formspree.io](https://formspree.io),
   create a form, and replace `YOUR_FORM_ID` in `contact.html` with your ID
3. **Email:** Replace `hello@techsaathi.com` with your real email
   (found in `contact.html`, `privacy-policy.html`, `disclaimer.html`, `terms.html`)
4. **Site name:** If you want a different name than "TechSaathi", search-replace it

---

## 💰 Step 4: Apply for AdSense

1. Sign in at [adsense.google.com](https://adsense.google.com) with your Google account
2. "Get started" → enter your website URL → country: India
3. Fill in payment address details (name must exactly match your bank records)
4. Google will ask you to add the `ads.txt` code / AdSense script — follow the instructions
5. Review usually takes **1 day to 2 weeks**

### Tips to maximize approval chances:

- ✅ Add the site to **Google Search Console** and submit the sitemap before applying
- ✅ Grow to **15-20 articles** before applying (currently 8) — add 3-4 per week
- ✅ Let the site live for 2-3 weeks and gain some organic traffic first
- ❌ Copy-paste content, low-value spun content, or empty pages — instant rejection
- ❌ Clicking your own ads — permanent account ban
- ❌ Illegal/hacking/adult content categories — never approved

### After approval:

- Copy your `ads.txt` line from the AdSense dashboard and create `ads.txt` in the site root:
  `google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0`
- Place ad units (below header, inside articles, sidebar) — but never click them yourself
- Remember to add every new article URL to `sitemap.xml`

---

## 📝 How to Add a New Article

1. Copy any existing article from the `articles/` folder
2. Change the title, meta description, content and FAQ — update the `lastmod` date
3. Add a new card in `index.html`
4. Add the new URL entry in `sitemap.xml`
5. Optionally add the link to the footer's "Popular Articles" list

---

## 🎯 Realistic Expectations

- Static site + custom domain + 15-20 original articles → **very strong approval chances**
- Plenty of sites get approved with 8 articles, but more content = better odds + higher earnings
- If rejected, don't panic — read the reason, add more articles, and re-apply after 2 weeks
- Earnings depend on traffic — typically starts small (₹100/day range) and grows with visitors
