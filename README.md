# Movie Reviews (GitHub Pages + Jekyll)

## 1) IMPORTANT: Set your repo name (baseurl)
Open `_config.yml` and set:

`baseurl: "/YOUR-REPO-NAME"`

Example: if your repo is `Christmas-Movies`, use:
`baseurl: "/Christmas-Movies"`

## 2) Replace the header image
Replace:
`assets/img/header-movies.png`
with your real header image (same file name).

## 3) Add posters
Upload posters into:
`assets/posters/`

Your filenames you told me are supported out of the box:
- 2025R1.jpeg
- 2025R2.jpg … 2025R8.jpg

## 4) Add a review (on GitHub.com)
Create a new file under `_reviews/2025/` or `_reviews/2024/`

Example:
`_reviews/2025/2025R9.md`

Template:
```yaml
---
title: "Movie Title"
year: 2025
rating: 4
poster: /assets/posters/2025R9.jpg
date: 2025-12-30
---

Your review text here.
```
