+++
title = "Matching Species Names Across Biodiversity Databases: Sources, tools, pitfalls and best practices for taxonomic harmonization"
date = 2021-10-02T18:18:32+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Matthias Grenié**", "Emilio Berti", "Juan D. Carvajal-Quintero",
"Marten Winter", "Alban Sagouis"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Biodiversity Information Science and Standards"
publication_short = "Biodiversity Information Science and Standards"

# Abstract and optional shortened version.
abstract = "\n The quantity and quality of ecological data have rapidly increased in the last decades, bringing ecology into the realm of big data. Frequently, multiple databases with different origins and data characteristics are combined to address new research questions. Taxonomic name harmonization, i.e., the process of standardizing taxon names according to common sources such as taxonomic databases (TD), is necessary to properly combine multiple databases using species names. In order to be able to develop proper data matching workflows, TDs and tools using them need to be clearly and comprehensively described. But this is rarely the case. Common problems users have to deal with are: poorly described taxonomic concepts behind biological databases, lack of information when TDs are actively updated, and details regarding where the primary source of taxonomic information comes from (e.g., secondary TDs taking information from primary TDs). In addition, software to access these TDs is not always advertised, partly redundant, or developed with incompatible standards, creating additional challenges for users. As a result, taxonomic name harmonization has become a major difficulty in ecological studies. Researchers face a jungle of primary and secondary TDs with a diversity of tools to access them and no clear workflow on how to practically proceed. As a consequence, it is hard for users to know which TD, tool and workflow will fit the task at hand and lead to the most robust results when combining different biological datasets.\n Here, we present an overview of major TDs as well as an extensive review of R packages to access TDs, and to harmonize taxa names. We developed an R Shiny web application summarizing meta-data and linkages among TDs and R packages (Figs 1, 2), which users can explore to learn about general features of TDs and tools and how they are linked among one another. This is particularly helpful to assist users when deciding on the TDs and tools that best fit the tasks and data at hand and to develop more informed workflows for taxonomic name harmonization. Finally, from our review and using the Shiny app, we were able to provide general best practice principles to harmonize taxonomic names and avoid common pitfalls."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["tools-for-biodiversity-science", "macroecology"]

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://biss.pensoft.net/article/75359"
url_preprint = ""
url_code = "https://github.com/Rekyt/taxo_harmonization/"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.3897/biss.5.75359"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Taxonomic harmonization is needed when merging any two datasets index by taxon names."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++