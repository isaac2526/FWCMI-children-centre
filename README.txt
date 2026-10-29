FWCMI CHILDREN CENTRE FUNDRAISING LANDING PAGE
==============================================

CONTENTS
- index.html: complete responsive single-page website
- config.js: GoFundMe campaign link setting
- assets/: FWCMI logo and photographs extracted from the supplied needs assessment report

HOW TO ADD YOUR GOFUNDME LINK
1. Open config.js in a text editor.
2. Replace the empty value after goFundMeUrl with the full campaign URL, for example:
   goFundMeUrl: "https://www.gofundme.com/f/your-campaign-name"
3. Save the file and upload the entire folder contents again. Every Donate button will then open the campaign in a new tab.
4. Until the URL is set, the Donate buttons display a small notice instead of sending visitors to a broken link.

HOW TO PREVIEW
- Extract the ZIP.
- Open index.html in a modern browser. Internet access is recommended for the Space Grotesk and DM Sans web fonts; local fallbacks are included.
- The page is static HTML/CSS/JavaScript and does not require npm, a build step, payment credentials, or a backend.

DEPLOY / DRAG AND DROP
- Upload the extracted website folder (or its contents, depending on the host) to a static hosting service that supports drag-and-drop deployment.
- Keep index.html, config.js and the assets folder together. Do not upload index.html alone.

FEATURES
- Responsive mobile/tablet/desktop layout
- Light/dark mode toggle (remembers visitor preference in their browser)
- Glassmorphism navigation and floating cards
- Scroll reveal effects, hover animations, subtle motion and reduced-motion support
- Real photos and logo from the supplied FWCMI needs assessment report
- Six needs with the supplied budget allocations
- Campaign target and budget context, with no fabricated live fundraising progress
- Email and phone contact links
- SEO/social-sharing metadata

IMPORTANT BEFORE PUBLIC LAUNCH
- Add the official GoFundMe campaign URL to config.js.
- Confirm that the campaign goal and budget figures remain current with FWCMI management.
- Confirm permission to publish the supplied children's photographs and ensure the organisation's child safeguarding/privacy requirements are met.
- Social media links were not added because none were supplied.
- The page does not collect donations or payment details itself; donations are handled by GoFundMe.
