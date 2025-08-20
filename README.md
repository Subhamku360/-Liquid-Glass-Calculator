# Liquid Design Calculator

A sleek, responsive calculator UI built with HTML5 and modern CSS (glassmorphism + CSS Grid) over an animated background video. This project focuses on visual design and layout; calculation logic is intentionally omitted so you can integrate your own JavaScript behavior.

## Repository description (copy‑paste for GitHub)
Sleek, responsive glassmorphism calculator UI with background video — built with HTML5 + CSS Grid.

## Features
- Glassmorphism card with blur, rounded corners, and soft inner shadows
- Full‑screen looping background video with object-fit: cover
- Responsive layout using CSS Grid for the keypad
- Subtle hover states for interactive feel
- Zero JavaScript by default (UI/UX only), making it easy to wire up your own logic

## Tech stack
- HTML5
- CSS3 (Grid, backdrop-filter, semi‑transparent layers)

## Getting started
1. Clone or download the repository.
2. Open `index.html` directly in your browser.
3. Ensure `video.mp4` is present in the project root so the background plays.

## Project structure
- `index.html`: Markup for the calculator UI and background video
- `style.css`: Styles for the glassmorphism layout and responsive grid
- `video.mp4`: Background video (replaceable)
- `pexels-pixabay-220182.jpg`: Optional image asset

## Customization
- Background video: Replace `video.mp4` with your own file (same path/name or update the `<source>` in `index.html`).
- Background image (optional fallback): In `style.css`, there is a commented `background` line under `html, body`—uncomment and adjust as needed.
- Glassmorphism intensity: Tune these in `style.css`:
  - `.calculator { background-color: rgba(255,255,255,.1); }`
  - `.calculator { backdrop-filter: blur(2px); }`
  - Inner shadows: `box-shadow: inset 0px 0px 5px white;`
- Grid/buttons: Modify `.button` grid settings or `button` sizing to change spacing and proportions.

## Accessibility notes
- The current input is visually styled and disabled for demo purposes. If you add functionality, ensure keyboard navigation, color contrast, and ARIA roles/labels where appropriate.
- Consider providing a non‑video background or a pause control for motion‑sensitive users if you add interactivity.

## Browser support
- Modern evergreen browsers are recommended.
- `backdrop-filter` may not be supported in older browsers; consider a more opaque background color as a graceful fallback.

## Deployment
- GitHub Pages: Push this repository and enable Pages for the `main` branch (root). Access it at your GitHub Pages URL.
- Any static host (e.g., Netlify, Vercel, Surge): Deploy the project root as a static site.

## Roadmap ideas
- Wire up JavaScript for full calculator functionality (keyboard input, operations, clear, etc.).
- Add dark/light theme toggle and motion‑reduced variant.
- Provide unit tests for calculation logic once added.

## Credits
- Background media: Replace with your own and credit the source if required by its license.

## License
No license has been chosen yet. If you plan to share or accept contributions, consider adding a license (e.g., MIT) via a `LICENSE` file.
