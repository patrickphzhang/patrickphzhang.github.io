---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Architecture, University of Chinese Academy of Sciences, 2024
* M.S. in Computer Architecture, University of Chinese Academy of Sciences, 2019
* B.S. in Computer Science and Technology, Shandong University, 2017

Work experience
======
* 2024: Tencent Tech Expert
  * WeChat Group
  * Duties includes: program profiling, profile-guided optimization.

* 2023: Research Assistant
  * Zhongguancun Laboratory
  * Duties included: eBPF security research
  * Supervisor: Professor Chenggang Wu, Associate Professor Zhe Wang
  
Skills
======
* Compiler: Proficient in LLVM compiler architecture, middle-end and back-end programming, including program analysis, code transformation, and reinforcement. 
* Kernel: Experienced in kernel bypassing, eBPF, Linux kernel analysis, operating system development, and kernel debugging.
* Reverse Engineering: Skilled in binary code diffing and rewriting techniques.
* Others: Familiar with Intel/ARM hardware characteristics, Trusted Execution Environment principles and design, and fuzz testing.
* Programming Languages: C / C++ / Python / JavaScript / Java / Shell

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
