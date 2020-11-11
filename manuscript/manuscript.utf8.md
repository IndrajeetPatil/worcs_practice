---
title             : "The title"
shorttitle        : "Title"

author: 
  - name          : "First Author"
    affiliation   : "1"
    corresponding : yes    # Define only one corresponding author
    address       : "Postal address"
    email         : "my@email.com"
    role:         # Contributorship roles (e.g., CRediT, https://casrai.org/credit/)
      - Conceptualization
      - Writing - Original Draft Preparation
      - Writing - Review & Editing
  - name          : "Ernst-August Doelle"
    affiliation   : "1,2"
    role:
      - Writing - Review & Editing

affiliation:
  - id            : "1"
    institution   : "Wilhelm-Wundt-University"
  - id            : "2"
    institution   : "Konstanz Business School"

authornote: |
  Add complete departmental affiliations for each author here. Each new line herein must be indented, like this line.

  Enter author note here.

abstract: |
  One or two sentences providing a **basic introduction** to the field,  comprehensible to a scientist in any discipline.
  
  Two to three sentences of **more detailed background**, comprehensible  to scientists in related disciplines.
  
  One sentence clearly stating the **general problem** being addressed by  this particular study.
  
  One sentence summarizing the main result (with the words "**here we show**" or their equivalent).
  
  Two or three sentences explaining what the **main result** reveals in direct comparison to what was thought to be the case previously, or how the  main result adds to previous knowledge.
  
  One or two sentences to put the results into a more **general context**.
  
  Two or three sentences to provide a **broader perspective**, readily comprehensible to a scientist in any discipline.
  
  <!-- https://tinyurl.com/ybremelq -->
  
keywords          : "keywords"
wordcount         : "X"

bibliography      : ["r-references.bib", "references.bib"]

floatsintext      : no
figurelist        : no
tablelist         : no
footnotelist      : no
linenumbers       : yes
mask              : no
draft             : no

documentclass     : "apa6"
classoption       : "man"
output            : papaja::apa6_pdf
knit              : worcs::cite_essential
---



This manuscript uses the Workflow for Open Reproducible Code in Science [@vanlissaWORCSWorkflowOpen2020] to ensure reproducibility and transparency. All code <!--and data--> are available at <git@github.com:IndrajeetPatil/worcs_practice.git>.

This is an example of a non-essential citation [@vanlissaWORCSWorkflowOpen2020]. If you change the rendering function to `worcs::cite_essential`, it will be removed.



```r
# Seed for random number generation
set.seed(42)
knitr::opts_chunk$set(cache.extra = knitr::rand_seed)
```



# Methods
We report how we determined our sample size, all data exclusions (if any), all manipulations, and all measures in the study. <!-- 21-word solution (Simmons, Nelson & Simonsohn, 2012; retrieved from http://ssrn.com/abstract=2160588) -->

## Participants

## Material

## Procedure

## Data analysis
We used R [Version 4.1.0; @R-base] and the R-packages *papaja* [Version 0.1.0.9997; @R-papaja], and *worcs* [Version 0.1.6.2; @R-worcs] for all our analyses.


# Results

The mean of `wt` is 3.21725.

# Discussion


\newpage

# References

\begingroup
\setlength{\parindent}{-0.5in}
\setlength{\leftskip}{0.5in}

<div id="refs" custom-style="Bibliography"></div>
\endgroup
