# LaMosca Tarot

The website for LaMosca Tarot. It is a single page with no build step.

| File | What it is |
|---|---|
| `public/index.html` | The whole site: text, styles and scripts |
| `public/portrait.jpg` | The photo in the "Behind the cards" section |
| `public/favicon.svg` | The icon shown in the browser tab |

## Hosting

Any static host works. Point it at the `public` folder and leave the build command empty.

## Changing the site

Edit `public/index.html` and push to `main`. A host connected to this repository redeploys
the live site on every push.

## Booking form

No form service is connected. Sending the form opens the visitor's own email app with
their request filled in and addressed to the contact email shown on the page.
