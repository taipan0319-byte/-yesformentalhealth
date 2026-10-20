# YesForMentalHealth.vote

Campaign website for **Citizens for a Healthy Community** — the Winnebago
County half-cent mental health sales tax (extended through June 30, 2031;
next referendum likely November 2030).

## How this site works

This is a plain, static website — no WordPress, no database, nothing to
patch or maintain. It is hosted free on **GitHub Pages** from this
repository: any change pushed to the `gh-pages` branch goes live at
https://yesformentalhealth.vote within a minute or two.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page (thank-you message, video, impact stats, CSS Framework) |
| `our-story.html` | About the Mental Health Board |
| `contact.html` | Contact info + R1 Planning Council disclaimer |
| `privacy.html` | Privacy, phone, and text message policy |
| `css/style.css` | All styling for every page (colors are defined at the top) |
| `images/` | All pictures |
| `CNAME` | Tells GitHub Pages the custom domain — do not delete |

## How to edit

Every page is readable HTML. To change a sentence, open the file, find the
sentence, change it, and commit. On GitHub.com you can do this entirely in
the browser: open the file, click the pencil icon, edit, and commit to
`gh-pages`.

## Handing this off

To transfer the site to a new maintainer: add them as a collaborator
(Settings → Collaborators) or transfer the repository to their account
(Settings → Danger Zone → Transfer ownership). The domain itself is
registered at GoDaddy and transfers separately.
