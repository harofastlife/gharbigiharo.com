# TODO: Build haro-gharbigi.com

## Overview
Create a completely new personal website for Haro Gharbigi at the domain **haro-gharbigi.com**. This site must be entirely different from gharbigiharo.com and harogharbigi.com in design, structure, and content wording to avoid duplicate content penalties while maintaining the same external profile links.

## Requirements

### 1. Design Differentiation
The site must look and feel completely different from:
- **gharbigiharo.com**: Light warm theme (terracotta #C45A3B, cream background), sidebar navigation, Source Serif 4 + Source Sans 3 fonts
- **harogharbigi.com**: Dark theme

**Suggested approach for haro-gharbigi.com:**
- Modern minimalist design with a different color palette (e.g., deep blue/navy primary, white/light gray backgrounds)
- Different layout structure (e.g., full-width hero, single-column content, bottom navigation)
- Different font pairing (e.g., Playfair Display + Roboto, or Poppins + Open Sans)
- Different visual style (e.g., geometric shapes, gradient accents, card shadows)

### 2. Content Requirements
All content must be **completely rewritten** with unique wording:
- Same biographical facts but different phrasing
- Same professional history but different descriptions
- Same skills/expertise but presented differently
- Unique meta descriptions and titles for every page

### 3. SEO Requirements (Maximum Optimization)

#### Meta Tags
- Unique title tags (different wording from other sites)
- Unique meta descriptions
- Open Graph tags with OG image (1200x630)
- Twitter Card tags (summary_large_image)
- Geographic meta tags (geo.region, geo.placename, geo.position, ICBM)
- Hreflang tags
- Canonical URLs

#### Structured Data (JSON-LD)
- Person schema with full sameAs array (40+ URLs)
- WebSite schema
- Organization schema (AxiaASC)
- BreadcrumbList schema
- FAQPage schema (different questions/answers than other sites)
- ProfilePage schema

#### Identity Verification
- rel="me" links in head
- rel="author" link
- rel="me" on social profile links

#### Technical SEO
- robots.txt
- sitemap.xml with all pages
- 404.html custom error page
- Mobile-responsive design
- Fast loading (minimal dependencies)

### 4. Pages to Create

#### Homepage (index.html)
- Hero section with unique headline
- About section
- Ventures section (AxiaASC, Smash.com)
- Experience/timeline section
- Expertise/skills section
- Thought leadership section
- Connect/social section
- Footer

#### Profile Hub (/pages/index.html)
All profiles organized by category

#### Individual Profile Pages (~35 pages)
Each with unique descriptions linking to external profiles:

**Professional Networks:**
- LinkedIn (2 profiles)
- F6S
- GitHub

**Writing & Publications:**
- Medium
- Substack
- WordPress
- Quora
- Wattpad
- Goodreads (with book reviews)
- SpeakerDeck
- Issuu
- Scribd
- SlideShare

**Media & Content:**
- YouTube
- SoundCloud
- Flickr

**Social Media:**
- Instagram
- Twitter/X
- Pinterest

**Personal Profiles:**
- About.me
- Bento
- Gumroad
- Trustpilot
- Hotfrog

**Ventures:**
- AxiaASC
- Smash.com

**Websites:**
- Wix site
- Google Sites (2 sites)
- Rejuvie Med Spa
- CA Hotel Reviews
- LA Sushi Reviews
- Haro Gharbigi Social

### 5. Complete sameAs Array (for structured data)
```json
[
  "https://harogharbigi.com",
  "https://gharbigiharo.com",
  "https://www.linkedin.com/in/haro-gharbigi-20b00444/",
  "https://www.linkedin.com/pub/haro-gharbigi/6/483/8a9",
  "https://medium.com/@harogharbigi",
  "https://about.me/haro-gharbigi",
  "https://soundcloud.com/haro-gharbigi-306292856",
  "https://axiaasc.com",
  "https://harogharbigi.wixsite.com/axiaasc",
  "https://sites.google.com/view/haro-gharbigi/home",
  "https://www.youtube.com/watch?v=RMOM6F2hVnA",
  "https://www.youtube.com/watch?v=ahYbhYqB7G4",
  "https://www.youtube.com/watch?v=siFchbKm-yc",
  "https://www.instagram.com/harogharbigi/",
  "https://x.com/harotweet",
  "https://www.flickr.com/photos/125583669@N06/14525274720/",
  "https://harogharbigi.substack.com/",
  "https://harogharbigi.gumroad.com/",
  "https://bento.me/haro-gharbigi",
  "https://www.wattpad.com/user/HaroGharbigi",
  "https://www.f6s.com/haro-gharbigi",
  "https://www.goodreads.com/haro_gharbigi",
  "https://www.goodreads.com/review/show/8149080661",
  "https://www.goodreads.com/review/show/8149083753",
  "https://speakerdeck.com/harogharbigi",
  "https://www.trustpilot.com/users/69320403d7ccaa38575df8cc",
  "https://issuu.com/haro-gharbigi/docs/haro_gharbigi_-_the_ceo_s_guide_to_artificial_inte",
  "https://www.scribd.com/document/961078182/Haro-Gharbigi-The-CEO-s-Guide-To-Artificial-Intelligence",
  "https://smash.com",
  "https://rejuviemedspa.com",
  "https://cahotelreviews.com",
  "https://lasushireviews.com",
  "https://www.slideshare.net/HaroGharbigi",
  "https://github.com/haroxy/Haro-Gharbigi",
  "https://harogharbigi2.wordpress.com/",
  "https://harogharbigi2.wordpress.com/2025/12/11/the-ceos-guide-to-ai-implementation-why-healthcare-leaders-cant-afford-to-wait/",
  "https://www.pinterest.com/gharbigi2281/haro-gharbigi-board/",
  "https://www.hotfrog.com/company/93ffa059da51dab3306967d5d45218d7",
  "https://www.quora.com/profile/Haro-Gharbigi",
  "https://www.quora.com/What-are-the-best-AI-website-builders-now/answer/Haro-Gharbigi",
  "https://www.quora.com/Health-Which-brand-of-cigarettes-is-good-to-smoke-for-beginners/answer/Haro-Gharbigi",
  "https://www.quora.com/profile/Haro-Gharbigi/Are-there-any-updates-on-the-chemical-spill-on-the-East-Walker-River-from-any-locals-in-the-area",
  "https://www.harogharbigi-social.com/"
]
```

### 6. Key Person Information
- **Name:** Haro Gharbigi (also known as Gharbigi Haro, H. Gharbigi)
- **Title:** Founder & CEO
- **Company:** AxiaASC
- **Location:** Los Angeles, California, United States
- **Industry:** Healthcare Technology, AI
- **Experience:** Nearly two decades of entrepreneurial experience
- **Twitter:** @harotweet
- **Focus Areas:** AI-powered healthcare solutions, ambulatory surgery center software

### 7. File Structure
```
haro-gharbigi.com/
├── index.html
├── styles.css
├── favicon.svg (different design)
├── og-image.svg (1200x630, unique design)
├── robots.txt
├── sitemap.xml
├── 404.html
└── pages/
    ├── index.html (hub)
    ├── linkedin.html
    ├── medium.html
    ├── github.html
    ├── twitter.html
    ├── instagram.html
    ├── youtube.html
    ├── substack.html
    ├── wordpress.html
    ├── quora.html
    ├── goodreads.html
    ├── speakerdeck.html
    ├── issuu.html
    ├── scribd.html
    ├── slideshare.html
    ├── soundcloud.html
    ├── flickr.html
    ├── pinterest.html
    ├── aboutme.html
    ├── bento.html
    ├── gumroad.html
    ├── trustpilot.html
    ├── hotfrog.html
    ├── f6s.html
    ├── wattpad.html
    ├── axiaasc.html
    ├── smash.html
    ├── wix.html
    ├── google-sites.html
    ├── rejuviemedspa.html
    ├── cahotelreviews.html
    ├── lasushireviews.html
    └── harogharbigi-social.html
```

### 8. Cross-Linking
- Add links to harogharbigi.com and gharbigiharo.com in footer
- Include both sites in sameAs array
- Consider adding these sites as visible links on homepage

### 9. GitHub Repository
Push to: https://github.com/harofastlife/haro-gharbigi.com

---

## Important Notes
- ALL content must be uniquely written - no copy/paste from other sites
- Design must be visually distinct at first glance
- Every meta description must be unique
- FAQ questions should be different from other sites
- Test structured data with Google Rich Results Test after deployment
