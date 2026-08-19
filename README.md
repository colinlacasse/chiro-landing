# Chiropractor Landing Page

A simple, responsive landing page for a chiropractic practice. Built with plain HTML, CSS, and a small amount of JavaScript—no build step required.

## Preview locally

Open `index.html` in your browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Customize

- **Practice name & copy** — edit `index.html`
- **Colors & typography** — edit CSS variables at the top of `styles.css`
- **Contact info** — update phone, email, address, and hours in the contact section

## Typography

Brand fonts from your logo delivery are in `fonts/`:

| Use | Font | File |
|-----|------|------|
| Logo & H1 | Lyon Sans | `fonts/Lyon-Sans.ttf` |
| Sub-headers, H2/H3, eyebrows | Bangla MN | `fonts/Bangla MN.ttc` |
| Body copy | Arial | Helvetica, Futura, sans-serif fallbacks |

Bangla MN is the primary sub-font; Audrey remains listed as a CSS fallback if the bundled font fails to load.
