# Website template

A simple, dark-themed multi-page website template for article projects.
Plain HTML and CSS, no build tools or frameworks.

## Features

- Shared header and styles across all pages (`css/base.css`)
- Home page with an article list
- Article pages with their own Sources and About Us pages
- Responsive layout for desktop and mobile
- Contact page with a `mailto:` button

## Getting started

1. Download or clone this repository.
2. Open `index.html` in your browser.
3. Edit the placeholder text and images with your own content.

## Project structure

```
├── index.html          Home page with the article list
├── contact.html        Contact page
├── HomePage/           Main Sources and About Us pages
├── article01/          Example article with its Sources and About Us
├── article02/          Second example article
├── css/
│   ├── base.css        Shared: body, header, navigation, logo
│   └── ...             One stylesheet per page type
└── images/             Logo and placeholder images
```

## Adding a new article

1. Copy the `article02/` folder and rename it (for example `article03/`).
2. Rename the HTML files inside to match.
3. Replace the placeholder text, and add your video or audio file.
4. Add an entry for it in `index.html`.

## Customizing

- **Colors and fonts:** edit `css/base.css`.
- **Logo:** replace `images/Logo.png`.
- **Contact email:** change `example@example.com` in `contact.html`.
- **Video:** `article01/article01.html` expects a `Video.mp4` in its folder.

## Hosting

Works on GitHub Pages: go to Settings → Pages, choose the `main` branch
and the root folder, and save. All paths are relative, so it works under
any repository name.


> **Note:** This template is based on a simple website I built with self-taught skills,
> so the code isn't perfect. I plan to keep improving this repository over time,
> especially the CSS.