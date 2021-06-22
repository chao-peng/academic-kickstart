---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SolAnalyser: A Framework for Analysing and Testing Smart Contracts"
authors: ["Sefa Akca", "Ajitha Rajan", "Chao Peng"]
date: 2019-09-30T00:00:00+01:00
doi: "10.1109/APSEC48747.2019.00071"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-30T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 2019 26th Asia-Pacific Software Engineering Conference (APSEC)"
publication_short: "In proceedings of APSEC 2019"

abstract: "Executing, verifying and enforcing credible transactions on permissionless blockchains is done using smart contracts. Smart contracts define and execute crucial agreements, and attacks exploiting their vulnerabilities can lead to huge losses, like the failure of the DAO smart contract that resulted in 50 million US Dollars worth of losses. A key challenge with smart contracts is ensuring their correctness and security.\n\nTo address this challenge, we present a fully automated technique, SolAnalyser, for vulnerability detection over Solidity smart contracts that uses both static and dynamic analysis. Analysis techniques for smart contracts in the literature rely on static analysis with a high rate of false positives or lack support for vulnerabilities like out of gas, unchecked send, timestamp dependency. We instrument the original smart contract with property checks and use dynamic analysis to tackle this problem. Our tool, SolAnalyser, supports automated detection of 8 different vulnerability types that currently lack wide support in existing tools, and can easily be extended to support other types. We also implemented a fault seeding tool that injects different types of vulnerabilities in smart contracts. We use the mutated contracts for assessing the effectiveness of different analysis tools.\n\nOur experiment uses 1838 real contracts from which we generate 12866 mutated contracts by artificially seeding 8 different vulnerability types. We evaluate the effectiveness of our technique in revealing the seeded vulnerabilities and compare against five existing popular analysis tools – Oyente, Securify, Maian, SmartCheck and Mythril. This is the first large scale evaluation of existing tools that compares their effectiveness by running them on a common set of contracts. We find that our technique outperforms all five existing tools in supporting detection of all 8 vulnerability types and in achieving higher precision and recall rate. SolAnalyser was also faster in analysing the different vulnerabilities than any of the existing tools in our experiment. Among existing tools, Securify achieved high precision in detecting integer overflow, underflow, and division by zero but had poor recall rates."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Blockchain", "Smart Contract", "Testing", "Static Analysis", "Assertions", "Fault Seeding"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: pdf/solanalyser.pdf
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
