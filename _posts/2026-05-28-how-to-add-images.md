---
title: How to add images to a post
excerpt: A small example showing the Markdown and HTML pattern for adding project images.
image: /assets/images/project-details/openipc-case.jpg
image_alt: Transparent CAD view of an electronics enclosure.
---

Put images in `assets/images` or `assets/images/project-details`.

Then add them like this:

```html
<figure>
  <img src="/assets/images/project-details/example.jpg" alt="Describe the image">
  <figcaption>One useful sentence about what the image shows.</figcaption>
</figure>
```

Use the caption to point at the engineering decision, not to repeat the title.
