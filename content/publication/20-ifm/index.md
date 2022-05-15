---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Active Objects with Deterministic Behavior"
authors: 
- Ludovic Henrio
- einarj 
- Violet Ka I Pun

date: 2020-11-14T09:21:51+02:00
doi: "10.1007/978-3-030-63461-2_10"
# draft: true

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-12T09:21:51+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proc. 16th International Conference on integrated Formal
Methods (IFM 2020). LNCS 12546. © Springer 2020"
publication_short: "Proc. IFM 2020. LNCS 12546, Springer 2020"

abstract: "  Active objects extend the Actor paradigm with structured
  communication using method calls and futures.  Active objects are,
  like actors, known to be data race free. Both are inherently
  concurrent, as they share a fundamental decoupling of communication
  and synchronisation. Both encapsulate their state, restricting
  access to one process at a time. Clearly, this rules out low-level
  races between two processes accessing a shared variable. But is that
  sufficient to guarantee deterministic results from the execution of
  an active object program?

  In this paper we are interested in so-called high-level races caused
  by the fact that the arrival order of messages between active
  objects can be non-deterministic, resulting in non-deterministic
  overall behaviour. We study this problem in the setting of a core
  calculus and identify restrictions on active object programs which
  are sufficient to guarantee deterministic behaviour for active object
  programs. We formalise these restrictions as a simple extension to
  the type system of the calculus and prove that well-typed programs
  exhibit deterministic behaviour."

# Summary. An optional shortened abstract.
summary: "Proc. IFM 2020. LNCS 12546, Springer 2020"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Tech. report
  url: "https://hvlopen.brage.unit.no/hvlopen-xmlui/bitstream/handle/11250/2679468/HVL_Rapport_8_2020.pdf"
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
