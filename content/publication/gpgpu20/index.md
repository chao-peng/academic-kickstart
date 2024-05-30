---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Automated Test Generation for OpenCL Kernels Using Fuzzing and Constraint Solving"
authors: [admin, "Ajitha Rajan"]
date: 2020-02-23T00:00:00+01:00
doi: "10.1145/3366428.3380768"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-23T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In proceedings of the 13th Annual Workshop on General Purpose Processing using Graphics Processing Unit (GPGPU 2020)"
publication_short: "In proceedings of GPGPU 2020 (workshop of PPoPP 2020)"

abstract: "Graphics Processing Units (GPUs) are massively parallel processors offering performance acceleration and energy efficiency unmatched by current processors (CPUs) in computers. These advantages along with recent advances in the programmability of GPUs have made them attractive for general-purpose computations. Despite the advances in programmability, GPU kernels are hard to code and analyse due to the high complexity of memory sharing patterns, striding patterns for memory accesses, implicit synchronisation, and combinatorial explosion of thread interleavings. Existing few techniques for testing GPU kernels use symbolic execution for test generation that incur a high overhead, have limited scalability and do not handle all data types.\n\nWe propose a test generation technique for OpenCL kernels that combines mutation-based fuzzing and selective constraint solving with the goal of being fast, effective and scalable. Fuzz testing for GPU kernels has not been explored previously. Our approach for fuzz testing randomly mutates input kernel argument values with the goal of increasing branch coverage. When fuzz testing is unable to increase branch coverage with random mutations, we gather path constraints for uncovered branch conditions and invoke the Z3 constraint solver to generate tests for them.\n\nIn addition to the test generator, we also present a schedule amplifier that simulates multiple work-group schedules, with which to execute each of the generated tests. The schedule amplifier is designed to help uncover inter work-group data races. We evaluate the effectiveness of the generated tests and schedule amplifier using 217 kernels from open source projects and industry standard benchmark suites measuring branch coverage and fault finding. We find our test generation technique achieves close to 100% coverage and mutation score for majority of the kernels. Overhead incurred in test generation is small (average of 0.8 seconds). We also confirmed our technique scales easily to large kernels, and can support all OpenCL data types, including complex data structures."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Software Testing", "GPU", "OpenCL", "Test Case Generation", "Fuzz Testing", "Constraint Solving", "Data Race"]
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
url_code: https://github.com/chao-peng/CLFuzz
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
