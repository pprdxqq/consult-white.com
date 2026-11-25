# Consult White website

A static multi-page website for Consult White.

## Pages
- `index.html` — Home
- `leistungen.html` — Services overview
- `praxismanagement.html` — Practice management
- `abrechnung.html` — Billing service
- `marketing.html` — Marketing and public presence
- `consult-whai-te.html` — Consult Wh(ai)te / tailored AI solutions
- `team.html` — About the team
- `karriere.html` — Careers
- `kontakt.html` — Contact
- `impressum.html` — Legal notice
- `datenschutz.html` — Privacy notice

Shared presentation and behaviour live in `styles.css` and `site.js`.

## Preferences
The first-visit dialog lets visitors choose German or English and light or dark mode. Choices are stored in localStorage and can be changed from the header.

## Contact form
The contact form opens the visitor's email application using a prefilled mailto message. It does not store or transmit form data to a backend.\n\n## Appointment planner\nThe appointment page includes an interactive date picker, time-slot selection and contact details form. It is deliberately a frontend preview only: it does not reserve a slot, send data, or check real availability. A booking backend / calendar integration must be connected before the feature can accept real appointments.

## Before production
- Review the legal notice and privacy notice with the responsible legal adviser. The privacy page explicitly flags that the previous notice may no longer reflect the actual hosting and processing setup.
- Confirm all business details and service descriptions with Consult White.
- Configure the desired hosting/deployment target and custom domain.
- Add a backend only if server-side form delivery or CRM integration is required.

## Design attribution
Design direction incorporates principles from [unslop by Damir Sokolovsky](https://github.com/heydamir/unslop), licensed under CC BY 4.0.
