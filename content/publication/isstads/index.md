---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On the Correctness of GPU Programs"
authors: ["Chao Peng"]
date: 2019-05-30T00:00:00+01:00
doi: "10.1145/3293882.3338989"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-05-30T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of The ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA)"
publication_short: "In proceedings of ISSTA 2019"

abstract: "Testing is an important and challenging part of software development and its effectiveness depends on the quality of test cases. However, there exists no means of measuring quality of tests developed for GPU programs and as a result, no test case generation techniques for GPU programs aiming at high test effectiveness. Existing criteria for sequential and threaded CPU programs cannot be directly applied to GPU programs as GPU follows a completely different memory and execution model.\n\nWe surveyed existing work on GPU program verification and bug fixes of open source GPU programs. Based on our findings, we define barrier, branch and loop coverage criteria and propose a set of mutation operators to measure fault finding capabilities of test cases. CLTestCheck, a framework for measuring quality of tests developed for GPU programs by code coverage analysis, fault seeding and work-group schedule amplification has been developed and evaluated using industry standard benchmarks. Experiments show that the framework is able to automatically measure test effectiveness and reveal unusual behaviours. Our planned work includes data flow coverage adopted for GPU programs to probe the underlying cause of unusual kernel behaviours and a more comprehensive work-group scheduler. We also plan to design and develop an automatic test case generator aiming at generating high quality test suites for GPU programs."

# Summary. An optional shortened abstract.
summary: ""
tags: ["Software Testing", "Code Coverage", "Fault Finding", "Data Race", "GPU", "OpenCL", "Test Case Generation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: pdf/ISSTA20DS.pdf
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
