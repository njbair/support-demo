+++
title = 'Posts'
date = 2023-01-01T08:30:00-07:00
draft = false
outputs = ["json"]
+++

This section represents my first approach. The section root contains no HTML
output, and the posts are rendered as JSON. Each year folder contains its own
_index.md file, which specifies the "calendar" output type.

This approach correctly renders the calendar.json files in each year folder, but
the section root index.json file incorrectly contains entries for each year,
instead of the posts themselves.
