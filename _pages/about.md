---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 

---

I am currently a second-year master's student at Tsinghua Shenzhen International Graduate School, Tsinghua University, affiliated with the Intelligent Computing Lab. My supervisor is Prof.  [Xiu Li](https://scholar.google.com/citations?user=Xrh1OIUAAAAJ&hl=en), and I have received a lot of research guidance from my senior fellow student [Jiafei Lyu](https://dmksjfl.github.io/). My main research focus on Reinforcement Learning, especially on Agent Exploration, Multi-Agent Reinforcement Learning and RLHF of Large Models. Currently, I am undertaking an internship at Tencent Technology Engineering Group, Machine Learning Platform Department, researching the effective fine-tuning of Large Language Models using RLHF.

I have not yet decided on my future direction. If you believe I am a good fit for your position or would consider me for a PhD program, please don't hesitate to contact me at yk22@mails.tsinghua.edu.cn.

News
=====
- 2024.5 The paper "Exploration and Anti-Exploration with Distributional Random Network Distillation" is accepted by ICML 2024

- 2024.4 The work "BATON: Aligning Text-to-Audio Model with Human Preference Feedback" is accepted by IJCAI 2024.

- 2024.2 The paper "Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model" is accepted by CVPR 2024

- 2024.2 The work "BATON: Aligning Text-to-Audio Model with Human Preference Feedback" is on [Arxiv](https://arxiv.org/abs/2402.00744).

- 2024.1 My work "Exploration and Anti-Exploration with Distributional Random Network Distillation" is on [Arxiv](https://arxiv.org/abs/2401.09750).

- 2023.11 The paper "Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model" is selected as [HuggingFace daily paper](https://huggingface.co/papers/2311.13231)

- 2023.11 My work "Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model" is on [Arxiv](https://arxiv.org/abs/2311.13231).

Publications
======
- [Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model](https://arxiv.org/abs/2311.13231). **Kai Yang**, Jian Tao, Jiafei Lyu, Chunjiang Ge, Jiaxin Chen, Weihan Shen, Xiaolong Zhu, Xiu Li. IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR), 2024
- [Exploration and Anti-Exploration with Distributional Random Network Distillation](https://arxiv.org/abs/2401.09750). **Kai Yang**, Jian Tao, Jiafei Lyu, Xiu Li. International Conference on Machine Learning (ICML), 2024.
- [BATON: Aligning Text-to-Audio Model with Human Preference Feedback](https://arxiv.org/abs/2402.00744). Huan Liao, Haonan Han, **Kai Yang**, Tianjiao Du, Rui Yang, Zunnan Xu, Qinmei Xu, Jingquan Liu, Jiasheng Lu, Xiu Li. International Joint Conference on Artificial Intelligence (IJCAI), 2024.
- [GTLMA: Generalizable Hierarchical Learning for Tasks with Variable Entities](). **Kai Yang**, Aicheng Gong, Jian Tao, Yang Zhang, Xiu Li. 2023 International Conference on Frontiers of Robotics and Software Engineering (FRSE).
- [A novel ensemble approach for road traffic carbon emission prediction](https://link.springer.com/article/10.1007/s10668-024-04561-1): a case in Canada. Yongliang Liu, Chunling Tang, Aiying Zhou, **Kai Yang**. Environment, Development and Sustainability.
  
Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
