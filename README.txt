OMKAR WAGHMARE — PORTFOLIO WEBSITE

Files:
- index.html: Complete responsive portfolio website
- Omkar_CV.pdf: Resume linked from the website

Preview locally:
1. Extract the ZIP.
2. Open index.html in Chrome, Edge, or Firefox.
3. Internet is needed for Google Fonts; the rest of the site is self-contained.

Before publishing:
- Verify social/profile URLs and project links.
- Confirm dates and project metrics match your latest information.
- The contact email opens the visitor's email app; no backend contact form is configured.
- Deploy the folder using GitHub Pages, Netlify, or Vercel.

CONTACT FORM SETUP
------------------
The contact section is included and validates the visitor's name, email, subject, and message.
Until a Formspree endpoint is configured, clicking Send Message opens the visitor's email app with the message pre-filled (the visitor must press Send).

To enable direct form submission:
1. Create a form at https://formspree.io/ and set the recipient to omwaghmare2425@gmail.com.
2. Verify your recipient email if Formspree asks.
3. Copy your form endpoint, which looks like https://formspree.io/f/xxxxxxxx.
4. Open index.html and find: action="https://formspree.io/f/YOUR_FORM_ID"
5. Replace the placeholder URL with your real Formspree endpoint.
6. Save, reload the site, and submit a test message. Confirm it arrives in your inbox.

Do not publish an invented endpoint. Direct form delivery is not enabled until you configure and verify your real endpoint.
