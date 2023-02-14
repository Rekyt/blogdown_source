+++
title = "fundiversity: a modular R package to compute functional diversity indices"
date = 2022-12-29T17:31:40+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Matthias Grenié**", "Hugo Gruson"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Ecography"
publication_short = "Ecography"

# Abstract and optional shortened version.
abstract = """

1. Functional diversity is widely used and widespread. However, the main package used to compute functional diversity indices FD is not flexible and not adapted to the volume of data used in modern ecological analyses.

2. We here present fundiversity, an R package that eases the computation of classical functional diversity indices. It leverages parallelization and memoization (caching results in memory) to maximize efficiency with data with thousands of columns and rows.

3. In addition to being more flexible we did a performance comparison with packages that provide analog functions. fundiversity was always an order of magnitude quicker than alternative packages.

4. fundiversity aims to be a lightweight efficient tool to compute functional diversity indices, that can be used in a variety of contexts. Because it has been designed following clear principles, it is easy to extend. We hope the wider community will adopt it and we welcome all contributions.
"""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["functional-diversity", "tools-for-biodiversity-science"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://doi.org/10.1111/ecog.06585"
url_preprint = "https://doi.org/10.32942/osf.io/dg7hw/"
url_code = "https://github.com/funecology/fundiversity"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [
  {name = "Package on GitHub", url = "https://github.com/funecology/fundiversity"},
  {name = "Package on CRAN", url = "https://cran.r-project.org/package=fundiversity"}
]

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

doi = "10.1111/ecog.06585"

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""
+++
