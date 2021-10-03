+++
title = "Is prediction of species richness from stacked species distribution models biased by habitat saturation?"
date = 2020-04-01T18:14:56+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Matthias Grenié**", "Cyrille Violle", "François Munoz"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Ecological Indicators"
publication_short = "Ecol. Ind."

# Abstract and optional shortened version.
abstract = """
Several studies have proposed to predict Species Richness (SR) by combining the predictions of independent Species Distributions Models (SDMs) (the predict first-assemble later strategy). Alternative methods propose to combine outputs from SDMs differently, by either summing predicted presence probabilities at each location, or summing binary presence predictions after thresholding the probabilities. Species can occupy various proportions of their suitable habitats (i.e, have various levels of habitat saturation), which can cause discrepancy when predicting their presences through SDMs. Furthermore, these discrepancies can be increased when combining the predictions of individual SDMs to predict SR. In this article, we performed simulations of species distributions with varying habitat saturation (i.e., the amount of suitable habitat occupied by a species), and we compared observed richness with that predicted by the alternative approaches. We found that probability-based richness is not biased by the level of habitat saturation, while threshold-based richness over-predicts richness at low habitat saturation and under-predicts it as high habitat saturation. Probability-based richness should thus be used in priority when predicting species richness locally. Nonetheless, threshold-based richness represents species richness constrained by environmental filtering only and thus is a useful indicator of potential species richness when species fully saturate their habitats. Thus the systematic comparison of probability-based and threshold-based richness predictions can reveal the importance of habitat saturation and can thus help identify community assembly mechanisms at play.
"""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning.md"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = [""]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["habitat saturation", "Species Richness", "Stacked species distribution models (SSDMs)", "Predicted presence probabilities", "Threshold-based prediction"]

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S1470160X19309653"
url_preprint = ""
url_code = "https://doi.org/10.5281/zenodo.3552836"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "DOI: 10.1016/j.ecolind.2019.105970", url  = "https://doi.org/10.1016/j.ecolind.2019.105970"},
              {name = "GitHub", url = "https://github.com/Rekyt/ssdms_saturation_richness/"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

[header]
image = "simulation_routine.png"
caption = "Summary figure showing the simulation routine"
+++
