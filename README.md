# Badminton club website

A simple, no-build static site: just HTML and CSS, no JavaScript or tooling needed.

## Files

- `index.html`: all the content (sessions, news, membership, committee, contact)
- `style.css`: the look. Change the colours in the `:root` block at the top to rebrand.

## Editing

Open `index.html` in any text editor and replace the placeholder text (anything saying "Your Town", "Name Surname", `info@example.ie`, prices, etc.). Open the file in a browser to preview it; no server is required.

To add a news item, copy one `<li>` inside the `news` list and edit it.

## Putting it online (free)

**Netlify (easiest, no Git):** go to app.netlify.com/drop and drag the folder (or the zip's contents) onto the page. To update, drag the folder again.

**Cloudflare Pages:** Workers & Pages > Create > Pages > Upload assets, then upload the folder.

**GitHub Pages:** create a public repo, upload these files, then Settings > Pages > deploy from the `main` branch.

## Custom domain

Optional. Buy a domain from a registrar, then add it in your host's dashboard (Domains / Custom domains) and follow the DNS instructions. HTTPS is set up automatically.
