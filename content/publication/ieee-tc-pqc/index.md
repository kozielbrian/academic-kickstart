+++
title = "A High-Performance and Scalable Hardware Architecture for Isogeny-Based Cryptography"
date = 2018-07-21T23:54:25-04:00
draft = false

# Authors. Comma separated list, e.g. `["Brian Koziel"]`.
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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE Transacations on Computers: Special Section on Cryptographic Engineering in a Post-Quantum World" 
publication_short = "IEEE TC: PQC"

# Abstract and optional shortened version.
abstract = "In this work, we present a high-performance and scalable architecture for isogeny-based cryptosystems. In particular, we use the architecture in a fast, constant-time FPGA implementation of the quantum-resistant supersingular isogeny Diffie-Hellman (SIDH) key exchange protocol. On a Virtex-7 FPGA, we show that our architecture is scalable by implementing at 83, 124, 168, and 252-bit quantum security levels. This is the first SIDH implementation at close to the 256-bit quantum security level to appear in literature. Further, our implementation completes the SIDH protocol 2 times faster than performance-optimized software implementations and 1.34 times faster than the previous best FPGA implementation, both running a similar set of formulas. Our implementation employs inversion-free projective isogeny formulas. By replicating multipliers and utilizing an efficient scheduling methodology, we can heavily parallelize quadratic extension field arithmetic and the isogeny evaluation stage of the large-degree isogeny computation. For a constant-time implementation of 124-bit quantum security SIDH on a Virtex-7 FPGA, we generate ephemeral public keys in 8.0 and 8.6 ms and generate the shared secret key in 7.1 and 7.9 ms for Alice and Bob, respectively. Finally, we show that this architecture could also be used to efficiently generate undeniable and digital signatures based on supersingular isogenies."
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
url_pdf = "https://ieeexplore.ieee.org/document/8315051/"
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
