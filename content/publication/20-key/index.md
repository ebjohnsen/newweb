---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SymPaths: Symbolic Execution Meets Partial Order Reduction"
authors: 
- Frank de Boer
- Marcello Bonsangue
- einarj 
- Violet Ka I Pun
- S. Lizeth Tapia Tarifa
- Lars Tveito
date: 2020-08-20T00:17:05+02:00
doi: "https://doi.org/10.1007/978-3-030-64354-6_13"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-20T00:17:05+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "Deductive Software Verification: Future Perspectives. LNCS 12345, Springer 2020."
publication_short: "Deductive Software Verification: Future Perspectives. LNCS 12345, Springer 2020"

abstract: "Symbolic execution is an important technique for software
  analysis, which enables systematic model exploration by following
  all possible execution paths for a given program. For multithreaded
  shared variable programs, this technique leads to a state space
  explosion. Partial order reduction is a technique which allows
  equivalent execution paths to be recognized, reducing the state
  space explosion problem. This paper provides formal justifications
  for these techniques in a multithreaded setting by proving the
  correctness and completeness of symbolic execution for multithreaded
  shared variable programs, with and without the use of partial order
  reduction. We then show how these formal justifications carry over
  to prove the soundness and relative completeness of a proof system
  for such multithreaded shared variable programs in dynamic logic,
  such that partial order reduction can be used to simplify the proof
  construction by mitigating the state space explosion."

# Summary. An optional shortened abstract.
summary: "Deductive Software Verification: Future Perspectives. LNCS 12345, Springer 2020."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Artefact
  url: "https://github.com/larstvei/sympaths"

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
