+++
title = "The impact of 2D cine MR imaging parameters on automated tumor and organ localization for MR-guided real-time adaptive radiotherapy"
date = 2018-11-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["MJ Menten", "MF Fast", "A Wetscherek", "CM Rank", "M Kachelrieß", "DJ Collins", "S Nill", "U Oelfke"]

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
publication = "In *Physics in Medicine & Biology*"
publication_short = ""

# Abstract.
abstract = "2D cine MR imaging may be utilized to monitor rapidly moving tumors and organs-at-risk for real-time adaptive radiotherapy. This study systematically investigates the impact of geometric imaging parameters on the ability of 2D cine MR imaging to guide template-matching-driven autocontouring of lung tumors and abdominal organs.<br/>Abdominal 4D MR images were acquired of six healthy volunteers and thoracic 4D MR images were obtained of eight lung cancer patients. At each breathing phase of the images, the left kidney and gallbladder or lung tumor, respectively, were outlined as volumes of interest. These images and contours were used to create artificial 2D cine MR images, while simultaneously serving as 3D ground truth. We explored the impact of five different imaging parameters (pixel size, slice thickness, imaging plane orientation, number and relative alignment of images as well as strategies to create training images). For each possible combination of imaging parameters, we generated artificial 2D cine MR images as training and test images. A template-matching algorithm used the training images to determine the tumor or organ position in the test images. Subsequently, a 3D base contour was shifted to the determined position and compared to the ground truth via centroid distance and Dice similarity coefficient.<br/>The median centroid distance between adapted and ground truth contours was 1.56 mm for the kidney, 3.81 mm for the gallbladder and 1.03 mm for the lung tumor (median Dice similarity coefficient: 0.95, 0.72 and 0.93). We observed that a decrease in image resolution led to a modest decrease in localization accuracy, especially for the small gallbladder. However, for all volumes of interest localization accuracy varied substantially more between subjects than due to the different imaging parameters.<br/>Automated tumor and organ localization using 2D cine MR imaging and template-matching-based autocontouring is robust against variation of geometric imaging parameters. Future work and optimization efforts of 2D cine MR imaging for real-time adaptive radiotherapy is needed to characterize the influence of sequence- and anatomical site-specific imaging contrast."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1088/1361-6560/aae74d"

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
url_pdf = "files/SOI.pdf"
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