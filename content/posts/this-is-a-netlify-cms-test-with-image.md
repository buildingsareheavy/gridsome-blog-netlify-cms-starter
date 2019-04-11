---
title: This is a Netlify CMS Test with a Cover Image
date: 2019-03-30T21:38:54.816Z
description: "I am testing from the admin side of Netlify CMS."
cover_image: /content/posts/images/test.png
---

Here are some important things to keep in mind.

The description shows up in the post preview, like in the homepage, but not in the single post page (this current page). So if you want it to reflect, you will copy and paste the text into both the _description_ and the _body_, or don't.

If you inspect the image below, you'll realize it's displayed as a normal `<img>` and not as a `<g-image>` like the other posts. It's also in the directory that NetlifyCMS will upload images, not in the directory where the posts are stored. It's processed as a normal `<img >` because `<g-image>` is only activated with relative paths, and Netlify CMS automatically adds a slash at the beginning of all the paths. There is currently no way to add it directly as a `<g-link>`.

![](/content/posts/images/alexandr-podvalny-220262-unsplash.jpg)

Here is text below the image...
