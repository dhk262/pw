# David Kang — Personal Website

This repository contains the source for my personal academic website, built with the R Markdown website framework and deployed via GitHub Pages.

**Live site:** https://dhk262.github.io/pw/

## Built with
- R Markdown website framework (`rmarkdown::render_site()`)
- Custom CSS (`styles.css`) for typography, color palette, hero layout, info cards, and project cards
- Font Awesome 6 for navbar icons (GitHub, LinkedIn, email)
- Bootstrap "cosmo" theme as a base, heavily customized

## Pages
- **Home** (`index.Rmd`) — professional introduction with photo and quick info cards
- **CV** (`cv.Rmd`) — embedded PDF of my CV
- **Projects** (`projects.Rmd`) — two graduate-level projects from my Rollins capstone

## To build locally
```r
rmarkdown::render_site()
```
Output is written to the `docs/` directory, which GitHub Pages serves.
