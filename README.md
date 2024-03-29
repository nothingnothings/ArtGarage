![ArtGarage](/images/ArtGarage.png)

# ArtGarage

Frontend App built with vanilla HTML, CSS and Javascript. Flexbox and media queries were used for the responsive design (attempting to cater to multiple device types, both desktop and mobile, with different resolutions). The webApp can be accessed [here](https://nothingnothings.github.io/ArtGarage/).

The Webpack version of this app can be found [here](https://github.com/nothingnothings/ArtGarageWebpackVersion).

![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/nothingnothings/ArtGarage/master?style=flat-square)
[![HitCount](https://hits.dwyl.com/nothingnothings/ArtGarage.svg?style=flat-square)](http://hits.dwyl.com/nothingnothings/ArtGarage)


## Technologies

Some of the Languages and Libraries employed:

- HTML5
- CSS3 (besides animations, mainly Flexbox and common styles, with media queries for adjustments)
- Vanilla JavaScript (no JavasScript frameworks; usage of `var`, normal functions and common eventListeners)

## Project Directory Structure

```
.\
│
├── images\
│   ├── ArtGarage.png
│   ├── about1.jpg
│   ├── about2.jpg
│   ├── favicon.ico
│   ├── products1.jpg
│   ├── products2.jpg
│   └── products3.jpg
│
├── scripts\
│   └── index.js
│
├── README.md
├── index.html
└── style.css

```

## Setup

To use this project, clone it using Git:

1. Run `git clone` to clone the project into your local Git repository
2. Serve the files with the help of a hosting provider (frontend-only)

## Features

- SPA (Single-Page Application)-inspired webApp
- Responsive design (mobile and desktop) created with Flexbox and media queries
- Addition/removal of CSS classes ("slide-in" animation) implemented with JavaScript
- Usage of GitHub Actions to, upon the git push command, transfer the contents of the master branch into the gh-pages branch, which then deploys it at https://nothingnothings.github.io/ArtGarage/.
- Custom favicon, compatible with multiple devices 

## Inspiration

This app was based on the "CSS Flexbox" course provided by Origamid.
