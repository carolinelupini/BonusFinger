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
The signup form is currently a **styled placeholder** and does not collect emails yet.
To make it live: create a subscribe form in Beehiiv and paste its embed snippet where the
`<!-- BEEHIIV EMBED GOES HERE -->` comment is in `index.html`.

## Deploy / update
This repo IS the website. Any change pushed to the `main` branch goes live at bonusfinger.com
within a minute or two. See the setup walkthrough for first-time deployment.

## Local preview
From this folder: `python3 -m http.server 8099` then open http://localhost:8099
