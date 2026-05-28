# Joshua Yeadon Portfolio

Simple GitHub Pages portfolio using Jekyll. The homepage is the main portfolio: projects are shown as scrollable boards with expandable detail.

## Edit Your Details

Open `_config.yml` and replace:

- `hello@example.com`
- the LinkedIn URL

Do not put private CV details like address or phone number in the public site.

## Edit A Portfolio Project

Project source files live in `_projects`.

Each project has front matter like:

```md
---
title: Project title
category: Mechanical design
order: 1
hero: /assets/images/project-hero.jpg
thumbnail: /assets/images/project-thumb.jpg
hero_alt: Short description of the hero image.
summary: Two concise technical sentences.
facts:
  - CAD
  - Prototyping
  - Testing
---
```

Below the front matter, write the expandable detail. Keep it short and put images between text sections:

```md
## Context

One or two useful sentences.

<figure>
  <img src="/assets/images/project-details/my-image.jpg" alt="Describe the image">
  <figcaption>One useful sentence about what the image shows.</figcaption>
</figure>
```

The project will appear on the homepage automatically.

## Add A Blog Post

Blog posts live in `_posts`.

Duplicate one of the examples and rename it:

```text
YYYY-MM-DD-short-title.md
```

Use this front matter:

```md
---
title: My Blog Post
excerpt: One short sentence.
image: /assets/images/project-details/example.jpg
image_alt: Short description of the image.
---
```

Then write in Markdown. The newest four posts appear in the 2x2 blog grid.

## Add Images

Put project images in:

```text
assets/images/project-details
```

Use clear filenames like:

```text
gearbox-bearing-layout.jpg
openipc-internal-packaging.jpg
```

## Publish On GitHub Pages

1. Create a professional GitHub account.
2. Create a repository named `yourusername.github.io`.
3. Upload these files to the repository.
4. In GitHub repository settings, confirm Pages publishes from the main branch.

Your site will publish at:

```text
https://yourusername.github.io
```
