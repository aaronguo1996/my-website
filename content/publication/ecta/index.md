---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Searching Entangled Program Spaces"
authors: [James Koppel, Zheng Guo, Edsko de Vries, Armando Solar-Lezama, Nadia Polikarpova]
date: 2022-09-11
doi: "10.1145/3519939.3523450"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-11

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "_the 27th ACM SIGPLAN International Conference on Functional Programming_"
publication_short: "ICFP 2022"

abstract: "Many problem domains, including program synthesis and rewrite-based optimization, require searching astronomically large spaces of programs. Existing approaches often rely on building specialized data structures—version-space algebras, finite tree automata, or e-graphs—to compactly represent such spaces. At their core, all these data structures exploit independence of subterms; as a result, they cannot efficiently represent more complex program spaces, where the choices of subterms are entangled.

We introduce equality-constrained tree automata (ECTAs), a new data structure, designed to compactly represent large spaces of programs with entangled subterms. We present efficient algorithms for extracting programs from ECTAs, implemented in a performant Haskell library, ecta. Using the ecta library, we construct Hectare, a type-driven program synthesizer for Haskell. Hectare significantly outperforms a state-of-the-art synthesizer Hoogle+ — providing an average speedup of 8x — despite its implementation being an order of magnitude smaller."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: PDF
  url: ecta_paper.pdf
  icon_pack: far
  icon: file-pdf
- name: EXTENDED
  url: ecta_extended.pdf
  icon_pack: far
  icon: file-pdf
- name: CODE
  url: https://github.com/jkoppel/ecta
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
projects: [ecta]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---