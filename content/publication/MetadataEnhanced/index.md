+++
title = "Metadata-enhanced contrastive learning from retinal optical coherence tomography images"
date = 2024-10-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["R Holland", "O Leingang", "H Bogunović", "S Riedl", "L Fritsche", "T Prevost", "HPN Scholl", "U Schmidt-Erfurth", "S Sivaprasad", "AJ Lotery", "D Rueckert", "MJ Menten"]

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
publication = "In *Medical Image Analysis*"
publication_short = ""

# Abstract.
abstract = "Deep learning has potential to automate screening, monitoring and grading of disease in medical images. Pretraining with contrastive learning enables models to extract robust and generalisable features from natural image datasets, facilitating label-efficient downstream image analysis. However, the direct application of conventional contrastive methods to medical datasets introduces two domain-specific issues. Firstly, several image transformations which have been shown to be crucial for effective contrastive learning do not translate from the natural image to the medical image domain. Secondly, the assumption made by conventional methods, that any two images are dissimilar, is systematically misleading in medical datasets depicting the same anatomy and disease. This is exacerbated in longitudinal image datasets that repeatedly image the same patient cohort to monitor their disease progression over time. In this paper we tackle these issues by extending conventional contrastive frameworks with a novel metadata-enhanced strategy. Our approach employs widely available patient metadata to approximate the true set of inter-image contrastive relationships. To this end we employ records for patient identity, eye position (i.e. left or right) and time series information. In experiments using two large longitudinal datasets containing 170,427 retinal optical coherence tomography (OCT) images of 7912 patients with age-related macular degeneration (AMD), we evaluate the utility of using metadata to incorporate the temporal dynamics of disease progression into pretraining. Our metadata-enhanced approach outperforms both standard contrastive methods and a retinal image foundation model in five out of six image-level downstream tasks related to AMD. We find benefits in both a low-data and high-data regime across tasks ranging from AMD stage and type classification to prediction of visual acuity. Due to its modularity, our method can be quickly and cost-effectively tested to establish the potential benefits of including available metadata in contrastive pretraining."

# Summary. An optional shortened abstract.
summary = "*Medical Image Analysis, 2024*"

# Digital Object Identifier (DOI)
doi = "10.1016/j.media.2024.103296"

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "/files/MetadataEnhanced.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
&nbsp;