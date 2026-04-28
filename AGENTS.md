# AGENTS.md - Project Standards for Bazzcards Landing Page

## Project Overview
- **Project**: Bazzcards Landing Pages (index.html, shop.html, privacy.html, terms.html)
- **Location**: /Users/ceo/Desktop/Bazz Cards Landing/
- **Type**: Static marketing website

## Design Standards

### Colors
- Primary brand: `#85a700` (green)
- Primary light: `#96bc00`
- Primary dark: `#6b8800`
- Dark background: `#07090F`
- White: `#FFFFFF`
- Text: `#0A0E1A`
- Muted text: `#6B7280`
- Border: `#E5E8EF`

### Typography
- Font: Inter (Google Fonts)
- Headings: 700-800 weight
- Body: 400-500 weight
- Letter spacing: -1.5px for h1/h2

### Components
- Buttons: 10px border-radius, brand color background
- Cards: 16px border-radius
- Spacing: 8px base unit
- Sections: 96px vertical padding
- Max-width: 1200px container

## Page Structure

### index.html Sections (in order)
1. Navbar (sticky, dark glass effect)
2. Hero (dark bg, gradient text, phone mockup)
3. How It Works (4 steps, alternating layout)
4. NFC Cards (3 cards with prices: ₵80,000 / ₵500,000)
5. Tiers (Personal, Teams) - pricing section
6. Testimonials (auto-scrolling)
7. Share Channels
8. Why Switch
9. Trusted Brands
10. FAQs
11. Final CTA
12. Footer (4 columns)

### Footer Structure (4 columns)
1. Brand + social links + tagline
2. Platform (Sign In, Shop NFC Cards)
3. Resources (Customers, How It Works)
4. Contact (email, phone)

## Content Guidelines

### Pricing (UGX)
- Black Metal: UGX 80,000
- White PVC: UGX 80,000  
- Gold Metal: UGX 500,000

### Trust Metrics
- "Trusted by 300+ professionals"
- Include customer names with companies

### CTA Hierarchy
1. Primary: "Get Started" → opens signup modal
2. Secondary: "Shop NFC Cards" → #nfc-cards
3. Micro-copy: "No credit card required to start"

## Technical Requirements
- Images: Add loading="lazy" and width/height for below-fold
- Font: Preconnect to fonts.googleapis.com and app.bazzcards.com
- Accessibility: aria-expanded on FAQ toggles, ARIA roles on modal

## Code Style
- Tailwind not used (custom CSS)
- CSS variables for colors
- Mobile-first responsive breakpoints: 480px, 768px, 1024px

## File Dependencies
- bazzcards-logo.png (footer nav)
- favicon.png
- images/* (all product and brand images)