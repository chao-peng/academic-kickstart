---
# Display name
title: Chao Peng

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: PhD Candidate in Informatics

# Organizations/Affiliations
organizations:
- name: Laboratory for Foundations of Computer Science
  url: "http://wcms.inf.ed.ac.uk/lfcs"
- name: School of Informatics
  url: "https://www.ed.ac.uk/informatics"
- name: University of Edinburgh
  url: "https://www.ed.ac.uk"

# Short bio (displayed in user profile at end of posts)
bio: My research interests include Software Testing, Blockchain Security and Programming Languages.

interests:
- Software Testing
- GPGPU
- Smart Contract Security
- Programming Languages

education:
  courses:
  - course: PhD in Informatics
    institution: University of Edinburgh, UK
    year: In Progress
  - course: MSc in High Performance Computing and Data Science
    institution: University of Edinburgh, UK
    year: 2017
  - course: BEng in Computer Science and Technology
    institution: Xuzhou University of Technology, China
    year: 2016

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: cv
  icon_pack: ai
  link: 'cv-chaopeng-en.pdf'  # For a direct email link, use "mailto:test@example.org".
- icon: linkedin-in
  icon_pack: fab
  link: https://www.linkedin.com/in/chao-peng-uoe/
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.co.uk/citations?user=HoVGmNMAAAAJ
- icon: github
  icon_pack: fab
  link: https://github.com/chao-peng
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/clarkcp93
- icon: instagram
  icon_pack: fab
  link: https://www.instagram.com/chao_peng_/
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Researchers
- Visitors
---

Chao Peng （彭péng, 超chāo） is a PhD candidate at the [Laboratory for Foundations of Computer Science (LFCS)](http://wcms.inf.ed.ac.uk/lfcs), [School of Informatics](https://www.ed.ac.uk/informatics), [The University of Edinburgh](https://www.ed.ac.uk/). He holds an MSc in High Performance Computing with Data Science from the University of Edinburgh and a BEng in Computer Science and Technology from Xuzhou University of Technology. During his MSc, he was a member of Team EPCC for the International Supercomputing Conference Student Cluster Competition.

His research interest lies in the area of massively parallel architectures and programming. He is currently doing research in defining code coverage metrics for GPU programs and automated test case generation, reduction and execution. His supervisor is [Dr. Ajitha Rajan](http://homepages.inf.ed.ac.uk/arajan).

<!--
Email:
```c
printf("Email: %s%c%s\n", "chao.peng", 0x40, "ed.ac.uk");
printf("Permanent Email: %s%c%s\n", "xzchao93", 0x40, "gmail.com");
```
<button id='targetButton' onclick="targetField = document.getElementById('display');targetButton = document.getElementById('targetButton');if (targetField.innerHTML=='') {var first='Email: ' + 'chao.peng'+'@'+'ed.ac.uk';var second='Permanent Email: ' + 'xzchao93' + '@' + 'gmail.com'; targetField.innerHTML=first + '<br>' + second;targetButton.innerHTML='Hide Result'} else {targetField.innerHTML='';targetButton.innerHTML='Display Result'}">Display Result</button><br>
-->

<button id='btnShowEmail' onclick="targetField = document.getElementById('display'); btnShowEmail = document.getElementById('btnShowEmail'); var userName1 = 'chao.peng', domain1 = 'ed.ac.uk', userName2 = 'xzchao93', domain2 = 'gmail.com'; var first=`Email: ${userName1}@${domain1}`;var second=`Permanent Email: ${userName2}@${domain2}`; targetField.innerHTML=first + '<br>' + second; btnShowEmail.style.display = 'none';">Show Email Addresses</button><br>
<span id="display"></span>
