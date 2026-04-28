# Bazzcards Landing Page - Project Handoff

## Project Overview
- **Project**: Bazzcards Landing Pages
- **Location**: `/Users/ceo/Desktop/Bazz Cards Landing/`
- **Type**: Static marketing website

## Files
- `index.html` - Main landing page
- `shop.html` - NFC cards shop (UGX 80,000 Black/White, UGX 500,000 Gold)
- `privacy.html` - Privacy policy
- `terms.html` - Terms & conditions
- `AGENTS.md` - Project standards
- `CLAUDE.md` - Project context
- `CONTEXT.md` - Quick reference

## Design System

### Colors
```css
--brand: #85a700       /* Primary green */
--brand-light: #96bc00
--brand-dark: #6b8800
--dark-bg: #07090F     /* Dark background */
--text-dark: #0A0E1A
--text-muted: #6B7280
--border: #E5E8EF
```

### Typography
- Font: Inter (Google Fonts)
- Headings: 700-800 weight, letter-spacing: -1.5px
- Body: 400-500 weight

### Key Components
- Buttons: 10px border-radius, brand color
- Cards: 16px border-radius
- Sections: 96px vertical padding
- Max-width: 1200px container

## Page Structure

### index.html
1. Navbar (sticky, dark glass)
2. Hero (dark bg, gradient text)
3. How It Works (4 steps with images)
4. NFC Cards (3 cards with UGX prices)
5. Tiers (Personal, Teams)
6. Testimonials (auto-scrolling)
7. Share Channels
8. Why Switch (dark bg)
9. Trusted Brands
10. FAQs
11. Final CTA
12. Footer (4 columns)

### Footer Structure (4 columns)
1. Brand + tagline + social links
2. Platform (Sign In, Shop NFC Cards)
3. Resources (Customers, How It Works)
4. Contact (email, phone)

## Key Features Implemented
- Signup modal wizard (3-step)
- FAQ accordion with aria-expanded
- Image lightbox/gallery
- Testimonial auto-scroll
- Mobile hamburger menu
- Lazy loading on images
- Font preconnect
- Privacy policy link in signup modal

## Pricing
- Black Metal: UGX 80,000
- White PVC: UGX 80,000
- Gold Metal: UGX 500,000

## Known Issues
- Focus trap not implemented in modal
- Auto-scrolling testimonials have no pause control
- Slide dots should be buttons for accessibility

## External Links
- App: https://app.bazzcards.com/
- Support: support@bazzcards.com
- Phone: +256 753 330 197

## Last Updated
April 28, 2026