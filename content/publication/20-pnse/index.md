---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Model Checking Starvation for Resource-aware Active Objects with Coloured Petri Nets"
authors: 
- Anastasia Gkolfi
- einarj 
- Lars Michael Kristensen
- Ingrid Chieh Yu
date: 2020-06-1924T23:18:48+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-20T00:01:48+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proc. PNSE@Petri Nets 2020. CEUR Workshop Proceedings 2651, 2020"
publication_short: "Proc. PNSE@Petri Nets 2020"

abstract: "Dynamic resource provisioning is an important driver for
pay-on-demand cloud computing. Virtualized resources open for resource
awareness, such that applications may use resource management
strategies to modify their deployment resource consumption at
run-time. The ABS language supports the modeling of deployment
decisions and resource management for active objects. An important
property in this context is to ensure that the resource management
does not lead to starvation of the executing objects. In previous
work, we have formally translated the semantics of the ABS language
into a parameterized Coloured Petri Net (CPN) model, such that any ABS
program can be represented by setting the initial marking
accordingly. In this paper, we characterize starvation using
Computation Tree Logic (CTL), and demonstrate how CTL model checking
of the CPN encoding of the ABS model, in combination with path
finding, can be used to detect starvation and synthesize load
balancers that guarantee starvation freedom"

# Summary. An optional shortened abstract.
summary: "Proc. PNSE@Petri Nets 2020"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: PDF
   url: "http://ceur-ws.org/Vol-2651/paper5.pdf"
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
projects: [cumulus]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
