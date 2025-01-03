--- 
title: "Microbiome Data Science & Multi-Omics with R/Bioconductor"
subtitle: "Oulu, December 2024"
date: "2025-01-03"
site: bookdown::bookdown_site
documentclass: book
bibliography: [packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: microbiome/course_2024_oulu
description: "Course material"
output:
  bookdown::gitbook
  bookdown::pdf_document2
always_allow_html: true  
classoption: oneside
geometry:
  - top=30mm
  - left=15mm
---



# Overview

<!--<a href="https://bioconductor.org"><img src="https://github.com/Bioconductor/BiocStickers/raw/master/Bioconductor/Bioconductor-serial.gif" width="200" alt="Bioconductor Sticker" align="right" style="margin: 0 1em 0 1em" /></a>-->

<a href="https://bioconductor.org"><img src="bioconductor_logo_rgb.jpg" width="200" alt="Bioconductor Sticker" align="right" style="margin: 0 1em 0 1em" /></a>


## Contents and learning goals

::: {.grid}

::: {.g-col-8}
**Contents and learning goals**: This course provides an introduction to microbiome data science with R/Bioconductor, a popular open source environment for scientific data analysis. A special emphasis is given to multi-omic data integration methods. After the course you will know how to organize multiple data sources into a coherent framework, implement reproducible data science workflows, and approach common data analysis tasks by utilizing available documentation and R tools. Whereas the primary focus is on microbiome research, the covered data science methods are generally applicable and we will discuss links with other application domains such as transcriptomics, metabolomics, and single cell sequencing. 

**Target audience**: MSc students, PhD, postdoctoral, and other researchers who wish to learn new skills in statistical programming and data analysis. Academic students and researchers from Finland and abroad are welcome and encouraged to apply.

**Teaching material**: We will follow open online documentation created by the course teachers, primarily the [Orchestrating Microbiome Analysis](https://microbiome.github.io/OMA) (OMA) book. The training material walks you through the standard steps of omics data analysis covering data access, exploration, analysis, visualization, and reproducible workflows. Preparatory material and video clips, and online support are available before the course. All teaching materials are shared openly.
:::

::: {.g-col-3}
![Figure source: Moreno-Indias _et al_. (2021) _Frontiers in Microbiology_ 12:11. ](fig.png){fig-align="center" width="300"}
:::

:::


## Schedule 

**Venue**: University of Oulu. December 18-20, 2024 (Wed-Fri). The course is organized in a live format; no remote option available. 

**Costs**: Registration is free. Participants are expected to cover their own travel and accommodation.

**Accommodation**: Housing tips can be found at <https://visitoulu.fi/en/arrival-overnight/>.

**Schedule**: Contact teaching daily between 9am -- 5pm, including lectures, demos, practicals, and breaks. For a detailed schedule, see Section \@ref(program). The course can be extended by an independent assignment (details to be agreed with the main teacher).


## How to apply

- Send a brief motivation letter to Anna Kaisanlahti [anna.kaisanlahti\@oulu.fi](mailto:anna.kaisanlahti@oulu.fi){.email}. In your letter, please describe your skill level in R coding using scale 1-5 (1 = no previous experience, 5 = advanced level), and your previous experience related to bioinformatics.
- Applications from local students, and applications sent before 11 November 2024 will be given priority.
- The course has maximum capacity of 20 participants.
- The enrollment to the course will be confirmed within few days after the application deadline (Nov 11).
- Applications received after 11.11 will also be considered in case there are slots still available.

## Before the course

For self-learning, visit [this site](https://microbiome.github.io/OMA/docs/devel/pages/training.html).


## Teachers and organizers

**Teachers**: [Leo Lahti](https://datascience.utu.fi) is the main teacher and Professor in Data Science at the University of Turku, and a certified [Carpentries](https://carpentries.org) Instructor. PhD researcher *Tuomas Borman* is a co-teacher and main developer of the data science framework used in the course. *Anna Kaisanlahti* (Oulu) is a course assistant, and Docent *Justus Reunanen* is the course coordinator. The course is organized by [Health and Biosciences Doctoral Programme (HBS-DP)](https://www.oulu.fi/en/research/graduate-school/organisation-and-contact-information-uniogs/health-and-biosciences-doctoral-programme) University of Oulu Graduate School, Research Unit of Translational Medicine, University of Oulu. We thank the [Finnish IT Center for Science (CSC)](https://csc.fi/) supports the course by providing cloud computing services.

This is a Bioconductor course @Soneson2024 and we follow the best practices recommended by [Software carpentries](https://carpentries.org).

## Code of Conduct

The Bioconductor community values an open approach to science that promotes the

 - sharing of ideas, code, software and expertise
 - open collaboration and community contributions
 - diversity and inclusivity
 - a kind and welcoming environment
 
More details on its enforcement are available [here](https://bioconductor.github.io/bioc_coc_multilingual/).

## Acknowledgments

**Citation**: We thank all [developers and contributors](https://microbiome.github.io) who have contributed open resources that supported the development of the training material. Kindly cite the course material as @miacourse. This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 952914 (FindingPheno).

**Contact**: Refer to [https://microbiome.github.io](https://microbiome.github.io).

**License and source code**:

All material is released under the open [CC BY-NC-SA 3.0 License](LICENSE) and available online during and after the course, following the [recommendations on open teaching materials](https://avointiede.fi/fi/linjaukset-ja-aineistot/kotimaiset-linjaukset/oppimisen-ja-oppimateriaalien-avoimuuden-linjaus) of the national open science coordination in Finland.

