# Kim James Esguerra — Portfolio

A free, responsive, sci-fi styled portfolio built with HTML, CSS and Lightbox2.

## Included

- `index.html` — complete portfolio page
- `style.css` — black + `#3f2db3` sci-fi theme
- `images/kim-profile.jpg` — your uploaded profile photo
- `Kim-James-Esguerra-Resume.pdf` — your uploaded resume
- `Cover-Letter.txt` — your uploaded cover letter
- `images/` — project screenshot placeholders
- Lightbox2 screenshot galleries loaded from CDN

## Portfolio sections

- Home / introduction
- About
- Experience
- Skills & Technologies
- Projects with Lightbox2 screenshot galleries
- Resume and cover letter downloads
- Contact

## Customize your projects

Replace the placeholder screenshot files in `images/` with your real project screenshots.

Each project has three screenshot slots. You can add more images by copying another Lightbox2 link using the same `data-lightbox` group name.

## Customize contact information

The page currently uses the email and phone number from the uploaded resume.

## GitHub Pages

This is a static site and can be hosted for free on GitHub Pages.

Recommended repository name:

```text
yourusername.github.io
```

Then enable GitHub Pages in the repository settings.

## Important

For previous employer/client work, publish only material you have permission to showcase. Avoid uploading confidential source code, passwords, API keys, credentials or private client information.

The resume and cover letter are included exactly as provided by you.


## Stock development images

Four stock development/workspace images were added under `images/` and used as visual design elements and representative project imagery.

They are:
- `dev-workspace-1.jpg`
- `dev-workspace-2.jpg`
- `dev-workspace-3.jpg`
- `dev-workspace-4.jpg`

For client projects, replace these representative visuals with real website screenshots only when you have permission to publish the project images.


## 18 portfolio projects

The project section now includes all 18 sites from the Local screenshot, organized with category filters. Each project has one placeholder homepage image ready to be replaced with your full-page screenshot.


## Project Swiper

The Projects section now uses **SwiperJS**.

Features:
- 1 project per view on small screens
- 2 projects per view on tablets
- 3 projects per view on desktop
- Previous/next arrows
- Pagination bullets
- Keyboard navigation
- Swipe / drag interaction
- Autoplay that pauses when the mouse is over the carousel
- Existing Lightbox2 screenshot behavior remains intact

SwiperJS is loaded from jsDelivr:

```text
https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css
https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js
```


## Bootstrap responsive layout

The portfolio now uses Bootstrap 5 for its responsive navigation, containers, rows,
columns and mobile breakpoints, while the custom CSS keeps the black + #3f2db3
sci-fi visual theme.

Bootstrap is loaded from jsDelivr:
- bootstrap.min.css
- bootstrap.bundle.min.js

SwiperJS and Lightbox2 remain enabled.


## Effects and Flexbox

The portfolio now includes:
- Scroll reveal animations using IntersectionObserver
- Sci-fi cursor glow on desktop
- Project-card 3D tilt on desktop
- Project-card hover sweep/glow
- Button shine effect
- Timeline hover lift
- Hero ambient glow animation
- Flexbox-based component layouts for buttons, tags, metadata, document cards, contact details and visual strips
- Reduced-motion accessibility handling


## Effects troubleshooting

The effects are designed to work even when opening `index.html` directly.

Included effects:
- Scroll progress bar
- Scroll reveal
- Profile floating/orbit animation
- Hero text glow
- Project card glow and sweep
- Desktop cursor glow
- Project-card tilt
- Button shine
- Skill-card hover glow
- Timeline glow

JavaScript adds the `js-enabled` class at runtime so content remains visible
even if JavaScript is unavailable.
