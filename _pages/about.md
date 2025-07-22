---
permalink: /
title: "Great to meet you online"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a final year PhD student of Electrical Engineering at the University of Washington advised by Prof. [Kai-Mei Fu](https://sites.google.com/uw.edu/optospintronics-lab/home). My research focuses on formation, optical characterization and control of solid state spin defects as building blocks of an optical quantum network.
---
I have completed a [Graduate Certificate in Quantum Information Science & Engineering](https://www.quantumx.washington.edu/training/graduate-certificate-in-quantum-information-science-and-engineering/), from which I learned how to access real quantum computers hosted on the cloud and run simple ground state energy estimation algorithms on a few qubits from trotterizing Hamiltonians. 
---
Before UW I graduated from Reed College with a B.A. in Physics. I was grateful to be introduced to solid state device physics through my REU at Arizona State University hosted by Prof. Zachary Holman. As a continuation of my summer research, I built an optical setup to measure the minority carrier lifetime of CdTe thin film solar cells for my undergrad thesis project advised by Prof. John Essick. 

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

