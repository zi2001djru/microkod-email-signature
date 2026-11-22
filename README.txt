MICROCOD — PROFESSIONAL HTML EMAIL SIGNATURE
BLACK EDITION / MC MONOGRAM
==============================================

PROJECT FILES
-------------
index.html   Editable HTML email signature.
preview.png  Visual preview of the updated black design.
README.txt   Setup and learning guide.

DESIGN UPDATE
-------------
This edition uses:
- MC monogram instead of MK.
- A near-black (#090909) brand panel.
- White monogram and MICROCOD wordmark.
- Monochrome grey and black details.
- A clean white contact-information panel.

HOW TO ADD THE SIGNATURE TO GMAIL
---------------------------------
1. Open index.html in Chrome, Edge, or Firefox.
2. Select only the rendered signature (not the light grey page background).
3. Copy the selection.
4. Open Gmail > Settings (gear) > See all settings.
5. In General, scroll to Signature.
6. Click Create new and give it a name, such as MICROCOD.
7. Paste the copied signature into the signature editor.
8. Choose it for new emails and/or replies as desired.
9. Scroll to the bottom and click Save Changes.
10. Send a test email to another account and inspect the result.

IMPORTANT
---------
Gmail's signature editor accepts rendered content, not a raw HTML file upload.
Copy the rendered signature from the browser and paste it into Gmail.
Do not paste the source code into the signature editor.

EDITING THE CONTENT
-------------------
Open index.html in VS Code or another code editor.

- Change the name in the Name section.
- Change the job title in the Position section.
- Update both the mailto: address and the visible email text.
- Update both the tel: value and the visible phone number.
- Update the href and visible label for the portfolio and LinkedIn links.
- Edit inline color/background-color values to customize the palette.
- The MC letters are inside the left-column monogram cell.

WHY TABLES?
-----------
Email clients have inconsistent support for modern CSS layout features.
HTML tables provide a more predictable way to position content in email
signatures. This project uses table, tr and td for its two-column layout.

WHY INLINE CSS?
---------------
Some email clients remove or ignore styles in external stylesheets or parts
of the document head. Inline CSS places styles directly on HTML elements and
is generally a more dependable approach for email markup.

EMAIL TESTING CHECKLIST
-----------------------
- Inspect the signature in a browser first.
- Send a real test email through Gmail.
- Check Gmail web and mobile where possible.
- Test Outlook and Apple Mail if those clients matter to the recipient.
- Click every link and verify the destinations.
- Check spacing, text wrapping and legibility on a narrow screen.
- Check dark mode: some clients may adjust colors automatically.
- Avoid depending on JavaScript, Flexbox, Grid, remote fonts or background
  images for essential content.
- For wider testing, consider Litmus (litmus.com) or Email on Acid
  (emailonacid.com).

UPWORK PORTFOLIO SUGGESTION
---------------------------
Project title:
"Professional HTML Email Signature | Minimal Black MICROCOD Design"

Description:
"Designed and coded a minimalist, branded HTML email signature using
email-safe tables and inline CSS. Includes a custom MC monogram, clickable
email, phone, portfolio and LinkedIn links, and clean editable source code.
Built with Gmail-oriented email markup and without JavaScript, Flexbox or Grid."

Show the preview image, a code excerpt of the table structure, and (after
testing) a screenshot of the signature inside Gmail. Be precise: this project
uses Gmail-friendly techniques, but it has not been certified across every
email client or version.

LEARNING TIP
------------
Change one thing at a time in index.html, refresh the browser, and compare
the result. Then send yourself a test email. Browser preview and email-client
rendering are two separate checks.
