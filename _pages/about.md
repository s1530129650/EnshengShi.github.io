---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a joint PhD student, supervised by Dongmei Zhang, Shi Han, Yanlin Wang and Prof. Hongbin Sun, between Microsoft Research Asia and Xi'an Jiaotong University. 

I am mainly focusing on **code intelligence** (intersection of Software Engineering and Artificial Intelligence), which aims to leverage AI to help software developers improve the productivity of the development and reduce costs of the maintenance process. Specifically, it utilizes the **machine learning** model to mine knowledge from large scale, free source code data (Big Code) which is available on Github, etc, obtains the better **code representation** (based on code token/ AST/ PDG/ IR etc) and applies the representation to the **downstream tasks** such as code summarization, code search, clone detection, code completion, program repair, etc.

My research areas currently include: **(1) Code Represention Learning; (2) Code Summarization; (3) Code Search; (4)Commmit Message Generation**


## Publications
### 2021

<p><b>On the Evaluation of Neural Code Summarization</b> <br>
<small>
<i>ICSE2022 <a href="https://arxiv.org/abs/2107.07112">[pdf]</a> <a href="https://arxiv.org/abs/2107.07112">[code]</a></i>
<br />
<u>Ensheng Shi</u>, Yanlin Wang, Lun Du, Junjie Chen, Shi Han, Hongyu Zhang, Dongmei Zhang, Hongbin Sun 
<br /><b>TLNR</b>: Some interesting and surprising findings on the evaluated metric, code-preprocessing, and evaluated datasets. Building a shared code summarization toolbox andgiving actionable suggestions on the evaluation of neural code summarization. 
<br />
<details>
<summary></summary>
<ul>
<li> BLEU_DC (sentence BLEU with smoothing method 4) is most correlated to human perception on the evaluation of neural code summarization model among the 6 widely used BLEU variants.
</li>
<li> Performing S (identifier splitting) is always significantly better than not performing it. And different code pre-processing has a large impact on performance (-18\% to +25\%)
</li>
<li> To more comprehensively evaluate different models, it is recommended to use multiple datasets, as rank among models can be inconsistent on different datasets.
</li>
<li>More findings of the evaluated metric, code pre-processing operations, evaluated datasets(the data size, splitting way, and duplication ratio )
</li>
</ul>
</details>
</small>
</p>

<p><b>CAST: Enhancing Code Summarization with Hierarchical Splitting and Reconstruction of Abstract Syntax Trees</b> 
<br><small>
<i>EMNLP2021 <a href="https://aclanthology.org/2021.emnlp-main.332.pdf">[pdf]</a> <a href="https://github.com/DeepSoftwareAnalytics/CAST">[code]</a></i>
<br />
<u>Ensheng Shi</u>, Yanlin Wang, Lun Du, Hongyu Zhang, Shi Han, Dongmei Zhang, Hongbin Sun
<br /><b>TLNR</b>: Our model hierarchically
splits and reconstructs ASTs to obtain the better code representation for code summarization.</small>
</p>

<p><b>Is a Single Model Enough? MuCoS: A Multi-Model Ensemble Learning Approach for Semantic Code Search</b> 
<br><small>
<i>CIKM 2021 <a href="https://dl.acm.org/doi/abs/10.1145/3459637.3482127">[pdf]</a> <a href="https://github.com/Xzh0u/MuCoS">[code]</a></i>
<br />
 Lun Du, Xiaozhou Shi, Yanlin Wang, <u>Ensheng Shi</u>,  Shi Han, Dongmei Zhang
<br /><b>TLNR</b>: Ensembling three models which focus on the structure of code , local variables, and the information of API invocation, separately, for semantic code search.</small>
</p>

<p><b>On the Evaluation of Commit Message Generation Models: An Experimental Study</b> 
<br><small>
<i>ICSME 2021 <a href="https://ieeexplore.ieee.org/abstract/document/9609189">[pdf]</a> <a href="https://github.com/DeepSoftwareAnalytics/CommitMsgEmpirical">[code]</a></i>
<br />
 Wei tao, Yanlin Wang, <u>Ensheng Shi</u>, Lun Du, Shi Han, Dongmei Zhang, Wenqiang Zhang
<br /><b>TLNR</b>: We conduct the empirical study on evaluated metrics and existing datasets. We
also collect a large-scale, information-rich, and multi-language
commit message dataset MCMD and evaluate existing models
on this dataset. </small>
</p>

### 2020
<p><b>CoCoGUM: Contextual Code Summarization with
Multi-Relational GNN on UMLs</b> 
<br><small>
<i>MSR-TR 2020 <a href="https://www.microsoft.com/en-us/research/uploads/prod/2020/05/CoCoGUM-TR.pdf">[pdf]</a> </i>
<br />
Yanlin Wang, Lun Du, <u>Ensheng Shi</u>, Yuxuan Hu, Shi Han, Dongmei Zhang
<br /><b>TLNR</b>: We explore modeling two global
contexts: intra-class level context and inter-class level context for code summarization.</small>
</p>

## Educations

 <td align="left"><h3>
2019.8 ~ Present: <a href="http://en.xjtu.edu.cn/">Xi'an Jiaotong University</a> </h3>
<ul>
<li><p>MSRA-XJTU Joint PHD</p>
</li>
<li><p>The College of Artificial Intelligence</p>
</li>
</ul>
</td>

<td align="left"><h3>
2015.8 ~ 2019.7: <a href="http://en.xjtu.edu.cn/">Xi'an Jiaotong University</a> </h3>
<ul>
<li><p>Outstanding Graduate</p>
</li>
<li><p>Automatic Science and Technology</p>
</li>
</ul>
</td>

## Experiences
<ul>
<li>
Research Intern in Microsoft Research Asia<br>
Advised by Dongmei Zhang, Shi Han, & Yanlin Wang in Data, Knowledge, and Intelligence group, from Jun 2020 to Present.
</li>
<li>
Research Intern in Microsoft Research Asia<br>
Advised by Dongmei Zhang, Shi Han, Zhouyu Fu, & Mengyu Zhou in Software Analytics group, from Nov 2018 to Aug 2019.

</li>
</ul>

## Awards
<ul>
<li>
2019 Outstanding Graduate Award 
</li>
<li>
2018 Elite Class Scholarship of Institute of Automation, China Academy of Sciences
</li>
<li>
2018 Grateful Scientist Bursary
</li>
<li>
2018 National Scholarship
</li>
<li>
2017 Outstanding Volunteer Award
</li>
<li>2017 National  Encouragement Scholarship
</li>
<li>
2016 First Prize of Mathematical Modeling Contest at Provincial Level
</li>
<li>2016 National  Encouragement Scholarship
</li>
</ul>
