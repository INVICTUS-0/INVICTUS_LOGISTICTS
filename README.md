# INVICTUS Logistic

## Student Information
Name: Mphidi Asakundwi
Student number: ST10521417
Module code: WEDE5020
Submission: Part 1

## Project Overview

INVICTUS Logistics is a newly established, Pretoria-based freight
coordination start-up, founded in 2025 to connect small manufacturers,
e-commerce sellers and retailers across Gauteng with reliable road-freight
and last-mile delivery partners. It fills a gap left by logistics providers
that focus only on large corporate contracts, giving small and medium
businesses the same reliability without needing a large-scale contract.

Mission: To make dependable, transparent freight logistics accessible
and affordable to small and medium businesses.

Vision: To become Gauteng's most trusted logistics partner for SMEs,
known for reliability and technology-driven shipment tracking.

Target Audience: Small and medium business owners — manufacturers,
online sellers and retailers, roughly 25–50 years old — who need regular
freight or delivery and value clear pricing and reliable communication.

## Website Goals and Objectives

- Generate leads through an online quote-request form, reducing dependence
  on phone and email enquiries.
- Build client trust by clearly presenting services, coverage areas and
  shipment tracking.
- Make the site easy to navigate, keeping it to six essential pages so a
  customer never needs more than a couple of clicks to reach what they need.

Key Performance Indicators (KPIs): monthly quote-request submissions,
average session duration, homepage bounce rate, and clicks on the
"Get a Quote" button.

## Key Features and Functionality
- Home - hero introduction, services snapshot, and the combined
  login/register section (`#account`), so account access never requires
  leaving the homepage.
- About Us - company history, mission, vision and target audience.
- Services - three hauling services (Port & Bay, Airport, Mine), each
  with its own description and a direct link into the quote form.
-Get a Quote - a structured enquiry form capturing customer details,
  cargo details, and pickup/delivery information.
- Track Shipment - a reference-number lookup, with a sample shipment
  timeline showing the stages a booking moves through.
- Contact - a short contact form plus business hours and location.

Planned for later parts: form validation, a live quote calculator, an
interactive shipment tracker, and login/session handling (Part 3 —
JavaScript), styled throughout with the colour scheme and typography set
out in the project proposal (Part 2 — CSS).

## Timelines and Milestones

Part 1 | Research, proposal, and raw semantic HTML structure
Part 2 | CSS styling applied to the existing structure
Part 3 | Java Script functionality (validation, tracker, login logic

## Part 1 Details

Part 1 covered:

1. Research into two website proposals — INVICTUS Logistics (the site
   being built) and Ubuntu Community Library (a non-profit comparison
   proposal) — see `/proposals`.
2. Planning the site structure (see **Sitemap** below).
3. Building `index.html`, `about.html`, `services.html`, `quote.html`,
   `track.html`, and `contact.html` as raw, semantic HTML with no CSS or
   JavaScript, using comments throughout to explain each section.

Part 2 (CSS styling) and Part 3 (JavaScript functionality) will follow in
future submissions/edits to this repository.

## Sitemap

```
Home (index.html)
│
├── About Us (about.html)
│
├── Services (services.html)
│   ├── Port & Bay Hauling      → #bay
│   ├── Airport Hauling         → #airport
│   └── Mine Hauling            → #mine
│
├── Get a Quote (quote.html)
│
├── Track Shipment (track.html)
│
├── Contact (contact.html)
│
└── Login / Register            → index.html #account
    (a section on the homepage, not a separate page)
```

Six pages in total, all sharing the same header navigation and footer, so
any page is reachable in one click from any other page. Login and Register
are not separate pages — both forms live in the `#account` section on the
homepage to keep navigation as simple as possible.

## Changelog

### Part 1 - [2026/08/14]
Added 
- Initial repository structure and README.
- Two website proposals (INVICTUS Logistics, Ubuntu Community Library).
- Raw semantic HTML for all six INIVICTUS Logistic pages.
- Sitemap documentation.

## References

- HOSTAFRICA (2026) How much is it to host a website? [online] Available
  at: https://hostafrica.co.za/blog/hosting/how-much-is-it-to-host-a-website/
  (Accessed: 05 August 2026).
- New Perspective Design (2026) What is the cost of creating a website in
  South Africa? [online] Available at:
  https://www.newperspectivestudio.co.za/wp/what-is-the-cost-of-creating-a-website-in-south-africa/
  (Accessed: 05 August 2026).
- Owl Media (2026) How much does a website cost in South Africa? [online]
  Available at:
  https://owlmedia.co.za/how-much-does-a-website-cost-in-south-africa-2026-pricing-guide/
  (Accessed: 05 August 2026).
- Syniq Solutions (2026) How much does a website cost in South Africa?
  [online] Available at:
  https://www.syniqsolutions.co.za/blog/how-much-does-a-website-cost-south-africa
  (Accessed: 06 August 2026).
- Wired Web Services (2026) How much does a website cost in 2026?
  [online] Available at: https://wiredwebservices.co.za/how-much-does-a-website-cost-in-2026/
  (Accessed: 06 August 2026).
- Mozilla Developer Network (MDN) (2026) HTML: HyperText Markup Language.
  [online] Available at: https://developer.mozilla.org/en-US/docs/Web/HTML
  (Accessed: 06 August 2026).
  

