---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parallel Cost Analysis of Distributed Systems"
authors: ["Elvira Albert", "Jesús Correas", "Einar Broch Johnsen", "Guillermo Román-Díez"]
date: 2015-09-21T23:07:32+02:00 
doi: "http://dx.doi.org/10.1007/978-3-662-48288-9_16"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:35:27+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 22nd International Symposium on Static Analysis* (SAS 2015). LNCS 9291. © Springer 2015."
publication_short: "Proc. SAS 2015"

abstract: "We present a novel static analysis to infer the parallel cost of distributed systems. Parallel cost differs from the standard notion of serial cost by exploiting the truly concurrent execution model of distributed processing to capture the cost of synchronized tasks executing in parallel.It is challenging to analyze parallel cost because one needs to soundly infer the parallelism between tasks while accounting for waiting and idle processor times at the different locations. Our analysis works in three phases: (1) It first performs a block-level analysis to estimate the serial costs of the blocks between synchronization points in the program; (2) Next, it constructs a distributed flow graph (DFG) to capture the parallelism, the waiting and idle times at the locations of the distributed system; Finally, (3) the parallel cost can be obtained as the path of maximal cost in the DFG. A prototype implementation demonstrates the accuracy and feasibility of the proposed analysis."

# Summary. An optional shortened abstract.
summary: "Proc. SAS 2015"

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
