+++
# Projects widget.
widget = "projects"
active = true
date = "2016-04-20T00:00:00"

title = "Surveillance"
subtitle = "Examples of BuDA analysis in<br>macrofinancial surveillance"

# Order that this section will appear in.
weight = 30

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "surveillance"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.

[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "Article IV"
  tag = ".ArtIV"

[[filter]]
  name = "FSSA"
  tag = ".FSSA"

[[filter]]
  name = "Bilateral"
  tag = ".Bilateral"

[[filter]]
  name = "Multilateral"
  tag = ".Multilateral"

+++
