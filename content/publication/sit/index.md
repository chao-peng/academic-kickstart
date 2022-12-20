---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Automated Server Testing: an Industrial Experience Report"
authors: ["Chao Peng", "Yujun Gao", "Ping Yang"]
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

abstract: "A server API bug could have a huge impact on the operation of other servers and clients relying on that API, resulting in service downtime and financial losses. A common practice of server API testing inside enterprises is writing test inputs and assertions manually, and the test effectiveness depends largely on testers' carefulness, expertise and domain knowledge. Writing test cases for complicated business scenarios with multiple and ordered API calls is also a heavy task that requires a lot of human effort. In this paper, we present the design and deployment of SIT, a fully automated server reliability testing platform at ByteDance that provides capabilities including (1) traffic data generation based on combinatorial testing and fuzzing, (2) scenario testing for complicated business logics and (3) automated test execution with fault localisation in a controlled environment that does not affect online services. SIT has been integrated into the source control system and is triggered when new code change is submitted or configured as scheduled tasks. During the year of 2021, SIT blocked 434 valid issues before they were introduced into the production system."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Server Testing", "Traffic Record and Replay", "automated testing"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: pdf/ICSME22A.pdf
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
