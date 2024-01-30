---
permalink: /
title: "Thaweerath Phisannupawong"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently pursuing my Master's degree at the Korea Advanced Institute of Science and Technology (KAIST) in South Korea, where I am part of the Laboratory for Information and Control Systems (LiCS) under the expert guidance of Prof. Choi Han-Lim. My work at LiCS primarily revolves around time series representation learning, with a special focus on the trajectories of moving objects. Given the emphasis on core machine learning at LiCS, I have developed a keen interest in self-supervised learning, representation learning (particularly through contrastive learning), and their scientific applications.

In terms of applied machine learning, my current project is centered on aerospace data applications, notably the representation learning for air traffic control data and its multimodal aspects. However, my interests are not confined to any single domain; I believe that the principles of core machine learning research can be universally applied across various scientific fields.

Prior to my time at KAIST, I was an undergraduate student at King Mongkut's Institute of Technology Ladkrabang (KMITL) in Thailand. There, I joined the Air-Space Control, Optimization, and Management Laboratory (ASCOM-LAB) under the supervision of Asst. Prof. Dr. Patcharin Kamsing. The lab's focus on navigation, guidance, control, and aerospace data application aligned well with my interests. During my undergraduate studies, my thesis centered on vision-based spacecraft pose estimation for non-cooperative docking operations, exploring the intersection of data mining and aerospace engineering.

Additionally, I gained valuable experience as a research intern at the National Astronomical Research Institute of Thailand (NARIT), where my work involved simulating spacecraft kinematics and dynamics.

Before embarking on my journey at KAIST, I was part of an entrepreneurial endeavor linked to ASCOM-LAB. As an aerospace engineer at Satang Space Company Limited, a spin-off from ASCOM-LAB, I contributed to the development of a space situational awareness (SSA) system. This system not only monitors space objects and predicts collision risks but also incorporates data-driven risk assessment techniques using machine learning to evaluate potential collisions.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)
