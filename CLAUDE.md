# CLAUDE.md - Bazzcards Project Context

## Project Type
Static landing page website for NFC digital business card service in Uganda.

## Tech Stack
- Pure HTML/CSS/JS (no frameworks)
- Single page: index.html
- Secondary pages: shop.html, privacy.html, terms.html
- Images folder for assets

## Key Pages
- **index.html**: Main landing page with hero, features, testimonials, NFC cards, FAQ
- **shop.html**: Product listing for NFC cards (Black, White, Gold)
- **privacy.html**: Privacy policy page
- **terms.html**: Terms & conditions page

## Brand Colors
```
--brand: #99cc00 (Yellow Green)
--brand-light: #aadd00
--brand-dark: #7aaa00
--accent: #58584c (Ebony)
--dark-bg: #161616 (Onyx)
--off-white: #faeee1 (Linen)
--text-dark: #0A0E1A
--text-muted: #6B7280
```

## Typography
- Font: Switzer Variable (Fontshare CDN)
- CDN: https://api.fontshare.com/v2/css?f[]=switzer@300,400,500,600,700,800,900&display=swap

## Logo
- Files: bazz-logo-green.svg, bazz-logo-white.svg, bazz-logo-black.svg
- Wordmark is "Bazz" (not "Bazzcards") with stylized b icon
- Use green version on dark backgrounds — no filter needed

## Key Features
- Signup modal wizard (3-step)
- FAQ accordion
- Image lightbox/gallery
- Testimonial auto-scroll
- Mobile hamburger menu
- NFC card pricing: UGX 80,000 (Black/White), UGX 500,000 (Gold)

## Important Notes
- Footer uses 4-column grid layout
- All pages share same footer structure
- Links should point to local pages (/shop.html, /privacy.html, /terms.html) or sections (#nfc-cards)
- Social links go to actual Bazzcards profiles (linkedin, facebook, youtube, instagram)

## Common Tasks
- Edit hero CTA → find `.hero-btns` in index.html
- Edit footer → find `<footer class="footer">` in index.html
- Add new FAQ → find `.faq-list` in index.html
- Change pricing → find `.nfc-card` sections or shop.html