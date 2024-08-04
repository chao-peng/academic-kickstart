---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "RepoSim: Evaluating Prompt Strategies for Code Completion via User Behavior Simulation"
authors: [admin, "Qinyun Wu", "Jiangchao Liu", "Jierui Liu", "Bo Jiang", "Mengqian Xu", "Yinghao Wang", "Xia Liu", "Ping Yang"]

date: 2024-10-27T00:00:00+01:00
# doi: "10.1007/978-3-030-16722-6_19"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering (ASE 2024)"
publication_short: "In proceedings of ASE 2024"

abstract: "Large language models (LLMs) have revolutionized code completion tasks. IDE plugins such as Copilot can generate code recommendations, saving developers significant time and effort. However, current evaluation methods for code completion are limited by their reliance on static code benchmarks, which do not consider human interactions and evolving repositories. This paper proposes RepoSim, a novel benchmark designed to evaluate code completion tasks by simulating the evolving process of repositories and incorporating user behaviors. RepoSim leverages data from an IDE plugin, by recording and replaying user behaviors to provide a realistic programming context for evaluation. This allows for the assessment of more complex prompt strategies, such as utilizing recently visited files and incorporating user editing history. Additionally, RepoSim proposes a new metric based on users' acceptance or rejection of predictions, offering a user-centric evaluation criterion. Our preliminary evaluation demonstrates that incorporating users' recent edit history into prompts significantly improves the quality of LLM-generated code, highlighting the importance of temporal context in code completion. RepoSim represents a significant advancement in benchmarking tools, offering a realistic and user-focused framework for evaluating code completion performance."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Software Testing", "Code Completion" , "LLM4Code", "AI4SE"]
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
