---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An Empirical Study on LLM-based Agents for Automated Bug Fixing"
authors: ["Xiangxin Meng", "Zexiong Ma", "Pengfei Gao", admin]

date: 2024-11-15T00:00:00+01:00
doi: "10.48550/arXiv.2411.10213"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: "Large language models (LLMs) and LLM-based Agents have been applied to fix bugs automatically, demonstrating the capability in addressing software defects by engaging in development environment interaction, iterative validation and code modification. However, systematic analysis of these agent and non-agent systems remain limited, particularly regarding performance variations among top-performing ones. In this paper, we examine seven proprietary and open-source systems on the SWE-bench Lite benchmark for automated bug fixing. We first assess each system's overall performance, noting instances solvable by all or none of these sytems, and explore why some instances are uniquely solved by specific system types. We also compare fault localization accuracy at file and line levels and evaluate bug reproduction capabilities, identifying instances solvable only through dynamic reproduction. Through analysis, we concluded that further optimization is needed in both the LLM itself and the design of Agentic flow to improve the effectiveness of the Agent in bug fixing."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Bug Fixing", "Large Language Models", "Agents", "Empirical Study"]
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
