---
title: "Resampling and simulation techniques"
author: "Martin van Rongen, Matt Castle"
date: today
number-sections: false
---

## Overview 

Traditional statistical testing make use of various distributions and assumptions. This often works well, allowing us to analyse our data using standardised tests - or slight variations on them.

However, sometimes you might end up with data that are just *weird* and the standard tests or even the adaptations of them no longer work. This is where resampling and simulation techniques are very useful. Here we use either the original data or simulate new data to explore our hypothesis.

These topics rely on a mixture of statistical literacy and programming competencies. These materials are aimed to provide background and practical tools to address this.

**Note**: The materials are under active development. The learning objectives in brackets will be addressed in further versions of these materials.

::: {.callout-tip}
### Learning objectives

- Understand which resampling techniques there are and when to use them.
- Analyse data through permutation techniques
- (Bootstrapping)
- (Cross-validation)
- (Simulation data)
:::


### Target audience

This course is aimed at researchers and data analysts with an intermediate level of statistical and programming knowledge.

### Prerequisites

Confident in the use of R / Python; basic knowledge of statistics (e.g. attended the [Core statistics](https://cambiotraining.github.io/corestats/) course).


<!-- Training Developer note: comment the following section out if you did not assign levels to your exercises -->
### Exercises

Exercises in these materials are labelled according to their level of difficulty:

| Level | Description |
| ----: | :---------- |
| {{< fa solid star >}} {{< fa regular star >}} {{< fa regular star >}} | Exercises in level 1 are simpler and designed to get you familiar with the concepts and syntax covered in the course. |
| {{< fa solid star >}} {{< fa solid star >}} {{< fa regular star >}} | Exercises in level 2 combine different concepts together and apply it to a given task. |
| {{< fa solid star >}} {{< fa solid star >}} {{< fa solid star >}} | Exercises in level 3 require going beyond the concepts and syntax introduced to solve new problems. |


## Authors
<!-- 
The listing below shows an example of how you can give more details about yourself.
These examples include icons with links to GitHub and Orcid. 
-->

About the authors:

- **Martin van Rongen**
  <a href="https://orcid.org/0000-0002-1441-367X" target="_blank"><i class="fa-brands fa-orcid" style="color:#a6ce39"></i></a> 
  <a href="https://github.com/mvanrongen" target="_blank"><i class="fa-brands fa-github" style="color:#4078c0"></i></a>  
  _Affiliation_: Bioinformatics Training Facility, University of Cambridge  
  _Roles_: writing - review & editing; conceptualisation; coding
- **Matt Castle**
  _Affiliation_: Bioinformatics Training Facility, University of Cambridge  
  _Roles_: writing - review & editing; conceptualisation
  
<!--
## Citation

 We can do this at the end 

Please cite these materials if:

- You adapted or used any of them in your own teaching.
- These materials were useful for your research work. For example, you can cite us in the methods section of your paper: "We carried our analyses based on the recommendations in _TODO_.".

You can cite these materials as:

> TODO

Or in BibTeX format:

```
@Misc{,
  author = {},
  title = {},
  month = {},
  year = {},
  url = {},
  doi = {}
}
```
-->
