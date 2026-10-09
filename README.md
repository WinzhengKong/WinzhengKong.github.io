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
- Eight papers with full method-framework figures
- Education and awards

The page is static and has no build dependencies. Update profile content in `index.html`,
visual styling in `stylesheet.css`, and the portrait in `images/profile-photo.png`.

## Visitor counter

The footer displays the site-level visitor count provided by
[Busuanzi](https://ibruce.info/2015/04/04/busuanzi/). It loads only on
`https://winzhengkong.github.io`, not in local previews. If the production domain
changes, update the hostname check in `index.html`.

This is the provider's cumulative visitor metric, not the number of people
currently online or an exact count of distinct individuals. Visitors' browsers
send requests to the third-party service; its availability and counting rules
determine the displayed number. The counter stays hidden if no result is returned.
