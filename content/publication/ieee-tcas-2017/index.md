+++
title = "Post-Quantum Cryptography on FPGA Based on Isogenies on Elliptic Curves"
date = 2017-01-22T00:25:01-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["__B. Koziel__", "R. Azarderakhsh", "M. M. Kermani", "D. Jao"]

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
publication = "IEEE Transactions on Circuits and Systems I: Regular Papers"
publication_short = "IEEE TCAS"

# Abstract and optional shortened version.
abstract = "To the best of our knowledge, we present the first hardware implementation of isogeny-based cryptography available in the literature. Particularly, we present the first implementation of the supersingular isogeny Diffie-Hellman (SIDH) key exchange, which features quantum-resistance. We optimize this design for speed by creating a high throughput multiplier unit, taking advantage of parallelization of arithmetic in ${\\mathbb{F}_{p^2}}$ , and minimizing pipeline stalls with optimal scheduling. Consequently, our results are also faster than software libraries running affine SIDH even on Intel Haswell processors. For our implementation at 85-bit quantum security and 128-bit classical security, we generate ephemeral public keys in 1.655 million cycles for Alice and 1.490 million cycles for Bob. We generate the shared secret in an additional 1.510 million cycles for Alice and 1.312 million cycles for Bob. On a Virtex-7, these results are approximately 1.5 times faster than known software implementations running the same 512-bit SIDH. Our results and observations show that the isogeny-based schemes can be implemented with high efficiency on reconfigurable hardware."
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
tags = ["Elliptic Curve Cryptography", "Field Programmable Gate Array", "Isogeny-Based Cryptography", "Post-Quantum Cryptography"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/7725935"
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
