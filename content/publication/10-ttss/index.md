---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Models of Rate Restricted Communication for Concurrent Objects"
authors: ["Rudolf Schlatte", "Einar Broch Johnsen", "Fatemeh Kazemeyni", "S. Lizeth Tapia Tarifa"]
date: 2011-08-21T22:59:52+02:00
doi: "http://dx.doi.org/10.1016/j.entcs.2011.07.007"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:31:15+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 4th Intl. Workshop on Harnessing Theories for Tool Support in Software (TTSS 2010)*. Electronic Notes in Theoretical Computer Science **274**:67-81, 2011. © Elsevier."
publication_short: "Proc. TTSS 2010"

abstract: "Many software systems today are designed for deployment on a range of architectures. However, in formal models it is typically assumed that the architecture is known and fixed; for example, that the software is sequential or concurrent, that the communication environment is synchronous or asynchronous but ordered, etc. In order to specify and analyze models which range over different deployment scenarios, it is interesting to lift aspects of low-level deployment variability to the abstraction level of the modeling language. In this paper, we propose a technique for introducing explicit resource constraints on concurrent objects in a timed extension of Creol, a formally defined high-level object-oriented modeling language. The technique is demonstrated by examples concerning rate restrictions on communication between objects. These restrictions are compositional and non-invasive: no change to the functional parts of the model is required, and restrictions can be selectively applied to parts of the model. In fact, the rate restrictions are captured by parameters in the model, which allows timed simulations to be performed with varying rate restrictions. We demonstrate the usefulness of explicit rate restrictions on communication in the model by a case study of wireless sensor networks. In this domain, rate restrictions may be understood as an abstraction over the collision patterns of broadcast data packets. Simulation results with different rate restrictions show how the timed throughput of data to the sink node in the network varies depending on the available rates."

# Summary. An optional shortened abstract.
summary: "Proc. TTSS 2010"

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
