---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!


News
======
2025/
2024/
2023/
2022/

Publications
======
[1] Chai, X., Zhang, H., Zhu, A., et al. Component-Level Construction Progress Management via YOLO-Based BIM Visualization and Semantic Web Integration. (finished)
[2] Zhu, A., Chai, X., Shao, Z., et al. An Image Recognition-based Method for Hardware-Free Robotic Building Space Localization[J]. Automation in Construction. (under review)
[3] Zhu, A., Shao, Z., Chai, X., et al. Component-based BIM-Semantic Web Integration for Enhanced Robotic Visual Perception[J]. Automation in Construction,2025. (SCI, IF=9.6, JCR-Q1)
[4] Zhou, C., Zhang, H., Chai, X., et al. Research on the design of prefabricated curved structure production capacity residential energy system: a case study of an entry of 2022 China International Solar Decathlon Competition ——‘Solar Ark3.0’[J]. Architectural Intelligence,2024.
[5] Chen, X., Zhou, Y., Chai, X., et al. Algae Reactor: A 3D-printed façade module for cultivating chlorella with
indoor CO2. The 6th Conference on Computational Design and Robotic Fabrication, 2024.
Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

Competitions Activities
------

Honors and Awards
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Educations
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

Work Experiences
------
The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

