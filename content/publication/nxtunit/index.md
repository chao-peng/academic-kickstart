---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NxtUnit: Automated Unit Test Generation for Go"
authors: ["Siwei Wang", "Xue Mao", "Ziguang Gao", "Yujun Gao", "Qucheng Shen", "Chao Peng"]

date: 2023-06-14T00:00:00+01:00
# doi: "10.1007/978-3-030-16722-6_19"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 27th International Conference on Evaluation and Assessment in Software Engineering (EASE 2023)"
publication_short: "In proceedings of EASE 2023"

abstract: "Automated test generation has been extensively studied for dynamically compiled or typed programming languages like Java and Python. However, Go, a popular statically compiled and typed programming language for server application development, has received limited support from existing tools. To address this gap, we present NxtUnit, an automatic unit test generation tool for Go that uses random testing and is well-suited for microservice architecture. NxtUnit employs a random approach to generate unit tests quickly, making it ideal for smoke testing and providing quick quality feedback. It comes with three types of interfaces: an integrated development environment (IDE) plugin, a command-line interface (CLI), and a browser-based platform. The plugin and CLI tool allow engineers to write unit tests more efficiently, while the platform provides unit test visualization and asynchronous unit test generation. We evaluated NxtUnit by generating unit tests for 13 open-source repositories and 500 ByteDance in-house repositories, resulting in a code coverage of 20.74% for in-house repositories. We conducted a survey among ByteDance engineers and found that NxtUnit can save them 48% of the time on writing unit tests. We have made the CLI tool available at https://github.com/bytedance/nxt_unit."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Software Testing"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: pdf/EASE23.pdf
url_code:
url_dataset:
url_poster:
url_project: https://github.com/bytedance/nxt_unit
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
