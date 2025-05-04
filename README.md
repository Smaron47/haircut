# haircut
**Cutznix Barbershop & Hair Salon Website – Full Documentation**

---

## Table of Contents

1. Overview
2. Key Features
3. Technology & Dependencies
4. Directory and File Structure
5. HTML Template Breakdown

   * 5.1 `<head>` Section
   * 5.2 Stylesheets and Dark Mode Support
   * 5.3 Preloaded Sprites & Icons
   * 5.4 Meta Tags & SEO
   * 5.5 JavaScript Includes
6. Page Layout & Sections

   * 6.1 Header & Navigation
   * 6.2 Hero / Slider Area
   * 6.3 Services / Bookings
   * 6.4 About / Gallery
   * 6.5 Testimonials
   * 6.6 Call-to-Action / Footer
7. Responsive Design
8. CSS & Theming

   * 8.1 Custom Classes
   * 8.2 Media Queries
9. JavaScript Functionality

   * 9.1 Dynamic Height Calculation
   * 9.2 Cookie Consent & Analytics Integration
   * 9.3 Google Analytics & Tag Manager
10. Third-Party Libraries
11. Performance Optimization

* 11.1 Preloading Assets
* 11.2 Deferred / Async Scripts

12. SEO Considerations

* 12.1 Title & Description
* 12.2 Robots & Indexing
* 12.3 Social Meta Tags (Open Graph)

13. Deployment & Hosting
14. Customization Guide

* 14.1 Changing Colors & Fonts
* 14.2 Updating Images
* 14.3 Modifying Sections

15. Troubleshooting & FAQs
16. License & Credits

---

## 1. Overview

Cutznix is a fully responsive **Barbershop & Hair Salon** website template built with Elementor (WordPress) but also available as static HTML for preview. It showcases services, team, gallery, testimonials, and booking calls-to-action.

---

## 2. Key Features

* Responsive layout for mobile, tablet, and desktop
* Dark mode CSS support
* Hero slider / full-screen preview integration
* Services section with booking links
* Gallery and testimonials carousels
* Integrated Google Analytics, Tag Manager, and Cookie Consent
* Preloaded sprites for logos and icons

---

## 3. Technology & Dependencies

* **HTML5** markup
* **CSS3** with preloaded sprite sheets
* **JavaScript** (jQuery, analytics scripts)
* **Cookiebot** for consent management
* **Google Analytics (Universal & GTM)**
* **ThemeForest** preview infrastructure

---

## 4. Directory and File Structure

```
cutznix_preview/
├── index.html                    # Main HTML file
├── demo_files/                   # CSS, JS, and iframe content
│   ├── *.css                     # Compiled stylesheets
│   ├── main.b4887131.js          # Core scripts
│   ├── analytics.js              # Google Analytics loader
│   ├── gtm.js                    # Google Tag Manager bootstrap
│   └── saved_resource.html       # Embedded preview content
└── assets/                       # External sprite images and icons
```

---

## 5. HTML Template Breakdown

### 5.1 `<head>` Section

* Character set UTF-8
* Viewport meta for responsive scaling
* DNS prefetch for Envato static domains
* Preload critical sprite images for logos and common icons

### 5.2 Stylesheets and Dark Mode Support

* Two compiled CSS files loaded from `demo_files/`
* Dark-mode placeholders (`dark-mode-custom-link`, etc.) for dynamic theming

### 5.3 Preloaded Sprites & Icons

* Logos sprite sheet (`logos-*.png`)
* Common icons sprite sheet (`common-*.png`)

### 5.4 Meta Tags & SEO

* `<title>`: Cutznix Barbershop & Hair Salon Elementor Template Kit Preview
* `<meta name="description">` describing template usage
* `<meta name="robots" content="noindex, nofollow">` for preview pages
* `<meta turbo-visit-control="reload">` for Turbo links

### 5.5 JavaScript Includes

* Core Envato preview scripts (`core.js`, `gtm.js`, `bat.js`)
* Analytics trackers (`ec.js`, `linkid.js`, `analytics.js`)
* Full-screen preview resizing logic

---

## 6. Page Layout & Sections

### 6.1 Header & Navigation

* Sticky header within `.preview__header`
* Responsive menu toggling

### 6.2 Hero / Slider Area

* `<iframe>` with class `.full-screen-preview__frame` for live preview
* Dynamic height computed on resize

### 6.3 Services / Bookings

* Section highlighting barber services, booking buttons styled via CSS classes

### 6.4 About / Gallery

* Grid gallery of salon images
* About text and team member bios

### 6.5 Testimonials

* Carousel of client testimonials loaded via JS

### 6.6 Call-to-Action / Footer

* Contact information, social links, newsletter signup
* Footer credits and licensing info

---

## 7. Responsive Design

* Media queries adjust layout at 320px, 768px, 1024px breakpoints
* Flexbox and grid used for section alignment

---

## 8. CSS & Theming

### 8.1 Custom Classes

* `.team`, `.hero`, `.services`, `.gallery`, `.testimonials`, `.footer`

### 8.2 Media Queries

* `@media (max-width: 768px)` for mobile menu and stacking

---

## 9. JavaScript Functionality

### 9.1 Dynamic Height Calculation

* `calcHeight()` adjusts iframe based on header height

### 9.2 Cookie Consent & Analytics Integration

* Cookiebot events to control loading of trackers
* DataLayer events for GTM

### 9.3 Google Analytics & Tag Manager

* Universal Analytics (`analytics.js`) and GTM (`gtm.js`) integration
* Outbound link decoration and event tracking

---

## 10. Third-Party Libraries

* **jQuery**: DOM manipulation and event handling
* **Cookiebot**: GDPR/CCPA cookie consent
* **Google Analytics**: pageview and event tracking
* **Google Tag Manager**: marketing tag orchestration

---

## 11. Performance Optimization

### 11.1 Preloading Assets

* `<link rel="preload">` for critical images

### 11.2 Deferred / Async Scripts

* All analytics and preview scripts loaded with `async` attribute

---

## 12. SEO Considerations

* Ensure production pages remove `noindex, nofollow`
* Add Open Graph and Twitter Card meta tags for social sharing

---

## 13. Deployment & Hosting

* Host static files on any web server (Apache, Nginx)
* For WordPress, import as an Elementor Template Kit

---

## 14. Customization Guide

### 14.1 Changing Colors & Fonts

* Update CSS variables or rebuild stylesheets via Sass

### 14.2 Updating Images

* Replace sprite sheets and gallery images under `assets/`

### 14.3 Modifying Sections

* Edit HTML structure in `index.html` or import into Elementor

---

## 15. Troubleshooting & FAQs

* **Iframe not resizing?** Ensure `.preview__header` exists and JS is loaded
* **Analytics not firing?** Confirm Cookiebot consent and correct UA IDs

---

## 16. License & Credits

* **Template Source:** ThemeForest “Cutznix” by \[Author]
* **License:** Envato License applies for distribution

---

*End of Documentation for Cutznix Barbershop & Hair Salon Website.*
