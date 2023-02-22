---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello and welcome to my page! I'm Chrysovalantis Constantinou, 
an Associate Research Scientist at 
The Science and Technology in Archaeology and Culture 
Research Center of [The Cyprus Institute](https://www.cyi.ac.cy/). 
My PI is Associate Professor [Efthymia Nikita](https://cyi.academia.edu/EfthymiaNikita), 
and together we're using agent-based modeling to study the migration patterns 
of ancient populations and machine 
learning to predict the age and sex of skeletons. Previously,
I was a Computational Scientist at the [Department of Computation-based Science and Technology Research Center](http://castorc.cyi.ac.cy/), also at The Cyprus Institute. 


My research focuses on using agent-based modeling to study the migration 
patterns of ancient populations that lived 
around the Mediterranean Sea, with a particular focus on the Roman period. 
Together with my PI, we also employ machine learning to create 
models that predict the age and sex of skeletons. 
More specifically, we're using machine learning techniques 
on bone datasets to build models that predict the age, sex, and other properties 
of skeletons based on metric or ordinal measurements. The constructed models are 
then used in web applications to help make predictions on 
unknown skeletons. An example of such a service is [SexEst](http://sexest.cyi.ac.cy/), 
a web application we developed that uses machine learning to predict 
the sex of skeletal remains based on metric measurements.


I'm also responsible for work package 6 (training and demonstrators) 
of the [NI4OS-Europe](https://ni4os.eu/) project, an infrastructure project funded by 
the European Commission under the Horizon 2020 
grant agreement no. [857645](https://cordis.europa.eu/project/id/857645). 
The project aims to help 
researchers in South-Eastern Europe onboard their services, 
such as repositories and web applications, onto the 
[European Open Science cloud](https://eosc-portal.eu/). 
This will make the services readily 
available for citizens and researchers in Europe. 
NI4OS-Europe is a critical infrastructure project that 
aims to accelerate the uptake of open science in the region. 
My role in work package 6 involves developing training 
materials and demonstrations, and to help researchers 
effectively onboard their services onto the cloud.


Additionally, I'm a code contributor to [clowder](https://clowderframework.org/), 
an open-source data curation platform designed to help 
researchers manage and share their data. The platform 
offers a wide range of tools and features, including 3D 
model previewers, which are essential for researchers 
working with 3D models. My main contribution to the project is 
in creating 3D model previewers, which allow researchers to 
easily visualize their models. 



Finally, I am also interested in theoretical physics which was the subject of 
my doctorate studies. Specifically, I am interested in using high-performance 
computing to study the structure of nuclei such as 
<sup>6</sup>He, <sup>7</sup>Li, and <sup>7</sup>Be, which are 
important in stellar burning processes but also in low-energy nuclear reactions.
Due to my exposure to machine learning, I am now also interested in using machine 
learning in nuclear physics.


To summarize, I’m interested in using theoretical and computational techniques to 
solve problems related to nuclear physics (and physics in general), in using machine 
learning techniques on any available dataset, and, finally, 
I’m fascinated by 3D models and their use in 
websites and games. You can find an example of such usage
in [this](https://threejs-car-physics-demo.vercel.app/) web app.


Thank you for visiting my page, and please feel free to reach 
out if you have any questions or if you're 
interested in collaborating on any of my ongoing research projects.


<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
