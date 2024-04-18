---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MUBot: Learning to Test Large-Scale Commercial Android Apps like a Human"
authors: ["Chao Peng",  "Zhao Zhang", "Zhengwei Lv", "Ping Yang"]
date: 2022-09-26T00:00:00+01:00
# doi: "10.1007/978-3-030-16722-6_19"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 38th International Conference on Software Maintenance and Evolution (ICSME 2022)"
publication_short: "In proceedings of ICSME 2022"

abstract: "Automated GUI testing has been playing a key role to uncover crashes to ensure the stability and robustness of Android apps. Recent research has proposed random, search-based and model-based testing techniques for GUI event generation. In industrial practices, different companies have developed various GUI exploration tools such as Facebook Sapienz, WeChat WeTest and ByteDance Fastbot to test their products. However, these tools are bound to their predefined GUI exploration strategies and lack of the ability to generate human-like actions to test meaningful scenarios. To address these challenges, Humanoid is the first Android testing tool that utilises deep learning to imitate human behaviours and achieves promising results over current model-based methods. However, we find some challenges when applying Humanoid to test our sophisticated commercial apps such as infinite loops and low test coverage. To this end, we performed the first case study on the performance of deep learning techniques using commercial apps to understand the underlying reason of the current weakness of this promising method. Based on our findings, we propose MUBot (Multi-modal User Bot) for human-like Android testing. Our empirical evaluation reveals that MUBot has better performance over Humanoid and Fastbot, our in-house testing tool on coverage achieved and bug-fixing rate on commercial apps."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Android Testing", "Graphical User Interface", "Deep Learning", "AI2SE"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: pdf/ICSME22B.pdf
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
