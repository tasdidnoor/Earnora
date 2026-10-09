# Earnora

A responsive, multi-page website for Earnora, a Toronto-based customer loyalty and retention consultancy for local businesses.

> We build loyalty programs that actually work.

## About

Earnora helps cafés, salons, restaurants, and retailers build customer loyalty and retention programs. The site presents Earnora's services, approach, pricing information, frequently asked questions, and contact options.

## Website features

- Home, Services, Pricing, About, Contact, FAQ, Privacy Policy, Terms of Service, and Cookie Policy pages
- Responsive navigation and layouts
- Customer loyalty service information and process overview
- Cookie consent banner with preference controls
- Guided Earnora Assistant with quick replies
- FAQ content, privacy information, and terms page
- Search metadata, structured data, sitemap, and robots instructions
- Seamlessly looping integration-logo rows on the home page

## Run locally

The site is static HTML, CSS, and JavaScript. Serve the project directory with any local web server. For example, with Python 3:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

You can also open `index.html` directly, though a local server is recommended because the Privacy Policy page loads its policy content from a separate HTML file.

## Project files

- `index.html` and the other top-level HTML files: individual site pages
- `app.js`: page content, shared components, and browser interactions
- `styles.css`: responsive layout and visual design
- `EA.png`: Earnora logo asset
- `privacy-policy-earnora.html`: full privacy-policy content loaded on the Privacy page
- `sitemap.xml` and `robots.txt`: search-engine discovery files
- `Plan_Init.txt`: internal planning brief (excluded from Git by `.gitignore`)

## Integrations and launch notes

Booking, contact-form submission, and newsletter signup are placeholders and are not connected to external services. Before launch, connect the chosen providers and review the Privacy Policy and Terms of Service against actual business practices.

The configured site URL and contact email are `https://earnora.tasdidnoor.com` and `contact.earnora@tasdidnoor.com`; configure the corresponding domain and email service for them to work.
