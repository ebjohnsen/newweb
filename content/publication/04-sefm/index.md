---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An Asynchronous Communication Model for Distributed Concurrent Objects"
authors: ["Einar Broch Johnsen", "Olaf Owe"]
date: 2004-09-21T22:49:05+02:00
doi: "http://dx.doi.org/10.1109/SEFM.2004.10017"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:26:51+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 2nd Intl. Conf. on Software Engineering and Formal Methods (SEFM 2004)*, <br>© IEEE press, 2004."
publication_short: "Proc. SEFM 2004"

abstract: "Distributed systems are often modeled by objects that run concurrently, each with its own processor , and communicate by synchronous remote method calls.  This may be satisfactory for tightly coupled systems, but in the distributed setting synchronous external calls seem less satisfactory; at best resulting in inefficient use of processor capacity , at wor st resulting in deadlock. Furthermore, it is difficult to combine active and passive behavior in concurrent objects.  This paper proposes a solution to these problems by means of asynchronous method calls and conditional processor release points. Although at the cost of additional internal non- determinism in the objects, this approach seems attractive in asynchronous or unreliable environments.  The concepts are inte grated in a small object-oriented language with an oper ational semantics defined in rewriting logic, and illustrated by an example of a peer-to-peer network."

# Summary. An optional shortened abstract.
summary: ""

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
