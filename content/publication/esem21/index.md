---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Testing Smart Contracts: Which Technique Performs Best?"
authors:
 - Sefa Akca
 - admin
 - Ajitha Rajan

date: 2021-10-11T00:00:00+01:00
doi: "10.1145/3475716.3475779"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-30T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 15th ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM 2021)"
publication_short: "In proceedings of ESEM 2021"

abstract: "Executing, verifying and enforcing credible transactions on permissionless blockchains is done using smart contracts. A key challenge with smart contracts is ensuring their correctness and security. Several test input generation techniques for detecting vulnerabilities in smart contracts have been proposed in the last few years. However,a comparison of proposed techniques to gauge their effectivenessis missing. This paper conducts an empirical evaluation of testing techniques for smart contracts. The testing techniques we evaluated are: (1) Blackbox fuzzing, (2) Adaptive fuzzing, (3) Coverage-guided fuzzing with an SMT solver and (4) Genetic algorithm. We do not consider static analysis tools, as several recent studies have assessed and compared effectiveness of these tools. We evaluate effectiveness of the test generation techniques using (1) Coverage achieved - we use four code coverage metrics targeting smart contracts, (2) Fault finding ability - using aritificially seeded and real security vulnerabilities of different types. We used two datasets in our evaluation - one with 1665 real smart contracts from Etherscan, and another with 90 real contracts with known vulnerabilities to assess fault finding ability. We find Adaptive fuzzing performs best in terms of coverage and fault finding over contractsin both datasets."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Ethereum", "Smart Contract", "Fault Seeding", "Test Generation", "Genetic Algorithm", "Fuzzing", "SMT Solving", "Software Testing"]
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
