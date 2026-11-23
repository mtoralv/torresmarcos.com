# torresmarcos.com

My personal website: [torresmarcos.com](https://torresmarcos.com).

## Structure

Plain HTML, one file per page:

- `index.html`: home page with a short about me
- `uses.html`: what I use
- `projects.html`: the list of my projects
- `cv.html`: links to my CV
- `cv/`: the CV as PDF, in English and Spanish
- `projects/`: one page per project (for example `projects/torresmarcos.html`, served at `/projects/torresmarcos`)
- `style.css`: the look of every page (colours, fonts, layout)
- `favicon.svg`: the icon in the browser tab
- `fonts/`: IBM Plex Mono, served from this repo so no third party is contacted
- `robots.txt`: tells search engines they may crawl the whole site and where the sitemap is
- `sitemap.xml`: the list of public pages, for search engines

## View it locally

Open any of the HTML files in a browser by double-clicking it. The styles load, but links such as `/uses` only work on the published site.

## Add a project

1. Copy `projects/torresmarcos.html` to `projects/<name>.html` and fill it in: title, summary, year, tags, code link, why and what I learned. Keep `../` in front of `style.css` and `favicon.svg`, and set the `canonical` link to `https://torresmarcos.com/projects/<name>`.
2. Copy a row in `projects.html` (from `<li class="project-row">` to its closing `</li>`), put it at the top of the list and point its link to `/projects/<name>`.
3. Add `https://torresmarcos.com/projects/<name>` to `sitemap.xml`.

## Update the CV

The PDFs in `cv/` are built from a LaTeX source that is kept outside this repo. To update them, rebuild both PDFs and replace the files in `cv/`, keeping the same names so the links keep working.

## License

The code is released under the [MIT License](LICENSE). The content (texts and images) is © Marcos Torres Álvarez, all rights reserved. The IBM Plex Mono font is under the [SIL Open Font License](fonts/IBM-Plex-Mono-LICENSE.txt).

## To do

- Consider GitHub Actions.
