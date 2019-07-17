+++
title = "landscapemetrics: an open-source R tool to calculate landscape metrics"
date = 2019-07-27

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Maxmilian H.K. Hesselbarth",
            "Marco Sciaini",
            "Kimberly A. With",
            "Kerstin Wiegand", 
            "Jakub Nowosad"]

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
publication = "*Ecography*"
publication_short = "*Ecography*"

# Abstract and optional shortened version.
abstract = "Quantifying landscape characteristics and linking them to ecological processes is one of the central goals of landscape ecology. Landscape metrics are a widely used tool for the analysis of patch-based, discrete land-cover classes. Existing software to calculate landscape metrics has several constraints, such as being limited to a single platform, not being open-source, or involving a complicated integration into large workflows. We present landscapemetrics, an open-source R package that overcomes many constraints of existing landscape metric software. The package includes an extensive collection of commonly used landscape metrics in a tidy workflow. To facilitate the integration into large workflows, landscapemetrics is based on a well-established spatial framework in R. This allows pre-processing of land-cover maps or further statistical analysis without importing and exporting the data from and to different software environments. Additionally, the package provides many utility functions to visualize, extract, and sample landscape metrics. Lastly, we provide building-blocks to motivate the development and integration of new metrics in the future. We demonstrate the usage and advantages of landscapemetrics by analysing the influence of different sampling schemes on the estimation of landscape metrics. In so doing, we demonstrate the many advantages of the package, especially its easy integration into large workflows. These new developments should help with the integration of landscape analysis in ecological research, given that ecologists are increasingly using R for the statistical analysis, modelling, and visualization of spatial data"

# Featured image thumbnail (optional)
image_preview = "Ecography.jpg"

# Is this a selected publication? (true/false)
# selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project in `content/project/`.
#   Otherwise, set `projects = []`.
projects = ["landscapemetrics.md"]

# Links (optional).
url_pdf = "https://onlinelibrary.wiley.com/doi/abs/10.1111/ecog.04617"
url_preprint = ""
url_code = "https://github.com/mhesselbarth/Hesselbarth_et_al_2019_Ecography"
url_dataset = ""
url_project = "https://r-spatialecology.github.io/landscapemetrics"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/point_pattern.jpg"
# caption = "My caption :smile:"

+++