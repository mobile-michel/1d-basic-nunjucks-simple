# Basic template with Eleventy, Liquid & Simple CSS framework

## Folder structure

- pages in /src
- layouts in /_layouts
- includes in /_includes
- Json files in /_data
- CSS files in /assets/css
- images in /assets/images

## Page layout

- _layouts/base.liquid
- _includes/header.liquid
- _includes/footer.liquid

## Responsive navbar

- responsive mobile menu with CSS without JavaScript from [LogRocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/), without classes
- add tags: primary in frontmatter

## Package.json scripts

- "start": "npx @11ty/eleventy --serve",
- "build": "eleventy",
- "debug": "DEBUG=* eleventy"

## Dependencies

- "@11ty/eleventy": "^2.0.1"