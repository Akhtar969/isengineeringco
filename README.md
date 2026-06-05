# I.S. Engineering Co. — Website
**isengineeringco.in** | M.S. Flanges Manufacturer & Supplier, Mumbai — Since 1999

---

## File Structure

```
isengineering/
├── index.html          ← Homepage (Hero, Products, E Table, FAQ, Testimonials)
├── about.html          ← About Us, Mission, Timeline, Values
├── products.html       ← Full product catalogue with filter
├── gallery.html        ← Gallery with lightbox and category tabs
├── contact.html        ← Contact form, addresses, Google Map
├── robots.txt          ← SEO robots file
├── sitemap.xml         ← XML sitemap for Google
├── css/
│   └── style.css       ← Complete stylesheet (all pages)
├── js/
│   └── script.js       ← All JavaScript (carousel, FAQ, filter, etc.)
└── assets/
    └── images/         ← Place product & factory images here
```

---

## Deployment Instructions

### 1. Add Real Images
Place your product/factory photos in `assets/images/` and update the `background-image` URLs in hero slides:
```html
<!-- In index.html hero slides, replace: -->
style="background-image:url('assets/images/hero-flanges.jpg')"
<!-- with your actual photo filenames -->
```

**Recommended images to add:**
- `hero-flanges.jpg` — M.S. Flanges batch photo
- `hero-etable.jpg` — E Table Flanges photo
- `hero-pipes.jpg` — Pipes / factory photo
- `hero-factory.jpg` — Factory floor photo
- `hero-fittings.jpg` — Pipe fittings photo
- Product card images (replace SVG placeholders in `.product-img`)
- Gallery images (replace SVG placeholders in `.gallery-item`)

### 2. Upload to Hosting
Upload all files maintaining the folder structure to your web host (e.g. via cPanel File Manager or FTP):
- Upload to `public_html/` for root domain
- Ensure `index.html` is the default document

### 3. Update Google Maps Embed
In `contact.html`, replace the Google Maps iframe `src` with the correct embed URL for your factory address:
1. Go to Google Maps → search your address
2. Click Share → Embed a map → Copy HTML
3. Replace the `<iframe src="...">` in contact.html

### 4. Configure Contact Form Backend
The contact form currently shows a success message (demo mode). To make it send real emails, integrate with:
- **Formspree** (free): Replace `<form id="contact-form">` with `<form action="https://formspree.io/f/YOUR_ID" method="POST">`
- **EmailJS**: Add EmailJS SDK and update `script.js` `contactForm` section
- **PHP Mailer**: Add `action="mail.php"` and create `mail.php` server-side handler

### 5. SEO Final Steps
- Update `sitemap.xml` dates when you launch
- Submit sitemap to Google Search Console: `https://search.google.com/search-console`
- Add your site to Google Business Profile for local SEO
- Add real images with descriptive filenames (e.g. `ms-flanges-manufacturer-mumbai.jpg`)

### 6. WhatsApp Number
WhatsApp links use `+918355815350`. Verify this is a WhatsApp-enabled number.
If different, search and replace `918355815350` in all HTML files.

---

## Features Included

| Feature | Status |
|---|---|
| 5-page responsive website | ✅ |
| Mobile-friendly hamburger menu | ✅ |
| Hero image carousel (5 slides) | ✅ |
| Sticky header with scroll effect | ✅ |
| Product filter (category + search) | ✅ |
| FAQ accordion | ✅ |
| Gallery with tabs + lightbox | ✅ |
| Contact form with validation | ✅ |
| WhatsApp floating button | ✅ |
| Call Now floating button | ✅ |
| Back-to-top button | ✅ |
| Counter animation (stats bar) | ✅ |
| Fade-in scroll animations | ✅ |
| E Table Flanges spec table | ✅ |
| Google Map embed (contact page) | ✅ |
| JSON-LD Schema (LocalBusiness, FAQ, Org, Breadcrumb) | ✅ |
| Open Graph + Twitter Card meta | ✅ |
| Canonical URLs | ✅ |
| XML Sitemap | ✅ |
| robots.txt | ✅ |
| Semantic HTML (header, main, section, article, footer) | ✅ |
| SEO-optimised headings H1–H4 | ✅ |
| Google Fonts (Barlow Condensed + Source Sans 3) | ✅ |
| GSTIN displayed throughout | ✅ |
| Breadcrumb navigation | ✅ |
| Testimonials section | ✅ |
| Industries served section | ✅ |
| CTA banners (every page) | ✅ |

---

## Colours
- Primary Green: `#5B8E1D`
- Dark Grey: `#3E3E3E`
- Background: `#FFFFFF`

## Contact Details Embedded
- Phone 1: +91 83558 15350
- Phone 2: +91 91373 32945
- Email: info.isengineering.co@gmail.com
- Factory: Gala No 10, Plot 255, Darukhana, Mumbai – 400010
- Office: Jasmin Apt A-Wing 304, Mumbra, Thane – 400612
- GSTIN: 27AMZPK5174G1ZE

---
*Website built for I.S. Engineering Co. — isengineeringco.in*
