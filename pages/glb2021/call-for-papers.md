---
permalink: /glb2021/call-for-papers
title: "Call for Papers - GLB 2021"
masthead-title: "GLB 2021"
masthead-subtitle: "@TheWebConf 2021"
masthead-url: "/glb2021/"
navigation: 
  - title: "CfP"
    url: /glb2021/call-for-papers
  - title: "Schedule"
    url: /glb2021/#schedule
  - title: "Invited Speakers"
    url: /glb2021/#invited-speakers
  - title: "Accepted Papers"
    url: /glb2021/#accepted-papers
  - title: "Organization"
    url: /glb2021/#organizers
  - title: "GLB 2022"
    url: /
layout: splash
# classes: wide
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.9"
    overlay_image: /assets/images/glb-bg.jpg
---

{% capture notice-text %}
**You are viewing the archived site for GLB 2021.** To learn more on the latest edition of the workshop, [click here](/).
{% endcapture %}

<div class="notice--warning">
  <!-- <h4 class="no_toc">Notice Headline:</h4> -->
  {{ notice-text | markdownify }}
</div>


We especially (but not exclusively) call for submissions which will contribute to at least one of the following:

- **New Graph Datasets**: Novel graph-structured datasets—especially large-scale, application-oriented, and publicly accessible datasets. We also welcome methods and software packages that enable streamlined benchmarking of large-scale graph data, crawling or crowdsourcing for labeled graph data, and generation of realistic synthetic graphs.
- **New ML Tasks**: New ML tasks and applications on different types of graphs, at different levels (e.g., node, edge, subgraph or graph), with a special focus on real-world and industry-valued problems.
- **New Metrics**: New evaluation procedures and metrics of graph learning associated with the various tasks and datasets.
- **Benchmarking Studies**: Studies that benchmark multiple graph ML methods (especially graph neural networks) on non-trivial tasks and datasets. We explicitly encourage works that reveal limitations of existing models, optimize matches between model design and problems, and other novel findings about the behaviors of existing models on various tasks or datasets.

The acceptance of the contributed papers is decided on the meaningfulness of the established graph learning tasks/datasets and their potential of being formalized into new benchmarks, rather than the performance of ML models (old or new) on these tasks. We particularly welcome contributions of **negative results** of popular, state-of-the-art models on a new task/dataset, as these provide novel insights to the community’s understanding of the meta-knowledge of graph ML. 

# Important Dates
- Submission deadline: ~~Feb 15~~ Feb 22, 2021 (Anywhere on Earth)
- Acceptance notification: ~~Mar 8~~ Mar 15, 2021
- Camera-ready version due: ~~Mar 22~~ Mar 29, 2021

# Submission
Abstracts and papers can be submitted through CMT: <br>
[https://cmt3.research.microsoft.com/GLB2021/Submission/Index](https://cmt3.research.microsoft.com/GLB2021/Submission/Index)

# Format

- A paper no longer than *4 pages* (excluding references and the appendix) using [the ACM “sigconf” LaTeX template](https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart-master.zip) (see [the instruction by the Web Conference 2021](https://www2021.thewebconf.org/authors/call-for-papers)).
- This workshop is *non-archival*. Relevant findings that have been recently published are also welcome.
- The submission is single-blinded for the ease of data/code sharing. The reviewers are anonymized but the authors do not need to be anonymized in the submission.
- Authors are *strongly encouraged* to include the corresponding datasets and code as supplementary materials in their submission. For large datasets or repositories, the authors can provide an external link through Github, Google drive, Dropbox, OneDrive, or Box. We limit the choice of storage platforms for security considerations. Please email the organizers if none of the listed platforms works for you.
- If the data cannot be made publicly available, an extra section is required to illustrate how the results of the established benchmark may generalize to other graph data.