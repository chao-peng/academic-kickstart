---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CodeVisionary: An Agent-based Framework for Evaluating Large Language Models in Code Generation"
authors: ["Xinchen Wang", "Pengfei Gao", admin, "Ruida Hu", "Cuiyun Gao"]

date: 2025-09-16T00:00:00+01:00
doi: "10.48550/arXiv.2504.13472"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 40th IEEE/ACM International Conference on Automated Software Engineering (ASE 2025)"
publication_short: "ASE 2025"

abstract: "Large language models (LLMs) have demonstrated strong capabilities in code generation, underscoring the critical need for rigorous and comprehensive evaluation. Existing evaluation approaches fall into three categories, including human-centered, metric-based, and LLM-based. Considering that human-centered approaches are labour-intensive and metric-based ones overly rely on reference answers, LLM-based approaches are gaining increasing attention due to their stronger contextual understanding capabilities and superior efficiency. However, the performance of LLM-based approaches remains limited due to: (1) lack of multisource domain knowledge, and (2) insufficient comprehension of complex code.
To mitigate the limitations, we propose CodeVisionary, the first LLM-based agent framework for evaluating LLMs in code generation. CodeVisionary consists of two stages: (1) Multiscore knowledge analysis stage, which aims to gather multisource and comprehensive domain knowledge by formulating and executing a stepwise evaluation plan. (2) Negotiation-based scoring stage, which involves multiple judges engaging in discussions to better comprehend the complex code and reach a consensus on the evaluation score. Extensive experiments demonstrate that CodeVisionary achieves the best performance for evaluating LLMs in code generation, outperforming the best baseline methods with average improvements of 0.202, 0.139, and 0.117 in Pearson, Spearman, and Kendall-Tau coefficients, respectively. Besides, CodeVisionary provides detailed evaluation reports, which assist developers in identifying shortcomings and making improvements. The resources of CodeVisionary are available at https://anonymous.4open.science/r/CodeVisionary."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Code Generation", "Evaluation", "Large Language Model"]
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
