---
title: 'Optimizing Huffman Decoding for Error-Bounded Lossy Compression on GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sheng Di
  - Jiannan Tian
  - Xiaodong Yu
  - Dingwen Tao
  - Franck Cappello

share: false

date: '2022-06-01T00:00:00Z'
doi: '10.1109/IPDPS53621.2022.00075'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2022 IEEE International Parallel and Distributed Processing Symposium (Preprint)
publication_short: In IPDPS '22

abstract: "More and more HPC applications require fast and effective compression techniques to handle large volumes of data in storage and transmission. Not only do these applications need to compress the data effectively during simulation, but they also need to perform decompression efficiently for post hoc analysis. SZ is an error-bounded lossy compressor for scientific data, and cuSZ is a version of SZ designed to take advantage of the GPU's power. At present, cuSZ's compression performance has been optimized significantly while its decompression still suffers considerably lower performance because of its sophisticated lossless compression step -- a customized Huffman decoding. In this work, we aim to significantly improve the Huffman decoding performance for cuSZ, thus improving the overall decompression performance in turn. To this end, we first investigate two state-of-the-art GPU Huffman decoders in depth. Then, we propose a deep architectural optimization for both algorithms. Specifically, we take full advantage of CUDA GPU architectures by using shared memory on decoding/writing phases, online tuning the amount of shared memory to use, improving memory access patterns, and reducing warp divergence. Finally, we evaluate our optimized decoders on an Nvidia V100 GPU using eight representative scientific datasets. Our new decoding solution obtains an average speedup of 3.64X over cuSZ's Huffman decoder and improves its overall decompression performance by 2.43X on average."

tags: [High-Performance Computing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/optimizing/paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - cusz

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
