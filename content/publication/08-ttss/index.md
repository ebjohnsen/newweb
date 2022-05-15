---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Intra-Object versus Inter-Object: Concurrency and Reasoning in Creol"
authors: ["Einar Broch Johnsen", "Jasmin Christian Blanchette", "Marcel Kyas", "Olaf Owe"]
date: 2008-07-21T22:54:34+02:00
doi: "http://dx.doi.org/10.1016/j.entcs.2009.07.007"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:29:29+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *2nd Intl. Workshop on Harnessing Theories for Tool Support in Software*. Electronic Notes in Theoretical Computer Science *243*:89-103, 2009. © Elsevier."
publication_short: "Proc. TTSS 2008"

abstract:  "In thread-based object-oriented languages, synchronous method calls usually provide the mechanism to transfer control from caller to callee, blocking the caller until the call is completed. This model of control flow is well-suited for sequential and tightly coupled systems but may be criticized in the concurrent and distributed setting, not only for unnecessary delays but also for the reasoning complexity of multithreaded programs. Concurrent objects propose an alternative to multithread concurrency for object-oriented languages, in which each object encapsulates a thread of control and communication between objects is asynchronous. Creol is a formally defined modeling language for concurrent objects which clearly separates intra-object scheduling from inter-object communication by means of interface encapsulation, asynchronous method calls, and internal processor release points. This separation of concerns provides a very clean model of concurrency which significantly simplifies reasoning for highly parallel and distributed object-oriented systems. This paper gives an example-driven introduction to these basic features of Creol and discusses how this separation of concerns influences analysis of Creol models."

# Summary. An optional shortened abstract.
summary: "Proc. TTSS 2008"

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
