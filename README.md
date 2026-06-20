# Bonus Finger 🍴

A one-page landing site for **Bonus Finger** — the spatula for sauce too good to leave behind.
Static HTML/CSS, no build step, hosted on GitHub Pages at **bonusfinger.com**.

## Files
| File | What it is |
|------|-----------|
| `index.html` | The whole page |
| `styles.css` | All styling |
| `assets/favicon.svg` | Browser-tab icon |
| `assets/og-image.png` | Social-share preview image *(to add)* |
| `CNAME` | Tells GitHub Pages to serve the custom domain `bonusfinger.com` |

## Editing
It's plain HTML/CSS — open `index.html`, change the text, save. No tools needed.

## Email signup
Live — handled by the **Bonus Finger** Beehiiv publication (`bonusfinger.beehiiv.com`). An inline
subscribe form is embedded in the signup section of `index.html` via Beehiiv's loader script
(form ID `e112e1c8-0b8e-485a-9088-70340844cd32`). Signups land in that publication.

## Deploy / update
This repo IS the website. Any change pushed to the `main` branch goes live at bonusfinger.com
within a minute or two. See the setup walkthrough for first-time deployment.

## Local preview
From this folder: `python3 -m http.server 8099` then open http://localhost:8099

## Design explorations
The spatula illustration went through several rounds. The option mockups are kept as
`preview-spatula-options-*.html` in this folder (gitignored — local only, not published).
`preview-spatula-options-7.html` holds the four finalists; the live site uses **Option 1**
(straight spine, soft durable point).

## Product notes — if we ever actually make this
- **Make left-handed and right-handed versions.** The chosen design is asymmetric — a straight
  spine on one edge with the blade angled off the other — so the comfortable, natural grip favors
  one hand. A mirrored version would serve the opposite hand.
