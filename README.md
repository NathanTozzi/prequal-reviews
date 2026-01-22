# PrequalReviews - Subcontractor Prequalification Platform Review Site

A professional G2/Capterra-style review site for subcontractor prequalification platforms, owned and operated by Highwire.

## What's Been Built

### ✅ Homepage (`index.html`)
A fully-featured, professional homepage with:

- **Sticky Navigation** - Clean header with logo and navigation links
- **Hero Section** - Pain-point focused headline with transparent ownership disclosure (Option C approach)
- **Disclosure Bar** - Prominent FTC-compliant transparency notice
- **"How This Site Works"** - Trust-building section explaining ownership, verification, and comparisons
- **Featured Platform: Highwire** - Expanded card with:
  - Positioning statement
  - 5 key value propositions
  - Dual CTAs (Book Demo + See How It Works)
  - Social proof
- **Other Platforms** - ISNetworld, Avetta, and Contractor Compliance with minimal cards
- **Educational Section** - "What to Look For" guide with 6 buying criteria (SEO-optimized)
- **Lead Capture Form** - Enhanced form with:
  - Required fields: Name, Email, Company, Role
  - Multi-select needs checkboxes
  - Optional: Company size, Timeline, Current tool
  - Clear disclosure about Highwire follow-up
- **Professional Footer** - Multi-column footer with navigation and disclosure

### ✅ About Page (`about.html`)
Comprehensive transparency and compliance page covering:

- Who owns the site (Highwire)
- Why it was built
- FTC compliance notice
- Review verification process
- Rating criteria explanation
- Editorial independence standards
- Contact and dispute resolution process
- Privacy overview

## Design Features

- **G2/Capterra-inspired aesthetics** - Clean, modern, professional
- **Fully responsive** - Mobile-optimized with breakpoints
- **Smooth interactions** - Hover effects, transitions, smooth scrolling
- **Accessible color palette** - Good contrast, readable typography
- **Performance-optimized** - Single-file HTML with inline CSS (no build tools required)

## Form Integration

The lead form currently uses a placeholder action:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Next Steps for Form Setup:

1. **Formspree (recommended for quick setup):**
   - Go to [formspree.io](https://formspree.io)
   - Create a free account
   - Create a new form
   - Replace `YOUR_FORM_ID` in `index.html` line 790 with your actual Formspree ID
   - Test the form

2. **Alternative options:**
   - **Netlify Forms** - If you deploy on Netlify, add `netlify` attribute to form tag
   - **HubSpot** - Embed HubSpot form for direct CRM integration
   - **Custom backend** - Build your own form handler if you have development resources

## Pages Still Needed (Future Work)

The site references these pages in navigation/footer but they don't exist yet:

1. **`highwire.html`** - Detailed Highwire platform page with:
   - Full feature breakdown
   - Screenshots/demo video
   - Customer testimonials
   - Pricing information
   - FAQ section

2. **`contact.html`** - Simple contact page

3. **`privacy.html`** - Privacy policy (REQUIRED for GDPR/CCPA compliance)

4. **`submit-review.html`** - Review submission form

5. **Platform comparison pages** - e.g., `highwire-vs-isnetworld.html`

## Deployment Options

### Option 1: GitHub Pages (Free, Recommended)
```bash
# Already in a git repo, just push and enable GitHub Pages
git add .
git commit -m "Build professional review site"
git push origin main

# Then go to GitHub repo → Settings → Pages → Enable Pages from main branch
```

### Option 2: Netlify (Free)
- Drag and drop the `prequal-reviews` folder to [netlify.com/drop](https://app.netlify.com/drop)
- Or connect your GitHub repo for automatic deploys

### Option 3: Vercel (Free)
- Import your GitHub repo at [vercel.com](https://vercel.com)

## SEO Optimization Next Steps

1. **Add Google Analytics** - Track traffic and conversions
2. **Submit to Google Search Console** - Monitor search performance
3. **Create sitemap.xml** - Help search engines index your pages
4. **Add structured data** - Use Schema.org markup for rich snippets
5. **Optimize page titles** - Tweak for target keywords
6. **Create blog content** - Publish educational articles about prequal best practices

## Content Customization Checklist

Before going live, update these placeholders:

- [ ] Replace "PrequalReviews" logo with actual logo/branding
- [ ] Update Highwire positioning statement if needed
- [ ] Add real customer logos to social proof section
- [ ] Replace placeholder competitor descriptions with accurate info
- [ ] Update contact email in about page (currently `reviews@highwire.com`)
- [ ] Add actual business address in about page
- [ ] Update form action URL with your form handler
- [ ] Add Google Analytics tracking code
- [ ] Create favicon

## FTC Compliance Checklist

✅ Ownership disclosed in hero
✅ Ownership disclosed in prominent banner
✅ Ownership disclosed in about page
✅ Ownership disclosed in footer
✅ Clear explanation of business model (lead generation)
✅ Commitment to verified reviews (no fake reviews)
✅ Rating methodology explained
✅ Contact information provided
✅ Dispute resolution process documented

## File Structure

```
prequal-reviews/
├── index.html          # Homepage (complete)
├── about.html          # About/transparency page (complete)
├── README.md           # This file
└── [future pages]
    ├── highwire.html
    ├── contact.html
    ├── privacy.html
    └── submit-review.html
```

## Questions?

If you need help with:
- Adding more pages
- Customizing design/copy
- Setting up forms
- SEO optimization
- Analytics tracking

Just ask!

---

**Built with:** HTML5, CSS3, Vanilla JavaScript
**Framework:** None (intentionally simple for easy maintenance)
**Browser Support:** Modern browsers (Chrome, Firefox, Safari, Edge)
