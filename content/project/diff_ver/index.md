---
title: Differential Privacy Verification
summary: Using approximate solvers for non-linear real arithmetic to improve differential privacy verification.
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

Differential privacy is a technique that allows data to be aggregated while preserving the privacy of individual datapoints. Since differential privacy is defined mathematically, it is desirable and feasible to use formal techniques to determine properties of data-handling algorithms such as privacy and accuracy. To determine these properties, a program is encoded according to its semantics into a formula in the first-order theory of the reals with exponentiation, and the formula is then proved or disproved. However, our current state-of-the-art tool is not particularly fast, and the class of programs that can be verified is limited. Therefore, one of the goals of this project is to incorporate approximate solvers for non-linear real arithmetic into our verification tool. Since the fragment of non-linear real arithmetic these approximate solvers can handle is larger, we also hope to expand the class of programs we can verify.
