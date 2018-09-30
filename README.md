# My Jekyll Boilerplate

A boilerplate with the setup I prefer when starting a new [Jekyll](https://jekyllrb.com/) site.

Includes jQuery 3.3.1, Bootstrap 4, Google/Typekit webfont loader, Font Awesome 5 svg/js.

## Site variables of note
**In _config.yml**

`theme-color: ` Use this to set a color in your head metadata for favicons and theme.

`ga-id: ` Place your Google analytics ID here.


## Page variables of note

`share-image: ` is the location of an image that will be used when the url of the page is shared on Facebook or Twitter. Location is already set to img folder in assets, simply write the subpath from there. Example:

```
---
title: My Title
description: My Description
share-image: sample.jpg
---
```

## Includes of note


#### video.html

Use `{% include youtube-video.html ratio="16by9" id="Sjx9oSJDAVQ" %}` for responsive YouTube video embeds.

Use `{% include vimeo-video.html ratio="4by3" id="6759134" %}` for responsive Vimeo video embeds.

`ratio` is the aspect ratio of your video. Can be "1by1", "4by3", "16by9", or "21by9". `id` is the id associated with the video in the video's url.