---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Safe Locking for Multi-Threaded Java with Exceptions"
authors: ["Einar Broch Johnsen", "Thi Mai Thuong Tran", "Olaf Owe", "Martin Steffen"]
date: 2012-04-21T23:01:36+02:00
doi: "http://dx.doi.org/doi:10.1016/j.jlap.2011.11.002"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:33:09+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication:  "Journal of Logic and Algebraic Programming **81** (3): 257-283, 2012. © Elsevier. "
publication_short:  "Journal of Logic and Algebraic Programming **81** (3): 257-283, 2012"

abstract: "There are many mechanisms for concurrency control in high-level programming languages. In Java, the original mechanism for concurrency control, based on synchronized blocks, is lexically scoped. For more flexible control, Java 5 introduced non-lexical lock primitives on re-entrant locks.These operators may lead to run-time errors and unwanted behavior; e.g., taking a lock without releasing it, which could lead to a deadlock, or trying to release a lock without owning it. This paper develops a static type and effect system to prevent the mentioned lock errors for a formal, object-oriented calculus which supports non-lexical lock handling and exceptions. Based on an operational semantics, we prove soundness of the effect type analysis. Challenges in the design of the effect type system are dynamic creation of threads, objects, and especially of locks, aliasing of lock references, passing of lock references between threads, and reentrant locks as found in Java. Furthermore, the exception handling mechanism complicates the control-flow and thus the analysis."

# Summary. An optional shortened abstract.
summary: "Journal of Logic and Algebraic Programming **81** (3): 257-283, 2012"

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
