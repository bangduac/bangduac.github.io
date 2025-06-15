---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr Bang Du obtained his PhD from the University of Galway, Ireland, in March 2024. He then joined the University of Surrey as a Research Fellow in Bioinformatics and Anaerobic Digestion Microbiome Modelling, and serves as a Lecturer in Civil and Environmental Engineering. He is currently leading a Marie Skłodowska-Curie Postdoctoral Fellowship project and has contributed to several national and international research projects funded by UKRI-EPSRC, Science Foundation Ireland, Sustainable Energy Authority of Ireland, and the National Natural Science Foundation of China. Dr Du has published serveral peer-reviewed journal papers, such as Water Research.

His research focuses on valorisation and energy recovery from anaerobic waste and wastewater treatment, particularly in:
1. applying ecological theory in microbial enrichment and metabolic pathway regulation with engineering approaches, and 
2. integrating thermodynamic-kinetic-microbiome models to reveal the dynamics of microorganisms, substrates, energy, and electrons in biological treatment.

Research interests
------
1. Biological Treatment and Resource Recovery in Waste/Wastewater
2. Microbial Interactions and Electron Transfer Mechanisms
3. Modelling and Bioinformatics Analysis

Career
======
### Lecturer  
**Civil and Environmental Engineering, School of Engineering, University of Surrey, UK**  
*April 2025 – Present*  
- MSc Modules: ENGM304 Wastewater Treatment, ENGM044 Dissertation Project

### Research Fellow  
**School of Engineering, University of Surrey, UK**  
*May 2024 – March 2025*  
- Bioinformatics  
- Anaerobic microbiome modelling  
- Life cycle assessment

### Lab Manager  
**Centre for Environmental Health and Engineering (CEHE), University of Surrey, UK**  
*September 2024 – Present*

### Teaching Assistant  
**Civil Engineering, University of Galway, Ireland**  
*2022 – 2023*  
- Modules: Design of Sustainable Environmental Systems, Civil Engineering Materials and Design, Engineering Computing, Fundamentals of Engineering

### Research Assistant  
**Institute of Hydrobiology, Chinese Academy of Sciences, China**  
*August 2020 – December 2020*  
- Reactor operation  
- Experiments in molecular and cellular biology

### Civil Design Engineer  
**CITIC General Institute of Architectural Design and Research, China**  
*July 2019 – May 2021*  
- Construction Drawing Design  
- Building Information Modelling (BIM)  
- Projects: Water Supply, Drainage, Wastewater Treatment Module, and Fire-Fighting System

Education
======
Ph.D., Civil Engineering (Environmental Engineering), 06/2021–03/2024, University of Galway, Ireland

M.Eng., Civil Engineering (Environmental Engineering), 09/2016–04/2019, Hefei University of Technology, China

B.Eng., Water Supply and Drainage Engineering, 09/2012–07/2016, Hefei University of Technology, China

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
