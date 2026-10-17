# Yang Cui Homepage

This repository hosts the personal academic homepage for Yang Cui at
`cuiyang512.github.io`.

The homepage is a static GitHub Pages site built from `index.html`. It includes
CV-backed sections for:

- about
- news
- research interests
- journal publications
- field experience
- education
- awards and honors
- teaching
- contact and CV links

The current CV file is stored at `cv/Yang_s_CV_new.pdf`. When updating the
homepage, use the CV as the source of truth and avoid adding unsourced
information.

The homepage uses the local profile photo at `photo/photo_cropped.PNG` in the
profile area. If the image cannot load, the page falls back to initials.

The footer includes a total website view counter powered by
[`hits.sh`](https://hits.sh/). Because GitHub Pages serves this site statically,
the counter uses an external badge endpoint instead of local server-side state.

linkedIn: https://www.linkedin.com/in/yang-cui-414aa6321/
Researchgate: https://www.researchgate.net/profile/Yang-Cui-35?ev=hdr_xprf
Email: yang.cui512@gmail.com
university website: https://www.uu.se/en/contact-and-organisation/staff?query=N26-876


To preview locally, open `index.html` in a browser or run a simple static server:

```sh
python3 -m http.server 8000
```

## Homepage content and maintenance

The page highlights selected research using existing figures, lists public
research software, and groups preprints separately from published journal
articles. Older news remains available under **Earlier news**.

- Edit page content in `index.html` and styles in `assets/site.css`.
- Research figure sources are documented in `assets/README.md`.
- Each listed journal article/preprint has a portable citation in `bib/`.
  `bib/publications.bib` combines those citations without the CV template's
  sample entries or author-formatting commands. Keep individual citations and
  the combined download synchronized when updating a publication.
- `bib/ref.bib` remains the original CV bibliography.
- Paper and public repository links supplement the CV. Only link code when its
  connection to the publication is established.

The site remains static and requires no build step or JavaScript. Preview the
homepage by opening `index.html`, or use the static server command above.

The opening **Home** section showcases the existing portrait at
`photo/photo_cropped.PNG`, with the introduction and research links alongside
it on desktop and beneath it on smaller screens. Click the photo to view it
at full resolution.
