# Hoody's Sourdough Kitchen website

The marketing site for Hoody's Sourdough Kitchen, live at https://hoodyssourdoughkitchen.com.au

## What's in here

| File | What it is |
| --- | --- |
| `index.html` | Home page, including the email signup form |
| `freebies.html` | Free PDF downloads page, with a GA4 event per download |
| `doughly.html` | Landing page for the DoUGHLY dehydrated starter |
| `Hoody_Sourdough_Starter_Guide.pdf` | Freebie: starter guide |
| `Hoody_Sourdough_Starter_Feeding_Ratios.pdf` | Freebie: feeding ratios |
| `Temperature_Conversion_guide.pdf` | Freebie: temperature conversions |
| `logo.png`, `webpage_background.jpg` | Brand images |
| `_headers` | Netlify security headers, applied to every page |

## How it works

- Plain static HTML, no build step and no server-side code.
- Hosted on Netlify (project: `hoodys-sourdough-website`).
- The email signup form uses Netlify Forms (`data-netlify="true"` with a honeypot field).
- Analytics: GA4, measurement ID `G-9CL9QCDL4S`.

## Deploying

Keep this repo and the live site in sync. If you ever deploy by drag and drop, include `_headers` in the upload or the security headers will be dropped from the live site.

## Brand basics

- Colours: teal `#4A9EA6`, cream `#F0EDE8`, near-black `#1C1C1A`
- Fonts: Cormorant Garamond (headings), Montserrat (body)
