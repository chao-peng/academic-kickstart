---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Go-Oracle: Automated Test Oracle for Go Concurrency Bugs"
authors: ["Foivos Tsimpourlas", admin, "Carlos Rosuero", "Ping Yang", "Ajitha Rajan"]

date: 2024-12-11T00:00:00+01:00
doi: "10.48550/arXiv.2412.08061"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-15T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of The the International Symposium on Empirical Software Engineering and Measurement (ESEM 2025)"
publication_short: "In Proceedings of ESEM 2025"

abstract: "The Go programming language has gained significant traction for developing software, especially in various infrastructure systems. Nonetheless, concurrency bugs have become a prevalent issue within Go, presenting a unique challenge due to the language's dual concurrency mechanisms-communicating sequential processes and shared memory. Detecting concurrency bugs and accurately classifying program executions as pass or fail presents an immense challenge, even for domain experts. We conducted a survey with expert developers at Bytedance that confirmed this challenge. Our work seeks to address the test oracle problem for Go programs, to automatically classify test executions as pass or fail. This problem has not been investigated in the literature for Go programs owing to its distinctive programming model. Our approach involves collecting both passing and failing execution traces from various subject Go programs. We capture a comprehensive array of execution events using the native Go execution tracer. Subsequently, we preprocess and encode these traces before training a transformer-based neural network to effectively classify the traces as either passing or failing. The evaluation of our approach encompasses 8 subject programs sourced from the GoBench repository. These subject programs are routinely used as benchmarks in an industry setting. Encouragingly, our test oracle, Go-Oracle, demonstrates high accuracies even when operating with a limited dataset, showcasing the efficacy and potential of our methodology. Developers at Bytedance strongly agreed that they would use the Go-Oracle tool over the current practice of manual inspections to classify tests for Go programs as pass or fail."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Test Oracle", "Concurrency", "Go", "Neural Network"]
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
