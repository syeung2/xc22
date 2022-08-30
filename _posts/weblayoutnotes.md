---
toc: true
layout: post
description: temporary post to figure out web page layout
categories: [markdown]
title: Web Page Layout
---

### Web Page Layout
A complete HTML Web Application is typically made off of a Layout and a series of Fragments (sometimes called templates).  
- [Web Page Layout](https://padlet.com/jmortensen7/weblayout).  This illustration becomes important when you make your own layout and fragments using frameworks like Jinja2 (for Python)  or Thymeleaf (for Java).
- The design of GitHub pages allows us to change themes with the _config.yml file (theme: minima) key/value, change the value to a [supported theme](https://pages.github.com/themes/) and page should work, but will look different.
- [Minima theme](https://github.com/jekyll/minima/blob/master/_layouts/default.html), click on link for accurate syntax.  Everywhere you see an "include" this layout is including a fragment to complement the page, things like CSS, JavaScript, headers and footers are included into the layout.  Where you see "content", this is the statement that includes page specific fragments we have designed added within the layout.  You should associate all of this to "Procedural Abstraction".

```html
    <!DOCTYPE html>
    <html lang="{{ page.lang | default: site.lang | default: "en" }}">

    "include head.html"

    <body>

        "include header.html"

        <main class="page-content" aria-label="Content">
        <div class="wrapper">
            "content"
        </div>
        </main>

        "include footer.html"

    </body>

    </html>
```