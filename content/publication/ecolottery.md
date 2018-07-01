+++

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["François Munoz", "Matthias Grenié", "Pierre Denelle",
           "Adrien Taudière", "Fabien Laroche", "Caroline Tucker",
           "Cyrille Violle"]

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
publication = "Methods in Ecology and Evolution"
publication_short = ""


title = "ecolottery: Simulating and assessing community assembly with environmental filtering and neutral dynamics in R"

# Abstract and optional shortened version.
abstract = "1. We introduce the R package ecolottery dedicated to quick and efficient simulation of communities undergoing local neutral dynamics with environmentally filtered immigration from a reference species pool (spatially implicit model). The package includes an Approximate Bayesian Computation (ABC) tool to estimate the parameters of these processes. We present the rationale of the approach and show examples of simulations and ABC analysis. 2. The species in the reference pool differ in their abundances and trait values. Environmental filtering weights the probability of immigration success depending on trait values, while the descendants of established immigrants undergo neutral stochastic drift. The reference pool can be defined in a flexible way as representing, e.g. the composition of a broad biogeographical region, or available dispersers around local communities. The package provides a process-based alternative to the use of randomization-based null models. 3. The package proposes a coalescent-based simulation algorithm that presents significant advantages over alternative algorithms. It does not require simulating community dynamics from an initial state forward in time but does still allow measurement of the influence of environmental filtering. Because of its high calculation speed, this approach allows simulating many communities within a reasonable amount of time. 4. Diverse patterns of taxonomic, functional and phylogenetic compositions can be generated. The package can be used to explore the outcome of ecological and evolutionary processes playing at local and regional scales, and to estimate the parameters of these processes based on observed patterns."
abstract_short = "...."

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional)
url_pdf = "https://www.researchgate.net/profile/Francois_Munoz/publication/318635375_ecolottery_Simulating_and_assessing_community_assembly_with_environmental_filtering_and_neutral_dynamics_in_R/links/5a12b2d3a6fdccc2d79b8617/ecolottery-Simulating-and-assessing-community-assembly-with-environmental-filtering-and-neutral-dynamics-in-R.pdf"
url_preprint = ""
url_code = "https://github.com/frmunoz/ecolottery"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "CRAN", url = "http://cran.r-project.org/package=ecolottery"},
              {name = "DOI: 10.1111/2041-210X.12918", url = "https://doi.org/10.1111/2041-210X.12918"}]

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
