---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Characterizing and Finding System Setting-Related Defects in Android Apps"
authors: ["Jingling Sun", "Ting Su", "Kai Liu", "Chao Peng", "Zhao Zhang", "Geguang Pu", "Tao Xie", "Zhendong Su"]
date: 2022-12-19T00:00:00+01:00
#doi: "10.1109/APSEC48747.2019.00071"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-30T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Software Engineering"
publication_short: "TSE"

abstract: "Android, the most popular mobile system, offers a number of user-configurable system settings (e.g., network, location, and permission) for controlling devices and apps. Even popular, well-tested apps may fail to properly adapt their behaviors to diverse setting changes, thus frustrating their users. However, there exists no effort to systematically investigate such defects. To this end, we conduct the first large-scale empirical study to understand and characterize these system setting-related defects(in short as “setting defects”), which reside in apps and are triggered by system setting changes. We devote substantial manual effort (over four person-months) to analyze 1,074 setting defects from 180 popular apps on GitHub. We investigate the impact, root causes, and consequences of these setting defects and their correlations. We find that (1) setting defects have a wide impact on apps’ correctness with diverse root causes, (2) the majority of these defects (≈70.7%) cause non-crashing (logic) failures, and (3) some correlations exist between the setting categories, root causes, and consequences. Motivated and informed by these findings, we propose two bug-finding techniques that can synergistically detect setting defects from both the GUI and code levels. Specifically, at the GUI level,we design and introduce setting-wise metamorphic fuzzing, the first automated dynamic testing technique to detect setting defects(causing crash and non-crashing failures, respectively) for Android apps. We implement this technique as an end-to-end, automatedGUI testing tool named SETDROID. At the code level, we distill two major fault patterns and implement a static analysis tool named SETCHECKER to identify potential setting defects. We evaluate SETDROID and SETCHECKER on 26 popular, open-source Android apps, and they find 48 unique, previously-unknown setting defects. To date, 35 have been confirmed and 21 have been fixed by app developers. We also apply SETDROID and SETCHECKER on five highly popular industrial apps, namely WeChat, QQMail, TikTok,CapCut, and Alipay HK, all of which each have billions of monthly active users. SETDROID successfully detects 17 previously unknown setting defects in these apps’ latest releases, and all defects have been confirmed and fixed by the app vendors. After that, we collaborate with ByteDance and deploy these two bug-finding techniques internally to stress-test TikTok, one of its major app products.Within a two-month testing campaign, SETDROID successfully finds 53 setting defects, and SETCHECKER finds 22 ones. So far, 59have been confirmed and 31 have been fixed. All these defects escaped from prior developer testing. By now, SETDROIDhas been integrated into ByteDance’s official app testing infrastructure named FASTBOT for daily testing. These results demonstrate the strong effectiveness and practicality of our proposed techniques."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Empirical study", "System Settings", "Android Apps", "GUI Testing", "Static Analysis"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: pdf/TSE22.pdf
url_code:
url_dataset:
url_poster:
url_project: https://github.com/setting-defect-fuzzing/home
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
