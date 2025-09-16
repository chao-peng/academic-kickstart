---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tool-integrated Reinforcement Learning for Repo Deep Search"
authors: ["Zexiong Ma", admin, "Qunhong Zeng", "Pengfei Gao", "Yanzhen Zou", "Bing Xie"]

date: 2025-08-05T00:00:00+01:00
doi: "10.48550/arXiv.2508.03012"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-08-05T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: "Issue localization, the process of identifying code locations that need modification to resolve software issues, is a critical yet challenging task in software development. The semantic gap between natural language issue descriptions and faulty code requires complex multi-hop reasoning through code dependencies. Existing LLM-based agents attempt to address this by integrating repository retrieval tools. However, this transforms issue localization into a demanding task we call Repo Deep Search, which requires the LLM to effectively utilize various repository retrieval tools throughout a multi-step reasoning and navigation process. To tackle this challenge, we present ToolTrain, a two-stage tool-integrated training framework combining rejection-sampled supervised fine-tuning and tool-integrated reinforcement learning to enhance LLMs' ability to use retrieval tools for issue localization. Experimental results show that ToolTrain-trained models achieve state-of-the-art performance, with our 32B model even surpassing Claude-3.7 on function-level localization. The results also show that improved localization performance translates to better end-to-end issue resolution performance. This further demonstrates that training for issue localization is a viable and effective strategy for improving automated software development."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Bug Fixing", "Large Language Models", "Automated Program Repair", "Agents"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2508.03012
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
