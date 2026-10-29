# Bloomberg Dev — UK Property Website

Responsive static multi-page website for a UK real estate/property brand. Built with HTML, CSS and vanilla JavaScript.

## Pages
- `index.html` — homepage, search form and featured property cards
- `properties.html` — searchable/filterable example property listings
- `property-detail.html` — example listing detail page
- `about.html` — about the brand
- `sell.html` — seller information and valuation enquiry form
- `contact.html` — contact information and enquiry form
- `privacy.html` — privacy policy starter draft
- `terms.html` — terms and conditions starter draft
- `cookies.html` — cookie policy starter draft

## Run locally
Open `index.html` in a browser, or serve this folder with any static web server, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing
1. Replace the example listings and prices with verified live properties; listings are currently illustrative.
2. The contact and valuation forms are front-end demos and do not send messages. Connect them to a secure backend, email service or CRM and add server-side validation, spam protection and secure handling of personal data.
3. Review privacy, terms and cookie policy drafts against your real practices and applicable UK requirements; obtain professional advice where appropriate.
4. Verify the business name, contact details, any required property redress scheme membership, professional credentials and other applicable disclosures.
5. Images use remote Unsplash image URLs. For production, confirm licensing/usage and consider hosting properly licensed optimised copies locally.
6. Configure DNS/hosting for `bloomberg-dev.com` and set up HTTPS.

## Brand
The logo in `assets/logo.png` is cropped from the image supplied by the user. Brand colours are charcoal, slate blue-grey and white, inspired by the supplied mark.
