---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Fastbot2: Reusable Automated Model-based GUI Testing for Android Enhanced by Reinforcement Learning"
authors: ["Zhengwei Lv", admin, "Zhao Zhang", "Ting Su", "Kai Liu", "Ping Yang"]

date: 2022-10-10T00:00:00+01:00
doi: "10.1145/3551349.3559505"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 37th IEEE/ACM International Conference on Automated Software Engineering (ASE 2022)"
publication_short: "In proceedings of ASE 2022"

abstract: "In the industrial setting, mobile apps undergo frequent updates to catch up with the changing real-world requirements. It leads to the strong practical demands of continuous testing, i.e., obtaining quick feedback on app quality during development. However, existing automated GUI testing techniques fall short in this scenario as they simply run an app version from scratch and do not reuse the knowledge from previous testing runs to accelerate the testing cycle. To fill this important gap, we introduce a reusable automated model-based GUI testing technique. Our key insight is that the knowledge of event-activity transitions from the previous testing runs, i.e., executing which events can reach which activities, is valuable for guiding the follow-up testing runs to quickly cover major app functionalities. To this end, we propose (1) a probabilistic model to memorize and leverage this knowledge during testing, and (2) design a model-based guided testing strategy (enhanced by a reinforcement learning algorithm), to achieve faster-and-higher coverage testing. We implemented our technique as an automated testing tool named Fastbot2. Our evaluation on the two popular industrial apps (with billions of user installations) from ByteDance, Douyin and Toutiao, shows that Fastbot2 outperforms the state-of-the-art testing tools (Monkey, APE and Stoat) in both activity coverage and fault detection in the context of continuous testing. To date, Fastbot2 has been deployed in the CI pipeline at ByteDance for nearly two years, and 50.8% of the developer-fixed crash bugs were reported by Fastbot2, which significantly improves app quality. Fastbot2 has been made publicly available to benefit the community at: https://github.com/bytedance/Fastbot_Android. To date, it has received 500+ stars on GitHub and been used by many app vendors and individual developers to test their apps."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Software Testing", "AI2SE"]
categories: []
featured: true

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
url_project: https://github.com/bytedance/Fastbot_Android
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
