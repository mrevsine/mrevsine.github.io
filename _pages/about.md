---
permalink: /
title: "Mahler Revsine - About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! My name is Mahler Revsine (he/him; name pronounced like "dollar"). I'm a scientist interested in using Deep Learning to advance our understanding of Genomics. I am currently a PhD student working under the supervision of Dr. Michael Schatz in the Computer Science Department at Johns Hopkins Univeristy. I am grateful to be supported by the National Science Foundation's Graduate Research Fellowship Program. 

Research
======
I have been fortunate to learn from a number of talented PIs throughout my scientific career. During my undergrad at the University of North Carolina, [Dr. Jeremy Wang](https://jwanglab.org/) introduced me to the field of bioinformatics and got me hooked on the idea of using my programming skills to solve real-world problems. Throughout my postbac program at the National Cancer Institute at the NIH, I got to work with Drs. [Xin Wei Wang](https://ccr.cancer.gov/staff-directory/xin-wei-wang) and [Lichun Ma](https://ccr.cancer.gov/staff-directory/lichun-ma), both of whom enthusiastically guided me on a project to analyze tumor evolution during immunotherapy treatment. In my first semester of my PhD program at Johns Hopkins, I had the opportunity to rotate with [Dr. Steven Salzberg](https://salzberg-lab.org/), whose passion for discovery inspired me during a project to assess reported microbial counts in human cancer samples. Most recently, my advisor [Dr. Michael Schatz](https://schatz-lab.org/) has been a savvy mentor and a tremendous resource, showing me the frontiers of which key questions are currently unsolved in genomics while also helping me grow into a deep learning researcher. 

Background
======
I grew up in Washington DC, where I attended School Without Walls High School (it's a metaphor, we did in fact have walls). I went to college at the University of North Carolina, where I majored in Computer Science and Biology (go heels!). 

Some of my hobbies include:
- Basketball, both watching and playing - I'm a huge fan of the Chicago Bulls, even though I was born after Jordan left the team. I play recreationally as much as possible, including in Hopkins' intramural leagues.
- Sports in general - I'm also a fan of the Chicago Bears, although this has been a net negative on my life.
- Travel - If I'm not in another country, I'm saving up to go to one! 
- Maps - I am constantly on the hunt for a political, south-up, equal area map projection. There's one I've seen online but it's too small. If anyone finds one, please contact me.
- Daily games - I do the NYTimes crossword every day and am also a fan of Wordle, the NYTimes Spelling Bee, geography games, and others.
- Personal coding projects - I've done a variety of projects here and there when inspiration strikes. The one I've put the most time into is to make a chess engine that I can't beat, which is still a work in progress.

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
