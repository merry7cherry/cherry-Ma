---
permalink: /
title: "Hi, here is Chenrui Ma's homepage, Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a senior student at the [University of California, Irvine](https://uci.edu/), enrolled in the 3+2 engineering program under the Department of Electrical Engineering and Computer Science. I am completing my senior year studies, research, and preparations at UCI, while planning to pursue a Ph.D. in the future. Prior to this, I completed the first three years of my undergraduate study (2021.09-2024.06) at the School of Computer Science, [Central South University](https://www.csu.edu.cn/). During this time, I was awarded the third-class scholarship in 2023 and the second-class scholarship in 2024. I have completed both core and elective courses in computer science with strong academic performance and have actively participated in extracurricular competitions and internships, enhancing my coding skills and problem-solving abilities. I consider my ability and passion for learning new things to be my greatest strengths.

Research Interest
======
* Machine Learning
* Deep Learning
* Networks
* Big Data

Courses Studied
======

| Category            | Course Name                                           | Grade |
| ------------------- | ----------------------------------------------------- | ----- |
| Major Core Courses   | Analysis and Design of Algorithms                     | A     |
| Major Core Courses   | Operating Systems                                     | A     |
| Major Core Courses   | Computer Networks                                     | A+    |
| Major Core Courses   | Principles of Computer Organization and Assembly Language |  B    |
| Major Core Courses   | Database Principles                                   | B    |
| Major Core Courses   | Software Engineering                                  | A+    |
| Major Courses        | Computer Architecture                                 | A+    |
| Major Courses        | Machine Learning                                      | A     |
| Major Courses        | Digital Image Processing                              | A+    |
| Major Courses        | Deep Learning                                         | A+    |
| Major Courses        | Computer Vision                                       | A+    |
| Major Courses        | Data Warehousing and Data Mining                      | A+    |
| Major Courses        | Distributed Systems and Cloud Computing               | A+    |
| Major Courses        | Visualization Techniques                              | A+    |
| Major Courses        | Embedded Systems                                      | A+    |
| Major Courses        | Artificial Intelligence                               | A+    |
| Major Courses        | Bioinformatics                                        | A+    |
| Major Courses        | Linux System and Applications                         | A+    |
| Major Courses        | C Programming                                         | B     |
| Major Courses        | Java Programming and Application Development          | B     |
| Major Courses        | Python Programming                                    | A     |
| Major Courses        | Human-Computer Interaction                            | A+    |
| Major Courses        | Game Design                            | A+    |
| Courses in UCI       | [Scientific Writing](https://merry7cherry.github.io/cherry-Ma/files/Scientific-Writing-Grade.pdf)                         | A+    |

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
