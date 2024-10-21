+++
title = 'Posts'
date = 2023-01-01T08:30:00-07:00
draft = false
outputs = ["json", "calendar"]

[cascade]
  outputs = ["html"]
+++

This section represents my third approach. This time, I try moving the
"calendar" output type to the section root, naively hoping that it would trickle
down to the year folders. This does not work.

Instead, this approach renders both the "json" and "calendar" output types in
the section root, but the calendar.json files in each year folder are missing.
