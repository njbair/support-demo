+++
title = 'Posts'
date = 2023-01-01T08:30:00-07:00
draft = false
outputs = ["json"]

[cascade]
  outputs = ["html", "calendar"]
+++

This section represents my second approach. In this section, there are no
_index.md files in the year folders, and I attempt to specify outputs via the
[cascade] parameter. I need to include the "html" output type in the cascade,
otherwise the year folders would inherit only the "json" output type from the
section root.

This approach correctly renders the section root index.json file, but the
calendar.json files in each year folder are missing.
