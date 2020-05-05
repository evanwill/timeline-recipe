---
title: About
layout: page
---

# About timeline-recipe

A Jekyll template to create standalone [TimelineJS](https://timeline.knightlab.com/) on GitHub Pages.

To add a timeline to a page:

First, add base info to the page yml front matter:

```
timeline: demo-test # matches CSV file in _data
timeline-title: Demo Timeline Title
timeline-description: optional
timeline-featured-image: option link to image
timeline-featured-image-credit: optional credit for image
```

Add the timeline events as a CSV in `_data` directory.
Use fields:
`id,year,month,day,title,text,media_filename,media_type,media_credit`

- `media_filename` = a filename of jpg, png, pdf, mp3 included in the `objects` folder, *or* a YouTube ID. 
- Supported `media_type` values = image, pdf, audio, youtube.
- `year` is required, others are optional.
