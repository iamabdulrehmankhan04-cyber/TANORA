TANORA WEBSITE PROTOTYPE

Preview locally:
1. Extract this folder.
2. Open index.html in a modern browser.
3. For a more realistic local preview, run a local static server from this folder, for example: python -m http.server 8000, then open http://localhost:8000.

Files:
- HTML pages: homepage plus service, process, treatments, pricing, about, physician, FAQ, resources, contact, booking, privacy, notices, and accessibility pages.
- styles.css: responsive styling and TANORA design tokens.
- script.js: shared navigation, FAQ interactions, pricing data, and demo form/booking behavior.
- assets/: temporary SVG wordmark and favicon.
- sitemap.xml and robots.txt: replace YOUR-DOMAIN before launch.

IMPORTANT BEFORE PUBLIC LAUNCH
- This is a front-end prototype, not a production clinical website.
- The booking and patient portal URLs are placeholders. Configure approved EHR/scheduler and portal destinations.
- Contact form does not transmit or store information. Connect an approved, privacy-reviewed form service before launch.
- No payments or recurring membership billing are enabled.
- Replace placeholder physician imagery with an approved headshot and add the approved biography.
- Confirm final services, prices, membership terms, state availability, legal notices, privacy policy, Notice of Privacy Practices, terms, and accessibility statement.
- Review all clinical copy with the practice's medical/legal team. Do not use this website to collect clinical PHI.
- Fonts are loaded from Google Fonts; confirm licensing, availability, and privacy requirements for the production deployment.
- Replace YOUR-DOMAIN in sitemap.xml and robots.txt.
- Configure HTTPS, hosting, security headers, backups, analytics consent, and production testing.

The price list is centralized in the TANORA.prices array in script.js. The tagline is centralized in TANORA.tagline.
