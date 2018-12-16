+++
title = "Key Compression for Isogeny-Based Cryptosystems"
date = 2016-06-22T00:55:04-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["R. Azarderakhsh", "D. Jao", "K. Kalach", "__B. Koziel__", "C. Leonardi"]

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
publication = "Proceedings of the 3rd ACM International Workshop on ASIA Public-Key Cryptography, AsiaPKC@AsiaCCS, Xi'an, China, May 30 - June 03, 2016"
publication_short = "AsiaPKC"

# Abstract and optional shortened version.
abstract = "We present a method for key compression in quantum-resistant isogeny-based cryptosystems, which allows a reduction in and transmission costs of per-party public information by a factor of two, with no e ect on security. We achieve this reduction by associating a canonical choice of elliptic curve to each j-invariant, and representing elements on the curve as linear combinations with respect to a canonical choice of basis. This method of compressing public information can be applied to numerous isogeny-based protocols, such as key exchange, zero-knowledge identi cation, and public-key encryption. We performed personal computer and ARM implementations of the key exchange with compression and decompression in C and provided timing results, showing the computational cost of key compression and decompression at various security levels. Our results show that isogeny-based cryptosystems achieve by far the smallest possible key sizes among all existing families of post-quantum cryptosystems at practical security levels; e.g. 3073-bit public keys at the quantum 128-bit security level, comparable to (non-quantum) RSA key sizes."
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
tags = ["Elliptic Curve Cryptography", "Isogeny-Based Cryptography", "Key Compression", "Post-Quantum Cryptography"]

# Links (optional).
url_pdf = "https://dl.acm.org/citation.cfm?doid=2898420.2898421"
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
