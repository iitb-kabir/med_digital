# MedDigital Healthcare Presentation

MedDigital is a single-page healthcare digital services presentation website for doctors and clinics. It explains common patient and clinic management problems, presents a digital website and appointment solution, shows pricing, and ends with direct contact options.

## Project Files

```text
med_digital/
|-- healthcare-presentation.html
`-- Readme.md
```

## Features

- Fully responsive one-page presentation
- Dark premium healthcare visual design
- Hero section with clinic website mockup
- Patient and doctor problem sections
- Solution overview and live system preview
- Benefits for doctors and patients
- Pricing section with optional add-ons
- Launch journey/process section
- Contact card with WhatsApp and email links
- Scroll reveal animations and reading progress bar

## Tech Used

- HTML
- CSS
- Vanilla JavaScript
- Tailwind CDN
- Google Fonts: `Sora` and `DM Sans`

No build system or framework is required.

## How to Run

Open the HTML file directly in a browser:

```text
healthcare-presentation.html
```

You can also use a simple local server if preferred:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/healthcare-presentation.html
```

## Main Sections

- `Hero`: Brand message, call-to-action buttons, and clinic mockup
- `Patient Problems`: Issues patients face when finding or contacting clinics
- `Doctor Problems`: Operational problems doctors and clinic staff manage daily
- `Solution`: MedDigital website and appointment solution
- `Live Preview`: Visual preview of a clinic website system
- `Benefits`: Separate benefits for doctors and patients
- `Pricing`: Starter package, add-ons, and maintenance policy
- `Launch Journey`: Step-by-step launch process
- `Why MedDigital`: Positioning and trust points
- `Contact`: WhatsApp, email, and consultation CTA

## Customization

Most content and styling is inside `healthcare-presentation.html`.

Common things to update:

- Brand name and tagline
- Pricing and add-on amounts
- WhatsApp number
- Email address
- Clinic/service descriptions
- Footer copyright text
- Colors in the `:root` CSS variables

Important contact links currently used:

```html
https://wa.me/918822093903
mailto:dhiraj.deka@meddigital.in
```

## Deployment

Because this is a static HTML page, it can be deployed on:

- GitHub Pages
- Netlify
- Vercel
- Any standard web hosting provider

Upload `healthcare-presentation.html` as the main page, or rename it to `index.html` before deployment.

## Notes

The page uses external CDN resources for Tailwind CSS and Google Fonts, so an internet connection is required for the full design to load correctly.
