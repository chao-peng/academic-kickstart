---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Effective Concurrency Testing for Go via Directional Primitive-constrained Interleaving Exploration"
authors: ["Zongze Jiang", "Ming Wen", "Yixin Yang", admin, "Ping Yang", "Hai Jin"]

date: 2023-09-11T00:00:00+01:00
# doi: "10.1007/978-3-030-16722-6_19"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 38th IEEE/ACM International Conference on Automated Software Engineering (ASE 2023)"
publication_short: "In proceedings of ASE 2023"

abstract: "The Go language (Go/Golang) has been attracting increasing attention from the industry in recent years due to its straightforward syntax, strong concurrency support, and ease of deployment. This programming language encourages developers to use channel-based concurrency, which simplifies development. Unfortunately, it also introduces new concurrency problems that differ from those caused by the mechanism of shared memory concurrency. Despite this, there are only few works that aim to detect these Go-specific concurrency issues. Even state-of-the-art testing tools will miss critical concurrent bugs that require fine-grained and effective interleaving exploration.\n\nThis paper presents GoPie, a novel testing approach for detecting Go concurrent bugs through primitive-constrained interleaving exploration. GoPie utilizes execution histories to identify new interleavings instead of relying on exhaustive exploration or random scheduling. To evaluate its effectiveness, we applied GoPie on existing benchmarks and large-scale open-source projects. Results show that GoPie can effectively explore concurrent interleavings and detect significantly more bugs in the benchmark. Furthermore, it uncovered 11 unique previously unknown concurrent bugs, and 9 of which have been confirmed."

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

url_pdf:
url_code:
url_dataset:
url_poster:
url_project: https://zenodo.org/record/8185418
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
