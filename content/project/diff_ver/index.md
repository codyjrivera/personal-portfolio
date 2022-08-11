---
title: Verification of Differential Privacy Properties
summary: Improving decidablility of real-number formulae for verification of differential privacy properties.
tags:
  - Programming Languages and Formal Methods
date: '2022-01-01T00:00:00Z'
show_date: false

# Optional external URL for project (replaces project detail page).
external_link: ''

share: false

image:
  caption: Illustration of differential privacy
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

Differential privacy is a technique that allows data to be aggregated while preserving the privacy of individual datapoints. Since differential privacy is defined mathematically, it is desirable and feasible to use formal techniques to determine properties of data-handling algorithms such as privacy and accuracy. To determine these properties, a program is encoded according to its semantics into a formula in the first-order theory of the reals with exponentiation, and the formula is then proved or disproved. However, some of the generated formulae fall into decidable fragments of the aforementioned theory, while others fall into undecidable fragments. Part of the project will be to investigate the decidability of a broader range of formulae, such as those formulae that are similar to a decidable formula. By enlarging the class of formulae corresponding to program encodings that tools can handle, this project aims to improve techniques for verifying differential privacy-related properties of programs.
