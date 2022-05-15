---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Formal Model of Parallel Execution on Multicore Architectures with Multilevel Caches"
authors: 
- Shiji Bijo
- einarj 
- Ka I Pun
- Silvia Lizeth Tapia Tarifa
date: 2017-10-22T00:23:39+02:00
doi: "https://doi.org/10.1007/978-3-319-68034-7_4"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:37:23+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 14th International Conference on Formal Aspects of Component Software (FACS 2017)*, LNCS 10487.  © Springer 2017."
publication_short: "Proc. FACS 2017"

abstract: "The performance of software running on parallel or distributed architectures can be severely affected by the location of data. On shared memory multicore architectures, data movement between caches and main memory is driven by tasks executing in parallel on different cores and by a protocol to ensure cache coherence, such as MSI. This paper integrates MSI in a formal model to capture such data movement from an application perspective. We develop an executable model which integrates cache coherent data movement between different cache levels and main memory, for software described by task-level data access patterns. The proposed model is generic in the number of cache levels and cores, and abstracts from the concrete communication medium. We show that the model guarantees expected correctness properties for the MSI protocol, in particular data consistency. This paper further presents a proof of concept implementation of the proposed model in rewriting logic, which allows different choices for a program's underlying hardware architecture to be specified and compared."

# Summary. An optional shortened abstract.
summary: "Proc. FACS 2017"

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
