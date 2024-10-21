+++
[build]
  list = "never"
  publishResources = false
  render = "never"

[cascade]
  outputs = ["calendar"]
+++

This is a workaround approach to rendering a calendar output type for each year.

Instead of using config and/or front matter, we use a separate _years_ content
section to render the calendar output type for each year.

It would be great to find a way to do this without an otherwise unnecessary
content section.
