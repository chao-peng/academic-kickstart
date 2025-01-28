---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Real-World Benchmark for Evaluating Fine-Grained Issue Solving Capabilities of Large Language Models"
authors: ["Ruida Hu", admin, "Jingyi Ren", "Bo Jiang", "Xiangxin Meng", "Qinyun Wu", "Pengfei Gao", "Xinchen Wang", "Cuiyun Gao"]

date: 2024-11-27T00:00:00+01:00
doi: "10.48550/arXiv.2411.18019"

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

abstract: "Automatically resolving software issues is crucial for software development in practice, impacting the software quality and user experience. The process of resolving real-world issues encompasses tasks such as question-answering (QA), fault localization, and code editing. Existing benchmarks such as HumanEval fall short in their ability to assess LLMs' proficiency in solving issues within a codebase. Although benchmarks like SWE-Bench are designed to evaluate the LLMs' capability to handle real-world GitHub issues, the end-to-end evaluation method cannot provide granular insights on the performance of subtasks involved in issue solving. To address existing deficiencies in benchmarking LLMs for practical software engineering tasks, we introduce FAUN-Eval, a benchmark specifically designed to evaluate the Fine-grAined issUe solviNg capabilities of LLMs. FAUN-Eval systematically assesses LLMs across three distinct tasks: QA, fault localization, and code editing. This benchmark is constructed using a dataset curated from 30 well-known GitHub repositories. For each entry, issue and pull request (PR) pairs are meticulously compiled and validated using cross-referencing and keyword verification methods. FAUN-Eval includes 300 entries and employs both LLM and manual checks to ensure data quality. We evaluate ten LLMs with FAUN-Eval, including four closed-source and six open-source models. Our experimental results reveal several key findings. We find that the top-performing LLMs differ across the different tasks. Additionally, features in issues may lead LLMs to generate incorrect information. Moreover, models may vary in their proficiency with texts of different lengths."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Code Question Answering", "Large Language Models", "Mining Software Repository"]
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
