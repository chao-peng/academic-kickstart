---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "AEGIS: An Agent-based Framework for General Bug Reproduction from Issue Descriptions"
authors: ["Xinchen Wang", "Pengfei Gao", "Xiangxin Meng", admin, "Ruida Hu", "Yun Lin", "Cuiyun Gao"]

date: 2024-11-27T00:00:00+01:00
doi: "10.48550/arXiv.2411.18015"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In Companion Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE) 2025"
publication_short: "In Companion Proceedings of FSE 2205"

abstract: "In software maintenance, bug reproduction is essential for effective fault localization and repair. Manually writing reproduction scripts is a time-consuming task with high requirements for developers. Hence, automation of bug reproduction has increasingly attracted attention from researchers and practitioners. However, the existing studies on bug reproduction are generally limited to specific bug types such as program crashes, and hard to be applied to general bug reproduction. In this paper, considering the superior performance of agent-based methods in code intelligence tasks, we focus on designing an agent-based framework for the task. Directly employing agents would lead to limited bug reproduction performance, due to entangled subtasks, lengthy retrieved context, and unregulated actions. To mitigate the challenges, we propose an Automated gEneral buG reproductIon Scripts generation framework, named AEGIS, which is the first agent-based framework for the task. AEGIS mainly contains two modules: (1) A concise context construction module, which aims to guide the code agent in extracting structured information from issue descriptions, identifying issue-related code with detailed explanations, and integrating these elements to construct the concise context; (2) A FSM-based multi-feedback optimization module to further regulate the behavior of the code agent within the finite state machine (FSM), ensuring a controlled and efficient script generation process based on multi-dimensional feedback. Extensive experiments on the public benchmark dataset show that AEGIS outperforms the state-of-the-art baseline by 23.0% in F->P metric. In addition, the bug reproduction scripts generated by AEGIS can improve the relative resolved rate of Agentless by 12.5%."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Bug Reproduction", "Large Language Models", "Agents"]
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
