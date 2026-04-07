# UDHAYAM JOB SERVICES LTD Hospitality Website Documentation

## Overview
This is a luxury, high-end corporate website for **UDHAYAM JOB SERVICES LTD**, a premium hospitality staffing agency based in London. The design focuses on elegance, elite branding, and professional workforce solutions.

## File Structure
- `index.html`: Home page with high-end hero section and statistics.
- `about.html`: Company vision, mission, and brand values.
- `services.html`: Comprehensive grid of professional staffing roles.
- `contact.html`: Dual-portal system for candidates and restaurant clients.
- `index.css`: Centralized luxury design system.
- `hero.png`: Premium hospitality background image.

## Connecting Forms to Google Sheets
To fulfill the requirement of storing data in Google Sheets automatically, you can use any of the following methods without needing a complex backend:

### Method 1: Using "SheetMonkey" or "Formspree" (Easiest)
1. Create a free account at [SheetMonkey](https://sheetmonkey.io/) or [Formspree](https://formspree.io/).
2. Connect your Google Sheet to the service.
3. Replace the `form` action in `contact.html` with your unique endpoint URL.
4. Add `name="..."` attributes to all input fields to match your Google Sheet column headers.

### Method 2: Google Apps Script (Custom & Free)
1. In your Google Sheet, go to **Extensions > Apps Script**.
2. Paste a basic "Google Sheets Form Handler" script (available in common web tutorials).
3. Deploy the script as a **Web App** with access set to "Anyone".
4. Update the `fetch()` call in your JavaScript to point to that Web App URL.

## Technical Highlights
- **Typography:** Cinzel (Logo/Premium Serif), Playfair Display (Headings) & Inter (Body/Sans-serif).
- **Animations:** AOS (Animate On Scroll) for premium entrance effects.
- **Responsiveness:** Fully optimized for mobile and tablet devices.
- **Glassmorphism:** Subtle blur and transparency on cards and navigation to create depth.
