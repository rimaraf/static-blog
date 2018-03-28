# Static Jekyll based blog

I've stitched together a no nonsense static webpage for blogging. The site is based on Jekyll and easy (and free) to host on GitHub Pages.

<img src="screenshot.png" width="500">

<figure>
  <img src="promp_blink.gif" width="200">
  <figcaption>The cursor symbol next to the blog title is blinking like a prompt - just for fun.</figcaption>
</figure>

It also adapts to smaller screens. Here on a 4.7" iPhone:

<img src="ios_screenshot.png" height="400">  <img src="ios_screen_post.png" height="400">

Remenber to change the baseurl in the config.yml file and to insert your blog title in the default.html file.

### Setup

1. Fork this repo

2. Make a branch called ```gh-pages```

3. Go to Settings. Change the Source under GitHub Pages to gh-pages - and it's live. The link for your blog will show above the Source-setting.

### How to publish new posts on the blog

1. Write your post in markdown

2. Place this:
```md
---
title: "Post title"
meta: "Text used as the posts subdivision on front page"
layout: default
---
```

in the very top of the document

3. Save your post as a md-file with this naming convention:
```md
yyyy-md-dd-post-title-seperated-by-minuses.md
```

4. Put the file in the posts folder - and it's live!
