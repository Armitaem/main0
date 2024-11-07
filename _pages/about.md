---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I’m Armita, and I’m on a mission to uncover the hidden connections between our genes, microbiota, and immune and nervous systems. I earned my bachelor’s degree from Alzahra University and master’s degree from Azad Medical University of Tehran. Currently, I work as a researcher in a microbiology lab, where I focus on gaining a molecular perspective of human diseases. In addition to my research, I also teach biology, sharing my enthusiasm for science and helping students explore the fascinating complexities of life at the cellular and molecular levels.

I’m deeply fascinated by how details at the molecular level influence broader biological systems, offering new insights for health improvement and disease prevention. My background in microbiology, molecular biology, and computational biology allows me to approach these questions with a holistic perspective. Whether I’m investigating how gut microbes impact cancer events, using machine learning to predict health outcomes, or engineering probiotics for therapeutic use, my goal is to drive meaningful insights that could shape the future of personalized medicine.”



My Work and Research
======
My work as a researcher in a microbiology lab at the Research Institute for Gastroenterology and Liver Diseases has immersed me in diverse projects in microbiology, molecular biology, and bioinformatics. Currently, my focus is on bioinformatics applications in cancer biology, with experience that includes clinical microbiology research, where I was part of an anaerobic bacterial research group exploring gastrointestinal diseases, microbiome therapies, and drug delivery modeling.


Through projects like multilocus sequence typing of Clostridioides difficile and studying the protective effects of Lactobacillus crispatus in liver disease models, I’ve developed expertise in microbiome analysis, gene expression profiling, and computational biology techniques. Teaching biology alongside my research allows me to inspire students and share my excitement for uncovering the mysteries of life through both laboratory work and data analysis.



Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/armitaem.github.io/main/) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/armitaem.github.io/main//blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/armitaem.github.io/main//blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/armitaem.github.io/main//tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](armitaem.github.io/main/talks), each [individual page](armitaem.github.io/main/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](armitaem.github.io/main/cv), and the [map of places you've given a talk](armitaem.github.io/main/talkmap.html) (if you run this [python file](https://github.com/academicpages/armitaem.github.io/main//blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/armitaem.github.io/main//blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/armitaem.github.io/main//tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/armitaem.github.io/main//blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](armitaem.github.io/main/markdown/), the [growing wiki](https://github.com/academicpages/armitaem.github.io/main//wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/armitaem.github.io/main//discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
