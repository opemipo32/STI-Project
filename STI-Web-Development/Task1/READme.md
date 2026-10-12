# Ajayi Opemipo Andrew — Personal Portfolio

A single-page personal portfolio built with HTML and CSS for **Task 1: Personal Portfolio Website**. It uses a clean blue and white design.

**Entry point:** `index.html`

---

## File Structure

```
portfolio/
├── index.html      # Single-page site (header, about, skills, contact)
├── style.css       # All styling
├── Myself.jpeg     # Profile photo
└── README.md       # This file
```

Keep all files in the same folder. `index.html` loads `style.css` and `Myself.jpeg` from its own directory.

---

## How to View It

No build step or server needed.

1. Download all files into one folder.
2. Double-click `index.html` to open it in any browser.

An internet connection is only needed to load the Google Fonts. Without it, the site falls back to system fonts.

---

## Sections

| Section | Content |
|---|---|
| **Navigation** | Sticky bar with smooth-scroll links to About, Skills and Contact |
| **Header** | Name, title, short intro, profile photo and two buttons |
| **About Me** | Short bio, background story and quick facts (location, education, career path) |
| **Skills** | Core web skills and transferable skills from a data and operations background |
| **Contact** | Email, phone, location and a contact form |

---

## Design System

| Name | Hex | Used for |
|---|---|---|
| Navy | `#0A2A5E` | Header, headings, footer |
| Blue | `#1F5FD6` | Accents, buttons, focus outlines |
| Sky | `#E8F0FD` | Alternate section backgrounds, inputs |
| White | `#FFFFFF` | Page background, cards |

**Typography**
- **Headings:** Space Grotesk
- **Body:** Inter

---

## Tech Stack

- HTML5 with semantic tags (`<nav>`, `<header>`, `<main>`, `<section>`, `<footer>`)
- CSS3 only, using Grid and Flexbox, with no frameworks and no JavaScript
- `scroll-behavior: smooth` for in-page navigation
- Fonts from the Google Fonts CDN

---

## Responsiveness

| Breakpoint | Behaviour |
|---|---|
| `≤ 860px` | Header, about and contact stack to one column; skills grid drops to 2 columns |
| `≤ 560px` | Nav stacks; skills grid drops to a single column; footer centres |

---

## Task 1 Checklist

- [x] HTML and CSS only
- [x] Single-page website
- [x] Header with name and title
- [x] About Me section
- [x] Skills section
- [x] Contact section
- [x] Clean layout with consistent spacing and alignment
- [x] Blue and white colour scheme

---

## Notes

- The contact form is a front-end demo and does not send messages yet.
- The address is limited to state and country level, so avoid adding a full home address if you publish the site.

**Built by Ajayi Opemipo Andrew.**