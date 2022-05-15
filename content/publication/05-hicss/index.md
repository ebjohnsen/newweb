---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inheritance in the Presence of Asynchronous Method Calls"
authors: ["Einar Broch Johnsen", "Olaf Owe"]
date: 2005-12-21T22:50:16+02:00
doi: "http://dx.doi.org/10.1109/HICSS.2005.323"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:27:31+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 38th Hawaii Intl. Conf. on System Sciences (HICSS-38)*, © IEEE press, 2005."
publication_short: "Proc. HICSS 2005"

abstract: "This paper considers a formal object-oriented model for distributed computing.  Object orientation appears as a leading framework for concurrent and distributed systems.  However, the synchronization of the RPC communication model is unsatisfactory in many distributed systems.  Asynchronous message passing gives better control and efficiency in this setting, but lacks the structure and discipline of traditional object-oriented methods. The integration of the message concept in the object-oriented paradigm is unsettled, especially with respect to inheritance and redefinition.  We propose an approach combining asynchronous method calls and conditional processor release points, which reduces the cost of waiting for replies in the distributed environment while avoiding low-level synchronization constructs such as explicit signaling.  Even the lack of replies to method calls in unstable environments need not lead to deadlock in the invoking objects.  This property seems attractive in asynchronous, open, or unreliable environments.  Furthermore, the approach allows active and passive behavior (client and server) to be combined in concurrent objects in a very natural way.  In this paper, we consider the integration of these constructs with a mechanism for multiple inheritance within a small object-oriented language.  The language constructs are formally described by an operational semantics defined in rewriting logic."

# Summary. An optional shortened abstract.
summary: "Proc. HICSS 2005"

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
