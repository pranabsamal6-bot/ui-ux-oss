# Halcyon Graft: Cyborg-Themed Landing Page

A responsive landing page for a fictional cybernetic augmentation clinic, built for the Techfest IIT Bombay task "Cyborg-Themed Landing Page Development".

**Author:** Babun Mal, BSc Data Science (2nd year), Bhadrak Autonomous College
**Live demo:** _add your GitHub Pages link here_

## Concept

The page is built around one idea: *human first, machine where it counts.* The hero is an eye split down the middle, with an organic human half and a mechanical half. Dragging the slider scans from one to the other.

## Features

- Interactive hero: drag (or use the arrow keys on) the slider to reveal the machine side
- Three augmentation modules with expandable spec details
- Four-step process timeline
- Booking form with basic validation and a confirmation message
- Fully responsive: layout reflows for tablets and phones
- Accessible: keyboard focus styles, ARIA labels, and `prefers-reduced-motion` support

## Tech stack

- HTML5, CSS3 (custom properties, grid, flexbox, `clip-path`)
- Vanilla JavaScript, with no frameworks or build step
- Google Fonts: Chakra Petch and IBM Plex Sans (system fonts as fallback)
- Inline SVG for all artwork

## Design choices

| Element | Choice |
|---|---|
| Bone `#ece4d8` | The human side |
| Plate `#232a31` and graphite `#12161a` | The machine side |
| Optic red `#ff4d2e` | The cybernetic eye and key accents |
| Coolant teal `#49c5b6` | Circuit lines and interactive states |

## Project structure

```
.
├── index.html   # the whole page (HTML, CSS and JS in one file)
└── README.md
```

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

No installation needed.

## Deploy with GitHub Pages

1. Go to **Settings → Pages** in your repository.
2. Under **Source**, choose the `main` branch and the `/ (root)` folder.
3. Save. Your site will be live at `https://<username>.github.io/<repo-name>/`.

## Notes

Halcyon Graft is a fictional brand created for a design exercise. The booking form does not send data anywhere.
