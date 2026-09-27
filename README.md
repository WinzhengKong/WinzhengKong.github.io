# Wenzheng Jiang — Academic Homepage

A lightweight academic homepage for Wenzheng Jiang, adapted from the layout and style of the
[`w-r-s/academic-homepage-template`](https://github.com/w-r-s/academic-homepage-template).

## Preview locally

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Then visit <http://127.0.0.1:8080>.

## Content

- Biography and research interests
- News and publication filters
- Seven published papers and two under-review manuscripts
- Education and awards
- Downloadable CV in `assets/Wenzheng_Jiang_CV.pdf`

The page is static and has no build dependencies. Update profile content in `index.html`
and visual styling in `stylesheet.css`. To add a portrait, replace
`images/profile-photo-placeholder.svg` with your image and update the corresponding
`src` in `index.html`.
