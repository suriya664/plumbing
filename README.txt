===========================================
PLUMBING SERVICES WEBSITE - README
===========================================

PROJECT STRUCTURE
-----------------
/
├── index.html (Homepage)
├── home2.html (Alternative homepage)
├── about.html
├── services.html
├── service-details.html
├── projects.html
├── testimonials.html
├── faq.html
├── contact.html
├── login.html (No header/footer, logo centered)
├── register.html (No header/footer, logo centered)
├── 404.html
├── assets/
│   ├── css/
│   │   └── style.css (Global styles)
│   ├── js/
│   │   └── script.js (Global JavaScript)
│   ├── images/
│   │   ├── favicon.ico (32x32)
│   │   └── favicon-192x192.png (192x192)
│   └── icons/ (Social media icons - SVG format)
└── README.txt (This file)

FAVICON IMPLEMENTATION
----------------------
The favicon is included in the <head> section of every HTML page using:
<link rel="icon" href="assets/images/favicon.ico" type="image/x-icon">
<link rel="apple-touch-icon" sizes="192x192" href="assets/images/favicon-192x192.png">

HOW TO VERIFY FAVICON:
1. Open any HTML page in a browser
2. Check the browser tab - the favicon should appear next to the page title
3. The favicon appears on ALL pages (index.html, about.html, services.html, etc.)
4. Verify in different browsers (Chrome, Firefox, Edge, Safari)

HOW TO CHANGE THE FAVICON:
1. Create a new favicon.ico file (32x32 pixels recommended)
2. Create a new favicon-192x192.png file (192x192 pixels for Apple devices)
3. Replace the files in /assets/images/
4. Keep the same filenames: favicon.ico and favicon-192x192.png
5. Clear browser cache and reload pages to see the new favicon

NOTE: Currently, placeholder favicon files need to be created. You can:
- Use an online favicon generator (e.g., favicon.io, realfavicongenerator.net)
- Create a simple icon using image editing software
- Use a plumbing-related icon (wrench, pipe, water drop, etc.)

FEATURES IMPLEMENTED
-------------------
✓ Responsive navigation with hamburger menu
✓ Active page highlighting in navigation
✓ Shared header and footer across all pages (except login/register)
✓ Form validation with AJAX submission
✓ Smooth scroll behavior (respects prefers-reduced-motion)
✓ Lazy loading for images
✓ Social media icons with brand colors
✓ Clickable phone numbers and email addresses
✓ Mobile-friendly design
✓ Accessible focus states
✓ SEO meta tags and structured data

TECHNICAL DETAILS
-----------------
- CSS: Uses CSS variables for consistent theming
- JavaScript: Vanilla JS (no dependencies)
- Fonts: Inter (with Poppins fallback)
- Images: Placeholder URLs from DepositPhotos/StockFresh
- Forms: Client-side validation with progressive enhancement
- Browser Support: Modern browsers (Chrome, Firefox, Safari, Edge)

CUSTOMIZATION
-------------
To customize colors, edit CSS variables in assets/css/style.css:
- --primary-color: Main brand color
- --secondary-color: Accent color
- --text-dark: Main text color
- etc.

To update contact information, search and replace:
- Phone: +1 555 123 4567
- Email: info@plumbingpro.com
- Address: 123 Main Street, City, State 12345

To update social media links, edit the href attributes in footer sections.

TESTING CHECKLIST
-----------------
See qa-checklist.txt for detailed testing procedures.

