# email-assets

Public images used in devs. outreach emails. Email clients (Gmail, Outlook) only show images from a public HTTPS URL, so they are served from here through jsDelivr:

- `logiops-logo.png` (128 x 128, shown at 32 x 32): `https://cdn.jsdelivr.net/gh/devs-islayer/email-assets@v1/logiops-logo.png`

To change an image, commit the new file, tag it `v2`, and point the email at `@v2`. A tagged URL never changes, so old emails keep showing the image they were sent with.
