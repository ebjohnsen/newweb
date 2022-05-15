---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Minimal Ownership for Active Objects"
authors: ["Dave Clarke", "Tobias Wrigstad", "Johan Östlund", "Einar Broch Johnsen"]
date: 2008-12-21T22:54:17+02:00
doi: "http://dx.doi.org/10.1007/978-3-540-89330-1_11"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:28:49+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 6th Asian Symposium on Programming Languages and Systems (APLAS'08)*. LNCS 5356. © Springer 2008."
publication_short: "Proc. APLAS 2008"

abstract: "Active objects offer a structured approach to concurrency, encapsulating both unshared state and a thread of control. For efficient data transfer, data should be passed by reference whenever possible, but this introduces aliasing and undermines the validity of the active objects. This paper proposes a minimal variant of ownership types that preserves the required race freedom invariant yet enables data transfer by reference between active objects (that is, without copying) in many cases, and a cheap clone operation where copying is necessary. Our approach is general and should be adaptable to several existing active object systems."

# Summary. An optional shortened abstract.
summary: "Proc. APLAS 2008"

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
