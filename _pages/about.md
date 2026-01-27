---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD student in [ZJUNLP](https://zjunlp.github.io/) group from Zhejiang University, advised by Prof. [Huajun Chen](https://person.zju.edu.cn/en/huajun) and Prof. [Ningyu Zhang](https://person.zju.edu.cn/en/ningyu). Currently, I am a visiting researcher at [UCL AI Center](https://www.ucl.ac.uk/engineering/research/centres-institutes-and-labs/ucl-centre-artificial-intelligence) supervised by Prof. [Emine Yilmaz](https://sites.google.com/site/emineyilmaz/). I used to intern at Alibaba Tongyi Lab [DeepResearch Team](https://tongyi-agent.github.io/about/), mentored by [Yong Jiang](https://jiangyong.site/) and [Fei Huang](https://sites.google.com/view/fei-huang). During my undergraduate studies, I interned at [BDBC](http://bdbc.buaa.edu.cn/?lang=zh) in Beihang University, supervised by Prof. [Richong Zhang](http://act.buaa.edu.cn/zhangrc). Now, my research interests focus on Large Language Models, AI Agents, and their applications.

**My research is supported by the CIE-Tencent Doctoral Research Incentive Program (中国电子学会-腾讯博士生科研激励计划). Many thanks!**




# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Four papers has been accepted by ICLR 2026. See you in Rio de Janeiro, Brazil🇧🇷!
- *2025.05*: &nbsp;🎉🎉 Four papers has been accepted by ACL 2025. See you in Vienna, Austria🇦🇹!
- *2024.09*: &nbsp;🎉🎉 One paper has been accepted by ICLR 2025. See you in Singapore🇸🇬!

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/datamind.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Scaling Generalist Data-Analytic Agents](https://www.arxiv.org/abs/2509.25084)

**Shuofei Qiao**, Yanqiu Zhao, Zhisong Qiu, Xiaobin Wang, Jintian Zhang, Zhao Bin, Ningyu Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen

[**Project Page**](https://github.com/zjunlp/DataMind) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR: A scalable data synthesis and agent training recipe designed to build generalist data-analytic agents.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/DataMind)](https://github.com/zjunlp/DataMind) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/knowself.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agentic Knowledgeable Self-awareness](https://arxiv.org/abs/2504.03553)

**Shuofei Qiao**, Zhisong Qiu, Baochang Ren, Xiaobin Wang, Xiangyuan Ru, Ningyu Zhang, Xiang Chen, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen

[**Project Page**](https://github.com/zjunlp/KnowSelf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR: A data-centric approach that applies agents with knowledgeable self-awareness like humans.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/KnowSelf)](https://github.com/zjunlp/KnowSelf) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/worfbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Benchmarking Agentic Workflow Generation](https://arxiv.org/abs/2410.07869)

**Shuofei Qiao**, Runnan Fang, Zhisong Qiu, Xiaobin Wang, Ningyu Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen

[**Project Page**](https://zjunlp.github.io/project/WorFBench/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR: A unified agentic workflow generation benchmark with multi-faceted scenarios and intricate graph workflow structures.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/WorfBench)](https://github.com/zjunlp/WorfBench) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/wkm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agent Planning with World Knowledge Model](https://arxiv.org/abs/2405.14205)

**Shuofei Qiao**, Runnan Fang, Ningyu Zhang, Yuqi Zhu, Xiang Chen, Shumin Deng, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen

[**Project Page**](https://zjunlp.github.io/project/WKM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR: We introduce parametric World Knowledge Model (WKM) which provides global prior task knowledge and local dynamic state knowledge to facilitate agent planning.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/WKM)](https://github.com/zjunlp/WKM) 🌟
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/autoact.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoAct: Automatic Agent Learning from Scratch for QA via Self-Planning](https://arxiv.org/abs/2401.05268)

**Shuofei Qiao**, Ningyu Zhang, Runnan Fang, Yujie Luo, Wangchunshu Zhou, Yuchen Eleanor Jiang, Chengfei Lv, Huajun Chen

[**Project Page**](https://zjunlp.github.io/project/AutoAct/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR:  We introduce AutoAct, an automatic agent learning framework for QA that does not rely on large-scale annotated data and synthetic trajectories from closed-source models.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/AutoAct)](https://github.com/zjunlp/AutoAct) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2024</div><img src='images/trice.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Making Language Moldels Better Tool Learners with Execution Feedback](https://arxiv.org/abs/2305.13068)

**Shuofei Qiao**, Honghao Gui, Chengfei Lv, Qianghuai Jia, Huajun Chen, Ningyu Zhang

[**Project Page**](https://zjunlp.github.io/project/TRICE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR: We propose an approach to learn through feedback derived from tool execution, thereby learning when and how  to use tools effectively.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/TRICE)](https://github.com/zjunlp/TRICE) 🌟
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023</div><img src='images/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning with Language Model Prompting: A Survey](https://arxiv.org/abs/2212.09597)

**Shuofei Qiao**, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen

[**Paper List**](https://github.com/zjunlp/Prompt4ReasoningPapers) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- TL;DR: A survey for language model reasoning with prompting.
- Github Stars: [![](https://img.shields.io/github/stars/zjunlp/Prompt4ReasoningPapers)](https://github.com/zjunlp/Prompt4ReasoningPapers) 🌟
</div>
</div>

- `arXiv 2026` [Aligning Agentic World Models via Knowledgeable Experience Learning](https://arxiv.org/abs/2601.13247). Baochang Ren, Yunzhi Yao, Rui Sun, **Shuofei Qiao**, Ningyu Zhang, Huajun Chen.
- `ICLR 2026` [InnoGym: Benchmarking the Innovation Potential of AI Agents](https://arxiv.org/abs/2512.01822). Jintian Zhang, Kewei Xu, Jingsheng Zheng, Zhuoyun Yu, Yuqi Zhu, Yujie Luo, Lanning Wei, **Shuofei Qiao**, Lun Du, Da Zheng, Shumin Deng, Huajun Chen, Ningyu Zhang.
- `ICLR 2026` [LightMem: Lightweight and Efficient Memory-Augmented Generation](https://arxiv.org/abs/2510.18866). Jizhan Fang, Xinle Deng, Haoming Xu, Ziyan Jiang, Yuqi Tang, Ziwen Xu, Shumin Deng, Yunzhi Yao, Mengru Wang, **Shuofei Qiao**, Huajun Chen, Ningyu Zhang.
- `ICLR 2026` [Towards Personalized Deep Research: Benchmarks and Evaluations](https://arxiv.org/abs/2509.25106). Yuan Liang, Jiaxian Li, Yuqing Wang, Piaohong Wang, Motong Tian, Pai Liu, **Shuofei Qiao**, Runnan Fang, He Zhu, Ge Zhang, Minghao Liu, Yuchen Eleanor Jiang, Ningyu Zhang, Wangchunshu Zhou.
- `arXiv 2025` [OceanGym: A Benchmark Environment for Underwater Embodied Agents](https://arxiv.org/abs/2509.26536). Yida Xue, Mingjun Mao, Xiangyuan Ru, Yuqi Zhu, Baochang Ren, **Shuofei Qiao**, Mengru Wang, Shumin Deng, Xinyu An, Ningyu Zhang, Ying Chen, Huajun Chen.
- `arXiv 2025` [KnowRL: Exploring Knowledgeable Reinforcement Learning for Factuality](https://arxiv.org/abs/2506.19807). Baochang Ren, **Shuofei Qiao**, Da Zheng, Huajun Chen, Ningyu Zhang.
- `AAAI 2026` [Why do open-source llms struggle with data analysis? a systematic empirical study](https://arxiv.org/abs/2506.19794). Yuqi Zhu, Yi Zhong, Jintian Zhang, Ziheng Zhang, **Shuofei Qiao**, Yujie Luo, Lun Du, Da Zheng, Ningyu Zhang, Huajun Chen. **Oral.**
- `EMNLP 2025` [LightThinker: Thinking Step-by-Step Compression](https://arxiv.org/abs/2502.15589). Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, **Shuofei Qiao**, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang. **Oral.**
- `ACL 2025` [SynWorld: Virtual Scenario Synthesis for Agentic Action Knowledge Refinement](https://arxiv.org/abs/2504.03561). Runnan Fang, Xiaobin Wang, Yuan Liang, **Shuofei Qiao**, Jialong Wu, Zekun Xi, Ningyu Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen.
- `NAACL 2024 findings/KnowledgeNLP@ACL 2024` [KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents](https://arxiv.org/abs/2403.03101). Yuqi Zhu, **Shuofei Qiao**, Yixin Ou, Shumin Deng, Ningyu Zhang, Shiwei Lyu, Yue Shen, Lei Liang, Jinjie Gu, Huajun Chen. **KnowledgeNLP@ACL 2024 Best Paper Award.**

# 🔧Projects

- ``EMNLP 2022 Demo`` [DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population](https://arxiv.org/abs/2201.03335). Github Stars: [![](https://img.shields.io/github/stars/zjunlp/DeepKE)](https://github.com/zjunlp/DeepKE) 🌟
- ``ACL 2024 Demo`` [EasyInstruct: An Easy-to-use Instruction Processing Framework for Large Language Models](https://arxiv.org/abs/2402.03049). Github Stars: [![](https://img.shields.io/github/stars/zjunlp/EasyInstruct)](https://github.com/zjunlp/EasyInstruct) 🌟

# 🎖 Honors and Awards

- *2025.12* Young Talent Support Program for Doctoral Students, CAST (中国科协青年人才托举工程博士生专项计划).
- *2025.12* National Scholarship for Doctoral Students (博士研究生国家奖学金).
- *2025.07* 2025 CIE-Tencent Doctoral Research Incentive Program (2025年度中国电子学会-腾讯博士生科研激励计划).
- 2025.04 ICLR 2025 Scholar Reward.
- *2024.10* Chen Tianzhou Scholarship (陈天洲奖学金). 
- *2024.08* KnowledgeNLP@ACL 2024 Best Paper Award.
- *2023.12* National Scholarship for Master Students (硕士研究生国家奖学金). 
- *2021.12* National Scholarship for Undergraduate Students (本科生国家奖学金).

# 📖 Educations
- *2024.02 - 2027.06*, PhD Student, Zhejiang University.
- *2022.09 - 2024.02*, Master Student, Zhejiang University.
- *2018.09 - 2022.06*, Undergraduate Student, Beihang University.

# 💬 Invited Talks
- *2025.08/2025.11*, How to do distinctive scientific research in the era of LLMs: Taking LLM Agent as an example. CCL2025 Student Seminar/MLNLP2025 Student Seminar.
- *2025.06,* Knowledgeable Agents: Problems, Methods, and Applications. BAAI 7th Conference InnoVibe Lightning Talk.
- *2024.11*, Knowledge-Augmented Large Language Model Agent Planning. SMP2024 PhD Seminar.
- *2023.11*, From Chain-of-Thought to LLM Powered Autonomous Agents. MLNLP. [Slides](https://github.com/zjunlp/Prompt4ReasoningPapers/blob/main/tutorial.pdf).

# 💻 Internships
- *2024.07 - 2025.08,* Alibaba Cloud, Tongyi Lab (DAMO Academy), China.
- *2023.07 - 2024.07*, Alibaba TaoTian Group, China.

# ✍️ Academic Service
- Conference Reviewer: ICLR, NeurIPS, ACL ARR, ACMMM.
- Conference Volunteer: ISWC 2023, ACL 2025.

<a href="https://info.flagcounter.com/UsPL"><img src="https://s01.flagcounter.com/count/UsPL/bg_FFFFFF/txt_000000/border_CCCCCC/columns_4/maxflags_20/viewers_0/labels_1/pageviews_1/flags_0/percent_1/" alt="Flag Counter" border="0"></a>