---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parallel Cost Analysis."
authors: 
- Elvira Albert
- Jesús Correas
- einarj 
- Violet Ka I Pun
- Guillermo Román-Díez
date: 2018-11-20T00:23:39+02:00
doi: "https://doi.org/10.1145/3274278"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:39:18+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Computational Logic **19 (4)**: 31:1--31:37, 2018. © ACM."
publication_short: "ACM Transactions on Computational Logic **19 (4)**: 31:1--31:37, 2018"

abstract: "This article presents parallel cost analysis, a static cost analysis targeting to over-approximate the cost of parallel execution in distributed systems. In contrast to the standard notion of serial cost, parallel cost captures the cost of synchronized tasks executing in parallel by exploiting the true concurrency available in the execution model of distributed processing. True concurrency is challenging for static cost analysis, because the parallelism between tasks needs to be soundly inferred, and the waiting and idle processor times at the different locations need to be accounted for. Parallel cost analysis works in three phases: (1) it performs a block-level analysis to estimate the serial costs of the blocks between synchronization points in the program; (2) it then constructs a distributed flow graph (DFG) to capture the parallelism, the waiting, and idle times at the locations of the distributed system; and (3) the parallel cost can finally be obtained as the path of maximal cost in the DFG. We prove the correctness of the proposed parallel cost analysis, and provide a prototype implementation to perform an experimental evaluation of the accuracy and feasibility of the proposed analysis."

# Summary. An optional shortened abstract.
summary: "ACM Transactions on Computational Logic **19 (4)**: 31:1--31:37, 2018"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
