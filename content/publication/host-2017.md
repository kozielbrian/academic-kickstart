+++
title = "On Secure Implementations of Quantum-Resistant Supersingular Isogeny Diffie-Hellman"
date = 2017-05-22T01:31:51-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["__B. Koziel__", "R. Azarderakhsh", "D. Jao"]

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
publication = "2017 IEEE International Symposium on Hardware Oriented Security and Trust, HOST 2017, McLean, VA, USA, May 1-5, 2017"
publication_short = "HOST"

# Abstract and optional shortened version.
abstract = "In this work, we analyze the feasibility of a physically secure implementation of the quantum-resistant supersingular isogeny Diffie-Hellman (SIDH) protocol. Notably, we analyze the defense against timing attacks, simple power analysis, differential power analysis, and fault attacks. Luckily, the SIDH protocol closely resembles its predecessor, the elliptic curve Diffie-Hellman (ECDH) key exchange. As such, much of the extensive literature in side-channel analysis can also apply to SIDH. In particular, we focus on a hardware implementation that features a true random number generator, ALU, and controller. SIDH is composed of two rounds containing a double-point multiplication to generate a secret kernel point and an isogeny over that kernel to arrive at a new elliptic curve isomorphism. To protect against simple power analysis and timing attacks, we recommend a constant-time implementation with Fermat's little theorem inversion. Differential power analysis targets the power output of the SIDH core over many runs. As such, we recommend scaling the base points by secret scalars so that each iteration has a unique power signature. Further, based on recent oracle attacks on SIDH, we cannot recommend the use of static keys from both parties. The goal of this paper is to analyze the tradeoffs in elliptic curve theory to produce a cryptographically and physically secure implementation of SIDH."
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
tags = ["Post-Quantum Cryptography", "Isogeny-Based Cryptography", "Side-Channel Analysis", "Hardware Architectures"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/7951824"
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
