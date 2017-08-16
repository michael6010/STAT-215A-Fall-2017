# STAT 215A, Fall 2017

This is the github repository for STAT 215A, Fall 2017.

Here you will find some useful resources and information about the peer grading system.

Feel free to post issues on this repository if you have any questions! That way everyone else can see your question and my answer and I don't have to answer the same questions a million billion times.
If you have a more sensitive question that you'd rather your peers not see, of course you can feel free to email me at rebeccabarter@berkeley.edu, and/or email Bin at binyu@stat.berkeley.edu. You can of course also talk to me after the lab or during office hours.



# Class times

**Lectures**:

Tuesdays & Thursdays, 11-12:30, Evans 344

**Labs**:

Fridays, 9-11, Evans 330

**Office Hours**:

*Bin*: TBA

*Rebecca*: TBA



# Useful resources

The following resources are excellent for both learning R and becomming a more advanced user.

- The [tidyverse website](http://www.tidyverse.org/). Much of what makes R powerful is the collection of packages developed by Hadley Wickham and the other lovely people over at RStudio encompassed in a the so-called "tidyverse". The tidyverse website provides a summary of all of its packages. The particularly useful ones will be `ggplot2` and `dplyr`.

- The ["Tidy Data"](https://www.jstatsoft.org/article/view/v059i10/v59i10.pdf) paper by Hadley Wickham will give you a feel for how to effectively mold in R your data for maximizing ease of usefulness. Note that the `reshape2` package is essentially obsolete and have been replaced by the `tidyr` package (part of the tidyverse). Specifically, the functions `melt` and `cast` have been replaced by the more intuitively named functions `gather` and `spread`, respectively.

We will also be using Git and GitHub a lot in this course. Here are some resources for figuring out what Git is and how to use it. I will add more as I come across them.

- For information on installing Git and setting up GitHub see their [website](https://github.com/).

- Software Carpentry has a thorough [Git and GitHub tutorial](http://swcarpentry.github.io/git-novice/) available for free.

# The lab assignments

There will be 4-5 lab reports throughout the semester. These reports are a *big deal*. It is in completing these reports that the real learning happens. You will get to apply what you've learned in the lectures and labs to real datasets (with real issues). You will also learn to tell a story with your analysis.

While you are allowed to discuss the projects with one another, each student must work on and hand in their own report.


The current tentative dates for the labs are as follows:

| Project title                  | Date released | Due date                | Peer grade submission date |
|--------------------------------|---------------|-------------------------|----------------------------|
| Redwood trees                  | September 1   | September 15 (2 weeks)  | September 22               |
| Linguistic Survey              | September 22  | October 5 (2 weeks)     | October 13                 |
| Stability of Linguistic Survey | October 13    | October 20 (1 week)     | October 27                 |
| *Midterm*                      | October 26    |                         | (graded by Rebecca)        |
| Cloud detection (group project)| October 27    | November 17 (3 weeks)   | November 21*               |
| fMRI (final project)           | November 17   | December 8 (3 weeks)    | (graded by Rebecca)        |




## The reports

Each report will be up to 12 pages (.pdf format) and will contain (1) a description of the problem, (2) a description of the data, (3) a description of the data cleaning procedure, (4) a description of the analytic methods, (5) a description of your results, and (6) relevant visualizations in all five stages.
There is no predetermined structure of the report, and it is entirely free form. There are only a few real requirements:

1. No code is to appear in the final pdf report.

1. Your report must not exceed 12 pages.

1. You must make an effort to communicate effectively. Think as if you are writing a blog post or an informal journal article.

1. Favour simplicity over complexity. It is much more important to be thorough and to communicate effectively than to come up with some super fancy modeling idea that no one understands. I would generally prefer that you spend more time on exploratory analysis (including visualization) than on modeling (especially on the earlier labs).

Keep in mind that there are two types of visualization: *exploratory* and *explanatory*. Exploratory visualizations are graphics that you produce to help *you* understand the data, whereas explanatory visualizations are final versions of a small subset of these figures that you produce to explain to *other people* what is in the data. Typically you will produce many, many exploratory plots and only a few key explanatory plots that answer specific questions. Choose your explanatory plots carefully, and ask the following question of every figure in your report: "Does this figure add anything? Is my story strictly worse when I remove it?" If the answer to either question is "no", then you should remove the figure. Just because you spent a lot of time making a really pretty figure, doesn't mean that it adds anything to your story. There have been many times in my life where I have spent an hour or two making a really awesome plot only to decide the next day that it is actually fairly irrelevant to my main points and removing it.

## Submitting the report

Your report and code will be submitted via github. I will post more details on this process once I have decided how to do it.

## Peer-grading

While you probably did a lot of really cool stuff in your own report, an excellent way to learn about other cool things is to see what other people did! This includes other exploratory and modeling ideas, neat R tricks, and issues with the data that you didn't notice or think of when you were doing your own analysis. So that you each have the opportunity to see a splattering of alternative approaches to the labs, we will be doing peer-grading for this class.

For each lab (except for the first and last one), you will each receive 3 reports from your peers to grade. A detailed rubric will be provided and you will be expected to provide both written feedback as well as a numeric grade on a variety of topics including communication, quality of data cleaning, relevance of visualizations, and reproducibility (can you easily re-compile their report). I will use these three grades for your report as a guide for grading, rather than as a final decision on your grade.

For the first lab, each student will only receive one lab to grade as a trial run (so that I can assess how you each grade). However, these grades will not be used, and I will thoroughly grade each of your first labs myself so that you can see what I expect both of your own lab and of the feedback you provide.

I will grade the final project lab.


## Frequently asked questions

**Do I have to use R? Can I use Python instead?**

We strongly recommend using R for several reasons.

1. The ability to embed R code, text and LaTeX formulae in RStudio is excellent and makes reproducibility a breeze.

1. Since we are doing peer reviewing, which includes a code-review, it will be *so* much easier for everyone if we are all using the same language.

If you *really, really* want to use Python, please talk to me in person in the lab or during Office Hours.


**Can I write my report using Jupyter Notebooks?**

No, sorry. One of the ways that we are ensuring that the reports are a reasonable length is to require a 12 page or less length limit. I also don't want to see any code in your final report.


**When should I start working on my lab?**

The labs, if done properly, will take you a long time. Ideally, you should be writing the report as you are going along in order to avoid a last minute hacking together of all of your analyses. Do not leave starting the lab until the last minute. You should start as soon as you receive the lab and work on it a little bit every day (rather than in one massive chunk). If you can easily do an entire lab in less than a week, then you have missed a lot in the data cleaning process.
