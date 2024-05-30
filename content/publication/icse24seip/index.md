---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hawkeye: Change-targeted Testing for Android Apps based on Deep Reinforcement Learning"
authors: [admin, "Zhengwei Lv", "Jiarong Fu", "Jiayuan Liang", "Zhao Zhang", "Ajitha Rajan", "Ping Yang"]

date: 2024-04-12T00:00:00+01:00
# doi: "10.1007/978-3-030-16722-6_19"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of ICSE 2024 SEIP"
publication_short: "In proceedings of ICSE 2024 SEIP"

abstract: "Android Apps are frequently updated to keep up with changing user, hardware, and business demands. Ensuring the correctness of App updates through extensive testing is crucial to avoid potential bugs reaching the end user. Existing Android testing tools generate GUI events that focus on improving the test coverage of the entire App rather than prioritising updates and its impacted elements. Recent research has proposed change-focused testing but relies on random exploration to exercise the updates and impacted GUI elements that is ineffective and slow for large complex Apps with a huge input exploration space. At ByteDance, our established model-based GUI testing tool, Fastbot2, has been in successful deployment for nearly three years. Fastbot2 leverages event-activity transition models derived from past App explorations to achieve enhanced test coverage efficiently. A pivotal insight we gained is that the knowledge of event-activity transitions is equally valuable in effectively targeting changes introduced by App updates. This insight propelled our proposal for directed testing of App updates with Hawkeye. Hawkeye excels in prioritizing GUI actions associated with code changes through deep reinforcement learning from historical exploration data.

In our empirical evaluation, we rigorously compared Hawkeye with state-of-the-art tools like Fastbot2 and ARES. We utilized 10 popular open-source Apps and a notable commercial App for this evaluation. The results showcased that Hawkeye consistently outperforms Fastbot2 and ARES in generating GUI event sequences that effectively target changed functions, both in open-source and commercial App contexts.

In real-world industrial deployment, Hawkeye is seamlessly integrated into our development pipeline, performing smoke testing for merge requests in a complex commercial App. The positive feedback received from our App development teams further affirmed Hawkeye's ability in testing App updates effectively."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Software Testing", "AI2SE"]
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
