---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CAT: Change-focused Android GUI Testing"
authors: ["Chao Peng", "Ajitha Rajan", "Tianqin Cai"]
date: 2021-09-27T00:00:00+01:00
# doi: "10.1007/978-3-030-16722-6_19"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 37th International Conference on Software Maintenance and Evolution (ICSME 2021)"
publication_short: "In proceedings of ICSME 2021"

abstract: "Android Apps are frequently updated, every couple of weeks, to keep up with changing user, hardware and business demands. Correctness of App updates is checked through extensive testing. Recent research has proposed tools for automated GUI event generation in Android Apps. These techniques, however, are not efficient at checking App updates as the generated GUI events do not prioritise updates, and instead explore other App behaviours. We address this need in this paper with CAT (Change-focused Android GUI Testing). For App updates, at the source code or GUI level, CAT performs change impact analysis to identify GUI elements affected by the update. CAT then generates GUI event sequences to interact with the affected GUI elements. Our empirical evaluations using 21 publicly available open source and 2 commercial Android Apps demonstrate that CAT is able to automatically identify GUI elements affected by App updates, generate and execute GUI event sequences focusing on change-affected GUI elements. Comparison with two popular GUI event generation tools, DroidBot and DroidMate, revealed that CAT was more effective at interacting with the change-affected GUI elements. Finally, CAT was able to detect previously unknown change-related bugs in two open source Apps. Developers of the commercial Apps found CAT was more effective than their in-house GUI testing tool in interacting with changed elements and faster at detecting seeded bugs."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Software Testing", "Android", "Graphical User Interface", "Program Analysis"]
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
