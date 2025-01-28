---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CoReQA: Uncovering Potentials of Language Models in Code Repository Question Answering"
authors: ["Jialiang Chen", "Kaifa Zhao", "Jie Liu", admin, "Jierui Liu", "Hang Zhu", "Pengfei Gao", "Ping Yang", "Shuiguang Deng"]

date: 2025-01-07T00:00:00+01:00
doi: "10.48550/arXiv.2501.03447"

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

abstract: "Large language models that enhance software development tasks, such as code generation, code completion, and code question answering (QA), have been extensively studied in both academia and the industry. The models are integrated into popular intelligent IDEs like JetBrains and Cursor. Current benchmarks for evaluating models' code comprehension capabilities primarily focus on code generation or completion, often neglecting QA, which is a crucial aspect of understanding code. Existing code QA benchmarks are derived from code comments with predefined patterns (e.g., CodeQA) or focus on specific domains, such as education (e.g., CS1QA). These benchmarks fail to capture the real-world complexity of software engineering and user requirements for understanding code repositories. To address this gap, we introduce CoReQA, a benchmark for Code Repository-level question answering, constructed from GitHub issues and comments from 176 popular repositories across four programming languages. Since questions and answers may include both natural language and code snippets, traditional evaluation metrics such as BLEU are inadequate for assessing repository-level QA performance. Thus, we provide an LLM-as-a-judge framework to evaluate QA performance from five aspects. Based on CoReQA, we evaluate the performance of three baselines, including two short-context models using generic retrieval strategies and one long-context model that utilizes the entire repository context. Evaluation results show that state-of-the-art proprietary and long-context models struggle to address repository-level questions effectively. Our analysis highlights the limitations of language models in assisting developers in understanding repositories and suggests future directions for improving repository comprehension systems through effective context retrieval methodologies."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Repository-level dataset", "Code Benchmark"]
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
