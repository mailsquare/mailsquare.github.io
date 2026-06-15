# MailSquare Static Site

This workspace is a plain static site. The deployable site lives entirely in `dist/`.

## Edit Here

Update these files directly:

- `dist/index.html` for document metadata, favicon links, and script/style tags
- `dist/site.json` for site name, logo path, hero copy, contact copy, and social links
- `dist/projects.json` for portfolio items
- `dist/testimonials.json` for testimonials
- `dist/assets/index-KuCZI7oZ.js` for built client-side behavior
- `dist/assets/index-D6j6s8Zw.css` for built styles
- `dist/images/` for logos and project images

## Deploy

Deploy the contents of `dist/` as a static site. No build step is required in this workspace.

## Content Notes

`dist/site.json`

- `name` controls the text label shown in the header and footer
- `logo` should point to an image inside `dist/`, for example `./images/cartflow_icon_1.png`
- `contact.formspreeId` controls the Formspree endpoint used by the contact form

`dist/projects.json`

- Array order controls display order
- `type: "design"` items can use `gallery` images for the lightbox

`dist/testimonials.json`

- Array order controls carousel order

## Current Branding

The header uses `dist/images/cartflow_icon_1.png` and renders the `CartFlow` name next to it.
# mailsquare.github.io
