---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Run-time Environment for Concurrent Objects with Asynchronous Method Calls"
authors: ["Einar Broch Johnsen", "Olaf Owe", "Eyvind W. Axelsen"]
date: 2004-07-21T22:48:43+02:00
doi: "http://dx.doi.org/10.1016/j.entcs.2004.06.012"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:27:05+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 5th Intl. Workshop on Rewriting Logic and its Applications (WRLA 2004)*, <br> [Electronic Notes in Theoretical Computer Science](http://www.sciencedirect.com/science/journal/15710661) **117**: 375-392, 2005. © Elsevier."
publication_short: "Proc. WRLA 2004"

abstract: "A distributed system may be modeled by objects that run concurrently, each with its own processor, and communicate by remote method calls. However objects may have to wait for response to external calls; which can lead to inefficient use of processor capacity or even to deadlock. This paper addresses this limitation by means of asynchronous method calls and conditional processor release points. Although at the cost of additional internal nondeterminism in the objects, this approach seems attractive  in asynchronous or unreliable distributed environments. The concepts are illustrated by the small object-oriented language Creol and its operational semantics, which is defined using rewriting logic as a semantic framework. Thus, Creol specifications may be executed with Maude as a language interpreter, which allows an incremental development of the language constructs and their operational semantics supported by testing in Maude. However, for prototyping of highly non-deterministic systems, Maude's deterministic engine may be a limitation to practical testing. To overcome this problem, a rewrite strategy based on a pseudo-random number generator is proposed, providing Maude with nondeterministic behavior."

# Summary. An optional shortened abstract.
summary: "Proc. WRLA 2004"

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
