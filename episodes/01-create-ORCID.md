---
title: "How to Create an ORCID"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- How can I create or update my ORCID profile?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Describe who runs ORCID and how it can support open science
- Describe to someone how to create or update an ORCID profile

::::::::::::::::::::::::::::::::::::::::::::::::

## What is an ORCID?

ORCID stands for Open Researcher and Contributor ID. It is a 16-digit unique identifier for scholarly authors. You can think of it as an online curriculum vitae. 
It can be very helpful for: 

* Disambiguation of authors with similar names
* Tracking individual author name changes
* Submissions to journals and grant applications

Creating and maintaining an ORCID record allows you to claim your scholarly online presence. You have the autonomy to list your works, grants, affiliations, etc. On a larger scale, departments may be interested in their faculty having well maintained records to aid in tracking of scholarly output. ORCID has an integration with many different tools online which we will cover in the next episodes. By curating the ORCID record, researchers can save time later with these integrations that will auto-populate other things they need.  


:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Steps to Create an ORCID

1. Go to the ORCID homepage: https://orcid.org/ 
2. Click on “Sign in / Register” in the top right corner
3. If you already have an ORCID record, try signing in
4. If you do not have an ORCID record, click “Register now”. 
5. Add a backup email to your account so you can always retrieve your account




::::::::::::::::::::::::::::::::::::: callout

If an account with your name already exists it may ask if it is you. If so, follow the prompts to retrieve this account. 

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?

What is the output of this command?

```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: solution 

## Output
 
```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution 

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

::::::::::::::::::::::::::::::::::::: callout

Callout sections can highlight information.

They are sometimes used to emphasise particularly important points
but are also used in some lessons to present "asides": 
content that is not central to the narrative of the lesson,
e.g. by providing the answer to a commonly-asked question.

::::::::::::::::::::::::::::::::::::::::::::::::


## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/

