---
title: 'Optimizing Error-Bounded Lossy Compression for Scientific Data on GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiannan Tian
  - Sheng Di
  - Xiaodong Yu
  - admin
  - Kai Zhao
  - Sian Jin
  - Yunhe Feng
  - Xin Liang
  - Dingwen Tao
  - Franck Cappello

share: false

date: '2021-10-13T00:00:00Z'
doi: '10.1109/Cluster48925.2021.00047'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2021 IEEE International Conference on Cluster Computing
publication_short: In CLUSTER '21

abstract: "Error-bounded lossy compression is a critical technique for significantly reducing scientific data volumes. With ever-emerging heterogeneous high-performance computing (HPC) architecture, GPU-accelerated error-bounded compressors (such as CUSZ and cuZFP) have been developed. However, they suffer from either low performance or low compression ratios. To this end, we propose CUSZ+ to target both high compression ratios and throughputs. We identify that data sparsity and data smoothness are key factors for high compression throughputs. Our key contributions in this work are fourfold: (1) We propose an efficient compression workflow to adaptively perform run-length encoding and/or variable-length encoding. (2) We derive Lorenzo reconstruction in decompression as multidimensional partial-sum computation and propose a fine-grained Lorenzo reconstruction algorithm for GPU architectures. (3) We carefully optimize each of CUSZ kernels by leveraging state-of-the-art CUDA parallel primitives. (4) We evaluate CU SZ+ using seven real-world HPC application datasets on V100 and A100 GPUs. Experiments show CUSZ+ improves the compression throughputs and ratios by up to 18.4× and 5.3×, respectively, over CUSZ on the tested datasets."

tags: [High-Performance Computing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/cusz-plus/paper.pdf'
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
