---
layout: page
title: "Test Page"
description: "The page of testing"
---
{% include JB/setup %}

Hello world! This is a test page, created using `rake page name="pages/test.md"` in the **working directory** of the site.

Pages can be created in a few ways, namely:

- `rake page name="name"` -- Creates a page named "name.md" in the root of the site (accessed via **http://site.com/name**).
- `rake page name="pages/name.md"` -- Creates a page named "name.md" in the "pages" directory (accessed via **http://site.com/pages/name.html**).
- `rake page name="pages/name"` -- Creates a directory called "name" in the "pages" directory, with a file named "index.html", which is where content goes (**USES HTML, NOT MARKDOWN**) (accessed via **http://site.com/pages/name/**).
