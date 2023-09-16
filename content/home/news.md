+++
widget = "blank"
headless = true
weight = 20
title = "News"

[design]
    columns = 2

+++
- **8 Aug 2023** Our paper *[Effective Concurrency Testing for Go via Directional Primitive-constrained Interleaving Exploration](publication/gopie)* is accepted by ASE 2023.
- **31 Jul 2023** Our paper *[AG3: Automated Game GUI Text Glitch Detection based on Computer Vision](publication/ag3)* is accepted by the Industry Track of FSE 2023.
- **19 May 2022** Invited to give a talk on mobile app testing at University of Edinburgh.
- **28 Apr 2023** Our paper *[NxtUnit: Automated Unit Test Generation for Go](publication/nxtunit)* is accepted by the Industry Track of EASE 2023.
- **19 Dec 2022** Our paper *[Characterizing and Finding SystemSetting-Related Defects in Android Apps](publication/tse22/)* is accepted by TSE.
- **29 Sep 2022** Invited to give a talk on mobile app testing at ECNU.
- **8 Aug 2022** Our paper *[Fastbot2: Reusable Automated Model-based GUI Testing for Android Enhanced by Reinforcement Learning](publication/fastbot2/)* is accepted by the Industry Track of ASE 2022.
- **22 Jun 2022** Our papers *[MUBot: Learning to Test Large-Scale Commercial Android Apps like a Human](publication/mubot/)* and *[Automated Server Testing: an Industrial Experience Report](publication/sit/)* are accepted by the Industry Track of ICSME 2022.

<div style="display:none" id="more_news">

- **05 Jul 2021** Joined ByteDance as a Tech Expert / Senior Researcher within the Quality Lab
- **30 Jun 2021** Our paper *[Testing Smart Contracts: Which Technique Performs Best?](https://dl.acm.org/doi/10.1145/3475716.3475779)* is accepted by ESEM 2021.
- **15 Jun 2021** Our paper *[CAT: Change-focused Android GUI Testing](https://ieeexplore.ieee.org/abstract/document/9609107/)* is accepted by ICSME 2021.
- **28 Dec 2020** Started project with ByteDance on Android testing.
- **23 Nov 2020** Started part-time programming language research intern at Huawei Edinburgh Research Centre mentored by Dan Ghica, the PL group lead.
- **20 Jan 2020** Our paper *[Automated Test Generation for OpenCL Kernels Using Fuzzing and Constraint Solving](https://dl.acm.org/doi/abs/10.1145/3366428.3380768)* is accepted by PPoPP’s GPGPU Workshop 2020.
- **28 Oct 2019** Joined Huawei London Research Centre as a Mobile GPU Intern mentored by Graham Connor, the Chief GPU Scientist.
- **30 Sep 2019** Our papers *[SIF: A Framework for Solidity Contract Instrumentation and Analysis](https://ieeexplore.ieee.org/document/8945726)* and *[SolAnalyser: A Framework for Analysing and Testing Smart Contracts](https://ieeexplore.ieee.org/document/8945725)* are accepted by APSEC 2019.
- **31 Jul 2019** We are excited to release **[SIF](https://github.com/chao-peng/Sif)** - a code analysis and instrumentation framework for Solidity smart contracts.
- **30 May 2019** My PhD research proposal *[On the Correctness of GPU programs](https://chao-peng.github.io/publication/isstads/)* is accepted by ISSTA 2019 Doctoral Symposium.
- **24 Jan 2019** Our paper *[CLTestCheck: Measuring Test Effectiveness for GPU Kernels](https://chao-peng.github.io/publication/cltestcheck/)* is accepted by FASE 2019.
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
