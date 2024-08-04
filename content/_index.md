---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      text: |-
        - **4 Aug 2024** Our paper *[RepoSim: Evaluating Prompt Strategies for Code Completion via User Behavior Simulation](publication/ase24nier)* is accepted by the NIER track of ASE 2024.
        - **14 Jun 2024** I am invited to join the organisation committee of the [6th International Workshop on Automated Program Repair (APR 2025)](https://program-repair.org/workshop-2025/), co-located with ICSE 2025. Please consider submitting your paper to the workshop!
        - **18 Apr 2024** Our paper *[Neat: Mobile App Layout Similarity Comparison based on Graph Convolutional Networks](publication/fse24)* is accepted by the Industry Track of FSE 2024.
        - **21 Dec 2023** Our paper *[Hawkeye: Change-targeted Testing for Android Apps based on Deep Reinforcement Learning](publication/icse24seip)* is accepted by the SEIP track of ICSE 2024.
        - **8 Aug 2023** Our paper *[Effective Concurrency Testing for Go via Directional Primitive-constrained Interleaving Exploration](publication/ase23)* is accepted by ASE 2023.
        - **31 Jul 2023** Our paper *[AG3: Automated Game GUI Text Glitch Detection based on Computer Vision](publication/fse23)* is accepted by the Industry Track of FSE 2023.
        <div style="display:none" id="more_news">

        - **19 May 2022** Invited to give a talk on mobile app testing at University of Edinburgh.
        - **28 Apr 2023** Our paper *[NxtUnit: Automated Unit Test Generation for Go](publication/ease23)* is accepted by the Industry Track of EASE 2023.
        - **19 Dec 2022** Our paper *[Characterizing and Finding SystemSetting-Related Defects in Android Apps](publication/tse22/)* is accepted by TSE.
        - **29 Sep 2022** Invited to give a talk on mobile app testing at ECNU.
        - **8 Aug 2022** Our paper *[Fastbot2: Reusable Automated Model-based GUI Testing for Android Enhanced by Reinforcement Learning](publication/ase22/)* is accepted by the Industry Track of ASE 2022.
        - **22 Jun 2022** Our papers *[MUBot: Learning to Test Large-Scale Commercial Android Apps like a Human](publication/icsme22b/)* and *[Automated Server Testing: an Industrial Experience Report](publication/icsme22a/)* are accepted by the Industry Track of ICSME 2022.
        - **05 Jul 2021** Joined ByteDance as a Tech Expert / Senior Researcher within the Quality Lab
        - **30 Jun 2021** Our paper *[Testing Smart Contracts: Which Technique Performs Best?](https://dl.acm.org/doi/10.1145/3475716.3475779)* is accepted by ESEM 2021.
        - **15 Jun 2021** Our paper *[CAT: Change-focused Android GUI Testing](https://ieeexplore.ieee.org/abstract/document/9609107/)* is accepted by ICSME 2021.
        - **28 Dec 2020** Started project with ByteDance on Android testing.
        - **23 Nov 2020** Started part-time programming language research intern at Huawei Edinburgh Research Centre mentored by Dan Ghica, the PL group lead.
        - **20 Jan 2020** Our paper *[Automated Test Generation for OpenCL Kernels Using Fuzzing and Constraint Solving](https://dl.acm.org/doi/abs/10.1145/3366428.3380768)* is accepted by PPoPP’s GPGPU Workshop 2020.
        - **28 Oct 2019** Joined Huawei London Research Centre as a Mobile GPU Intern mentored by Graham Connor, the Chief GPU Scientist.
        - **30 Sep 2019** Our papers *[SIF: A Framework for Solidity Contract Instrumentation and Analysis](https://ieeexplore.ieee.org/document/8945726)* and *[SolAnalyser: A Framework for Analysing and Testing Smart Contracts](https://ieeexplore.ieee.org/document/8945725)* are accepted by APSEC 2019.
        - **31 Jul 2019** We are excited to release **[SIF](https://github.com/chao-peng/Sif)** - a code analysis and instrumentation framework for Solidity smart contracts.
        - **30 May 2019** My PhD research proposal *[On the Correctness of GPU programs](publication/issta19ds/)* is accepted by ISSTA 2019 Doctoral Symposium.
        - **24 Jan 2019** Our paper *[CLTestCheck: Measuring Test Effectiveness for GPU Kernels](publication/fase19/)* is accepted by FASE 2019.
        - **01 Sep 2017** Started my PhD at University of Edinburgh with Dr. Ajitha Rajan fully funded by School of Informatics Scholarship.
        - **17 Nov 2016** Our Team EPCC selected to participate in the final round of the ISC Student Cluster Competition.

        </div>
        <script>
            function handleNews() {
                button_more = document.getElementById("button_more");
                news = document.getElementById("more_news");
                if (button_more.innerHTML == "More..") {
                    button_more.innerHTML = "Hide";
                    news.style.display="block";
                } else {
                    button_more.innerHTML = "More..";
                    news.style.display="none";
                }
            }
        </script>
        <u><a onclick="handleNews()" id="button_more">More..</a></u>

    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      text: |-
        {{% callout note %}}
        [See All publications >](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: service
    content:
      title: Service
      text: |-
        <table>
          <tbody>
            <tr>
              <td><b>Organising Committee</b></td>
              <td><a href='https://program-repair.org/workshop-2025/', target='_blank'>APR 2025 (Workshop with ICSE 2025)</a></td>
            </tr>
            <tr>
              <td><b>PC Member (Research/Technical Track)</b></td>
              <td>FSE 2025, MSR 2023(Junior PC), A-Mobile 2022, PRDC 2022</td>
            </tr>
            <tr>
              <td><b>PC Member (Industry Track)</b></td>
              <td>ISSRE 2024, APSEC 2024, MSR 2024</td>
            </tr>
            <tr>
              <td><b>PC Member (Artifact Evaluation)</b></td>
              <td>OSDI 2022, USENIX ATC 2022, ISSTA 2022, 2021, 2020</td>
            </tr>
            <tr>
              <td><b>Reviewer</b></td>
              <td>TOSEM, TSE, STVR</td>
            </tr>
            <tr>
              <td><b>Sub-reviewer</b></td>
              <td>ICSE 2019 Software Engineering in Practice Track</td>
            </tr>
            <tr>
              <td><b>Student Volunteer</b></td>
              <td>PLDI 2020, ISSTA 2019, ETAPS 2019</td>
            </tr>
          </tbody>
        </table>
    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-
        **[Part-time Postgraduate Student Mentor]** School of Computer Science, Fudan University. Mar 2022 - Present

        **[Sub-supervisor]** MSc Projects. School of Informatics, the University of Edinburgh. Apr 2018 - Aug 2018, Apr 2019 - Aug 2019

        **[Teaching Assistant, Tutor and Marker]** Software Testing. School of Informatics, the University of Edinburgh. Jan 2018 - Apr 2018, Jan 2019 - Apr 2019, Jan 2021 - Apr 2021

        **[Marker]** Computer Programming Skills and Concepts. School of Informatics, the University of Edinburgh. Nov 2017 - Dec 2017, Dec 2018 - Jan 2019

        **[Demonstrator]** Introduction to Java Programming. School of Informatics, the University of Edinburgh. Sep 2017 - Dec2017, Sep 2018 - Dec 2018

    design:
      columns: '2'
  - block: markdown
    id: awards
    content:
      title: Awards
      text: |-
        ### Scholarship
        - School of Informatics Scholarship (fully-funded PhD scholarship)
        - Outstanding Graduate Scholarship at Xuzhou University of Technology
        - China National Scholarship of 2014⁄15 Academic Year
        - China National Encouragement Scholarship of 2013⁄14 Academic Year
        - China National Scholarship of 2012⁄13 Academic Year
        ### Honours
        - Spot Bonus at ByteDance
        - Nominee for Teaching Awards: Best Student Who Tutors Award
        - Certificate of Achievement for Participating in the 6th Annual HPCAC Student Cluster Competition
        - Top Ten Role Models of Study in Xuzhou University of Technology
        - Excellent Graduate of Xuzhou University of Technology
        - Jiangsu Province-Level Excellent Student Cadre
    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Researcher
          company: ByteDance
          company_url: 'https://www.bytedance.com'
          company_logo: ''
          location: Beijing, China
          date_start: '2021-12-01'
          date_end: ''
          description: |2-
              LLM4SE | AI IDE | University Collaboration
        - title: '[Internship] Programming Language Research Intern'
          company: Huawei Edinburgh Research Centre
          company_url: ''
          company_logo: ''
          location: Edinburgh, UK
          date_start: '2020-11-23'
          date_end: '2021-06-22'
          description: |2-
            * Project: Testing and benchmarking for compilers
            * Mentor: Dan Ghica (PL Group Lead)
        - title: '[Internship] Mobile GPU Research Intern'
          company: Huawei London Research Centre
          company_url: ''
          company_logo: ''
          location: London, UK
          date_start: '2019-10-28'
          date_end: '2020-02-28'
          description: |2-
            * Micro benchmarking for mobile GPUs
            * Mentor: Graham Connor (Chief GPU Scientist)
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Extra-Curricular & Volunteer Activities'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          organization: "Edinburgh International Science Festival"
          organization_url: "https://www.sciencefestival.co.uk/"
          title: "Volunteer and Demonstrator"
          url: ""
          certificate_url: ""
          date_start: "2017-04-13"
          date_end: "2017-04-15"
          description: ""
        - certificate_url: ''
          organization: "18th Sports Meeting of Jiangsu Province, China"
          organization_url: ""
          title: "Volunteer Manager"
          url: ""
          certificate_url: ""
          date_start: "2013-09-01"
          date_end: "2014-09-30"
          description: ""
          url: ''
        - certificate_url: ''
          organization: "Student Union of Department of Information & Electrical Engineering, Xuzhou University of Technology"
          organization_url: ""
          title: "President of Student Union"
          url: ""
          certificate_url: ""
          date_start: "2014-12-01"
          date_end: "2015-12-01"
          description: ""
    design:
      columns: '2'
  - block: markdown
    content:
      title: ''
      text: |-
        <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=500&t=n&d=E9TlfkNpIanMxOr8TG2ZNRhIVJYur9Dih6YZSxVVt98'></script>

---
