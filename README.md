# torresmarcos.com

My personal website: [torresmarcos.com](https://torresmarcos.com).

## Structure

Plain HTML, one file per page:

- `index.html`: home page with a short about me
- `uses.html`: what I use
- `projects.html`: my projects
- `style.css`: the look of every page (colours, fonts, layout)
- `favicon.svg`: the icon in the browser tab
- `fonts/`: IBM Plex Mono, served from this repo so no third party is contacted

## View it locally

Open any of the HTML files in a browser by double-clicking it. The styles load, but links such as `/uses` only work on the published site.

## Add a project

Copy an existing project block in `projects.html` (from `<article class="project">` to `</article>`) and fill it in: what it is, the tags, why, built with, what I learned and a link to the code.

## License

The code is released under the [MIT License](LICENSE). The content (texts and images) is © Marcos Torres Álvarez, all rights reserved. The IBM Plex Mono font is under the [SIL Open Font License](fonts/IBM-Plex-Mono-LICENSE.txt).

## Milestones

- 2026-10-25: Chose the domain torresmarcos.com: it was available, it's timeless and it's a .com.
- 2026-10-25: Compared Porkbun and Cloudflare and chose Cloudflare for the customisation and control of its dashboard, even though it requires using its DNS.
- 2026-10-25: Created the repo.
- 2026-10-25: Weighed Astro against plain HTML and chose HTML: simple for now and easy to migrate.
- 2026-10-25: Chose GitHub Pages: it's free and the site is lightweight.
- 2026-10-25: Learned how to set up a custom domain on GitHub Pages.
- 2026-10-25: Learned the DNS record types (A and CNAME) and set them up in Cloudflare.
- 2026-10-25: Set the records to DNS only (grey cloud), so visits go straight to GitHub without passing through Cloudflare.
- 2026-10-25: Enabled Enforce HTTPS.
- 2026-10-25: Decided to write the text before the visual identity, because the look depends on the content.
- 2026-10-25: Decided to work with branches and pull requests.
- 2026-10-25: Wrote a short about me.
- 2026-10-25: Added the Uses page.
- 2026-10-25: Added the Projects page.
- 2026-10-25: Chose the licences: MIT for the code, all rights reserved for the content.
- 2026-10-25: Added the design: dark by default with a light version, IBM Plex Mono served from the repo, a top menu, a favicon and a © line in the footer.

## To do

- Consider GitHub Actions.
- Decide whether search engines should index the site.
- Link MART Formula Student and the University of Málaga on the home page.
