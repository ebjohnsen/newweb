---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Translating active objects into colored Petri nets for communication analysis"
authors: 
- Anastasia Gkolfi
- Crystal Chang Din
- einarj 
- Lars Michael Kristensen
- Martin Steffen
- Ingrid Chieh Yu
date: 2019-07-09T00:23:39+02:00
doi: "https://doi.org/10.1016/j.scico.2019.04.002"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:39:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Science of Computer Programming **181**: 1-26, 2019. © Elsevier."
publication_short: "Science of Computer Programming **181**: 1-26, 2019"

abstract: "Actor-based languages attract attention for their ability to scale to highly parallel architectures. Active objects combine the asynchronous communication of actors with object-oriented programming by means of asynchronous method calls and synchronization on futures. However, the combination of asynchronous calls and synchronization may introduce communication cycles which lead to a form of communication deadlock and livelock. This paper addresses such communication deadlocks and livelocks for ABS, a formally defined active object language which additionally supports cooperative scheduling to express complex distributed control flow, using first-class futures and explicit process release points. Our approach is based on a translation of the semantics of ABS into colored Petri nets, such that a program and its state correspond to a marking of this net. We prove the soundness of this translation and demonstrate by example how the implementation of this net can be used to analyze ABS programs with respect to communication deadlocks and livelocks."

# Summary. An optional shortened abstract.
summary: "Science of Computer Programming **181**: 1-26, 2019"

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

# [[url_custom]]
# -name: Preprint
# url: "papers/gkolfi19scp.pdf"

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
projects: [cumulus]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
