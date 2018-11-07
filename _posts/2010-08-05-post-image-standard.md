---
layout: post
title: "Post: Image (Standard)"
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

The preferred way of using images is placing them in the `/images/` directory and referencing them with an absolute path. Prepending the filename with `{% raw %}{% endraw %}` will make sure your images display properly in feeds and such.

Standard image with no width modifier classes applied.

**HTML:**

```html
{% raw %}<img src="https://raw.githubusercontent.com/daoyking/daoyking.github.io/master/images/filename.jpg" alt="">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt](https://raw.githubusercontent.com/daoyking/daoyking.github.io/master/images/filename.jpg){% endraw %}
```

![Unsplash image 9](https://raw.githubusercontent.com/daoyking/daoyking.github.io/master/images/unsplash-image-9.jpg)
