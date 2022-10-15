---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Type-Directed Program Synthesis for RESTful APIs"
authors: [Zheng Guo, David Cao, Davin Tjong, Jean Yang, Cole Schlesinger, Nadia Polikarpova]
date: 2022-06-15
doi: "10.1145/3519939.3523450"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-23

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "_the 43rd ACM SIGPLAN Conference on Programming Language Design and Implementation_"
publication_short: "PLDI 2022"

abstract: "With the rise of software-as-a-service and microservice architectures, RESTful APIs are now ubiquitous in mobile and web applications. A service can have tens or hundreds of API methods, making it a challenge for programmers to find the right combination of methods to solve their task.
We present APIphany, a component-based synthesizer for programs that compose calls to RESTful APIs. The main innovation behind APIphany is the use of precise semantic types, both to specify user intent and to direct the search. APIphany contributes three novel mechanisms to overcome challenges in adapting component-based synthesis to the REST domain: (1) a type inference algorithm for augmenting REST specifications with semantic types; (2) an efficient synthesis technique for \"wrangling\" semi-structured data, which is commonly required in working with RESTful APIs; and (3) a new form of simulated execution to avoid executing APIs calls during synthesis. We evaluate APIphany on three real-world APIs and 32 tasks extracted from GitHub repositories and StackOverflow. In our experiments, APIphany found correct solutions to 29 tasks, with 23 of them reported among top ten synthesis results."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: PDF
  url: apiphany_paper.pdf
  icon_pack: far
  icon: file-pdf
- name: EXTENDED
  url: apiphany_extended.pdf
  icon_pack: far
  icon: file-pdf
- name: CODE
  url: https://github.com/aaronguo1996/rest_api_synthesis
  icon_pack: fas
  icon: code-branch


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
projects: [apiphany]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---