---
url_pdf: ""
summary: Using local, or intrinsic, definitions of data structures to develop predictable verification for data structures and systems.
url_video: ""
date: 2022-02-01T00:00:00Z
external_link: ""
show_date: false
url_slides: ""
title: Developing a Predictable Verification Paradigm with Intrinsic Defnitions of Data Structures
tags:
  - Programming Languages and Formal Methods
image:
  caption: Illustration of an intrinsically-defined linked list, and code verified in the philosophy built around intrinsic definitions.
  focal_point: Smart
url_code: ""
share: false
---
Much of the existing work on automated verification of data structure manipulations is impacted by unpredictability, since existing works generate verification conditions in incomplete logics that must be solved using unpredictable heuristics. Therefore, it is often the case that the proof of a correct program won't go through, forcing the engineer to perform proof engineering effort by adding lemmas and tactics, making for a frustrating verification experience. We avoid this by using local, or intrinsic definitions of data structures, rather than recursive ones, and we develop a verification philosophy that leads to predictable verification: a user provides a program and annotations that prove data structure invariants correct, and the verification problem becomes decidable. We have implemented this philosophy by verifying a range of standard data structures, including an overlay of a list and a binary search tree as seen in the Linux kernel I/O scheduler, as seen in this [preprint](uploads/IntrinsicDataStructures.pdf). We intend to extend our philosophy to the concurrent and distributed setting, verifying more complex systems and refining the paradigm from the engineer's perspective.
