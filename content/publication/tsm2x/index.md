---
title: 'TSM2X: High-performance tall-and-skinny matrix–matrix multiplication on GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jieyang Chen
  - Nan Xiong
  - Jing Zhang
  - Shuaiwen Leon Song
  - Dingwen Tao

author_notes:
  - 'Equal contribution'
  - 'Equal contribution' 

share: false

date: '2021-05-01T00:00:00Z'
doi: '10.1016/j.jpdc.2021.02.013'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Parallel and Distributed Computing, Volume 151
publication_short: JPDC, Vol. 151

abstract: "Linear algebra operations have been widely used in big data analytics and scientific computations. Many works have been done on optimizing linear algebra operations on GPUs with regular-shaped input. However, few works focus on fully utilizing GPU resources when the input is not regular-shaped. Current optimizations do not consider fully utilizing the memory bandwidth and computing power; therefore, they can only achieve sub-optimal performance. In this paper, we propose two efficient algorithms – TSM2R and TSM2L – for two classes of tall-and-skinny matrix–matrix multiplications on GPUs. Both of them focus on optimizing linear algebra operation with at least one of the input matrices tall-and-skinny. Specifically, TSM2R is designed for a large regular-shaped matrix multiplying a tall-and-skinny matrix, while TSM2L is designed for a tall-and-skinny matrix multiplying a small regular-shaped matrix. We implement our proposed algorithms and test on several modern NVIDIA GPU micro-architectures. Experiments show that, compared to the current state-of-the-art works, (1) TSM2R speeds up the computation by 1.6x on average and improves the memory bandwidth utilization and computing power utilization by 18.1% and 20.5% on average, respectively, when the regular-shaped matrix size is relatively large or medium; and (2) TSM2L speeds up the computation by 1.9x on average and improves the memory bandwidth utilization by up to 9.3% on average when the regular-shaped matrix size is relatively small."

tags: [High-Performance Computing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/tsm2x/paper.pdf'
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
  - tsm2x

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
