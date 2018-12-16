+++
title = "Fast Hardware Architectures for Supersingular Isogeny Diffie-Hellman Key Exchange on FPGA"
date = 2016-12-22T01:00:42-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["__B. Koziel__", "R. Azarderakhsh", "M. M. Kermani"]

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
publication = "Progress in Cryptology - INDOCRYPT 2016, 17th International Conference on Cryptology in India, Kolkata, India, December 11-14, 2016, Proceedings"
publication_short = "Indocrypt"

# Abstract and optional shortened version.
abstract = "In this paper, we present a constant-time hardware implementation that achieves new speed records for the supersingular isogeny Diffie-Hellman (SIDH), even when compared to highly optimized Haswell computer architectures. We employ inversion-free projective isogeny formulas presented by Costello et al. at CRYPTO 2016 on an FPGA. Modern FPGA’s can take advantage of heavily parallelized arithmetic in $\\mathbb{F}_{p^2}$ , which lies at the foundation of supersingular isogeny arithmetic. Further, by utilizing many arithmetic units, we parallelize isogeny evaluations to accelerate the computations of large-degree isogenies by approximately 57%. On a constant-time implementation of 124-bit quantum security SIDH on a Virtex-7, we generate ephemeral public keys in 10.6 and 11.6 ms and generate the shared secret key in 9.5 and 10.8 ms for Alice and Bob, respectively. This improves upon the previous best time in the literature for 768-bit implementations by a factor of 1.48. Our 83-bit quantum security implementation improves upon the only other implementation in the literature by a speedup of 1.74 featuring fewer resources and constant-time."
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
tags = ["Post-Quantum Cryptography", "Elliptic Curve Cryptography", "Isogeny-Based Cryptography", "Field Programmable Gate Array"]

# Links (optional).
url_pdf = "https://link.springer.com/chapter/10.1007%2F978-3-319-49890-4_11"
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
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
