+++
title = "Low-Resource and Fast Elliptic Curve Implementations over Binary Edwards Curves"
date = 2016-05-24T21:31:23-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Brian Koziel"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "RIT Scholar Works: Theses"
publication_short = "RIT Theses"

# Abstract and optional shortened version.
abstract = "Elliptic curve cryptography (ECC) is an ideal choice for low-resource applications because it provides the same level of security with smaller key sizes than other existing public key encryption schemes. For low-resource applications, designing efficient functional units for elliptic curve computations over binary fields results in an effective platform for an embedded co-processor. This thesis investigates co-processor designs for area-constrained devices. Particularly, we discuss an implementation utilizing state of the art binary Edwards curve equations over mixed point addition and doubling. The binary Edwards curve offers the security advantage that it is complete and is, therefore, immune to the exceptional points attack. In conjunction with Montgomery ladder, such a curve is naturally immune to most types of simple power and timing attacks. Finite field operations were performed in the small and efficient Gaussian normal basis. The recently presented formulas for mixed point addition by K. Kim, C. Lee, and C. Negre at Indocrypt 2014 were found to be invalid, but were corrected such that the speed and register usage were maintained. We utilize corrected mixed point addition and doubling formulas to achieve a secure, but still fast implementation of a point multiplication on binary Edwards curves. Our synthesis results over NIST recommended fields for ECC indicate that the proposed co-processor requires about 50% fewer clock cycles for point multiplication and occupies a similar silicon area when compared to the most recent in literature."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Binary Edwards Curves", "Gaussian Normal Basis", "Low-Resource Devices", "Crypto-Processor"]

# Links (optional).
url_pdf = "http://scholarworks.rit.edu/theses/9145/"
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
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

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
