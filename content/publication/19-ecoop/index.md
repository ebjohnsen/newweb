---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Godot: All the Benefits of Implicit and Explicit Futures"
authors:  
- Kiko Fernandez-Reyes
- Dave Clarke
- Ludovic Henrio
- einarj 
- Tobias Wrigstad
date: 2019-07-10T23:08:36+02:00
doi: "https://doi.org/10.4230/LIPIcs.ECOOP.2019.2"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:39:07+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 33rd European Conference on Object-Oriented Programming* (ECOOP 2019). LIPIcs 134. Schloss Dagstuhl--Leibniz-Zentrum fuer Informatik 2019."
publication_short: "Proc. ECOOP 2019"

abstract: "Concurrent programs often make use of futures, handles to the results of asynchronous operations. Futures provide means to communicate not yet computed results, and simplify the implementation of operations that synchronise on the result of such asynchronous operations. Futures can be characterised as implicit or explicit, depending on the typing discipline used to type them. Current future implementations suffer from \"future proliferation\", either at the type-level or at run-time. The former adds future type wrappers, which hinders subtype polymorphism and exposes the client to the internal asynchronous communication architecture. The latter increases latency, by traversing nested future structures at run-time. Many languages suffer both kinds. Previous work offer partial solutions to the future proliferation problems; in this paper we show how these solutions can be integrated in an elegant and coherent way, which is more expressive than either system in isolation. We describe our proposal formally, and state and prove its key properties, in two related calculi, based on the two possible families of future constructs (data-flow futures and control-flow futures). The former relies on static type information to avoid unwanted future creation, and the latter uses an algebraic data type with dynamic checks. We also discuss how to implement our new system efficiently."

# Summary. An optional shortened abstract.
summary: "Proc. ECOOP 2019"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Artefact
  url: "http://dx.doi.org/10.4230/DARTS.5.2.1"
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://drops.dagstuhl.de/opus/volltexte/2019/10794/pdf/LIPIcs-ECOOP-2019-2.pdf
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
