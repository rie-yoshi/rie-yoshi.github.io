---
permalink: /
title: # "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second-year of master student at The University of Tokyo where I am majoring in Interdisciplinary Information Studies. My areas of research interests are Computer Vision, Human-Object Interaction Recognition, and Human Motion Recognition. 


## Research Interests
Human skill understanding in video\
Hand object interaction

## Domestic Conference
- <u>Rie Yoshioka</u> and Kazutaka Kurihara, "AugmentedDecisions: 判断能力の拡張を目的とした機械学習予測提示インタフェースの検討," [情報処理学会 エンタテインメントコンピューティングシンポジウム2025](https://ec2025.entcomp.org/program/), 論文集2025 p. 218-225, 2025-08-18. (In Japanese). [[Proc.](https://ipsj.ixsq.nii.ac.jp/records/2003677)]
- <u>Rie Yoshioka</u> and Daisuke Sugimura, “In-Air Writing Authentication using Recurrent Neural Networks,” [電子情報通信学会総合大会 2024](https://pub.confit.atlas.jp/ja/event/general2024/presentation/D-12B-16), Hiroshima University, 7 March, 2024. (In Japanese). [[PDF](https://drive.google.com/file/d/1NjCGtUBL-Jo2mJaRtByzdK41CbO1wpso/view)]

## Awards
- [HeroseLeague 2024](https://heroes-league.net/)
  - 12-30 November, 2024. Myヒーロー賞 [(toioとM5StackやxModによるインパクトある作品で賞)](https://protopedia.net/event/hl2024#:~:text=toio%E3%81%A8M5Stack%E3%82%84xMod%E3%81%AB%E3%82%88%E3%82%8B%E3%82%A4%E3%83%B3%E3%83%91%E3%82%AF%E3%83%88%E3%81%82%E3%82%8B%E4%BD%9C%E5%93%81%E3%81%A7%E8%B3%9E%20by%20akichika) . (December 2024)  [Link](https://www.tsuda.ac.jp/news/2024/1227.html)
- **Umeko Tsuda Memorial Alumni Association Awards**(*2) (May 2024) 
- **Project award**
  - In a required course in which students develop their own systems (December 2023) 
- **Umeko scholarship**(*1) 2023 (September 2023) 
- **Umeko scholarship**(*1) 2022 (July 2022)

*(\*1) Umeko scholarship: Award to outstanding students for academic achievement and personal qualities, recommended by each department, who are in their second year or above.* [Link](https://www.tsuda.ac.jp/student-life/scholarship/detail.html#:~:text=%E6%A2%85%E5%AD%90%E3%82%B9%E3%82%AB%E3%83%A9%E3%82%B7%E3%83%83%E3%83%97%EF%BC%88%E5%AD%A6%E6%A5%AD%EF%BC%89) \
*(\*2) Umeko Tsuda Memorial Alumni Association Awards: Award to a senior undergraduate student with excellent academic performance and character, and a rich spirit of service.* [Link](https://www.tsuda.ac.jp/student-life/scholarship/detail.html#:~:text=%E6%B4%A5%E7%94%B0%E6%A2%85%E5%AD%90%E8%A8%98%E5%BF%B5%E5%90%8C%E7%AA%93%E4%BC%9A%E8%B3%9E)


<!--
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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
