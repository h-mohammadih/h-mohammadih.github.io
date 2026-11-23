---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a **Postdoctoral Research Scholar at Mass Eye and Ear and Harvard Medical School**, specializing in computational and experimental biomechanics, solid mechanics, and biomedical engineering.

My research focuses on understanding and predicting the mechanical behavior, deformation, and failure of biological tissues and biomechanical systems. I integrate finite-element (FE) modeling, nonlinear constitutive modeling, experimental mechanics, medical imaging, uncertainty quantification, and machine learning to develop experimentally informed computational models.

Research Interests
======
- Computational and Experimental Solid Mechanics
- Middle-Ear Biomechanics and Hearing Mechanics
- Biological Tissue Damage and Failure
- Nonlinear Finite-Element Modeling
- Experimental Mechanics and Model Validation
- Uncertainty Quantification and Machine Learning

Current Research
======
1. My current research focuses on the biomechanics of the human hearing system, particularly the mechanical response of middle-ear structures under intense acoustic loading and surgical manipulation.

1. I develop subject-specific finite-element models informed by high-resolution imaging and experimental measurements to investigate tissue deformation, nonlinear behavior, mechanical injury, and functional impairment.

1. A central goal of my research is to establish predictive computational frameworks to identify injury mechanisms, assess the functional consequences of tissue damage, and contribute to safer otologic surgical procedures.


Research Background
------
I received my PhD in Systems Design Engineering from the University of Waterloo. Before joining Mass Eye and Ear and Harvard Medical School, I conducted postdoctoral research at the University of Waterloo.

My previous research has included computational and experimental investigations of soft-tissue puncture, fracture and damage, nonlinear material behavior, and biomechanical systems.

Future Research Directions
-----
My long-term goal is to establish an independent research program integrating computational mechanics, experimental characterization, and data-driven modeling to investigate tissue injury and its consequences for biomechanical function.

While my current research emphasizes middle-ear biomechanics, I aim to extend these approaches to other mechanically sensitive biological tissues and structures, including the inner ear and other systems where nonlinear material behavior, complex loading conditions, and mechanical injury influence physiological function.



The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

