# SQMB 2022/23 – Summative Assessment 2

**DEADLINE: THURSDAY 27 APRIL AT NOON**

---

## Overview

In this assessment, you will:

- select a dataset and its associated research questions,
- analyse the data using **one linear model** (not multiple), and
- write a report about the data, the model, and your findings.

**Unlike previous assessments in this course, your report will not contain any code.
Rather, the report you submit will contain only your writing and any tables/figures that you use to summarise your data and/or model estimates.**

The aim is to give you practice writing about data and statistical models: an important skill for your dissertations and publications.

Please keep your report as succinct as possible.
As your academic careers continue, you'll find that many hours go into doing statistics, while disproportionately few words are actually spent on describing all that work (a sad reality!).
**Aim for a report that resembles a methods/results section of a published academic paper, containing all and only the information needed to understand your analysis.**


## What datasets can I choose from?

You'll find the four datasets you can choose from in the `data/` folder.
The research questions that go along with each of them are in `data/README.md`.
The `data/` folder also contains files that give a bit of background information about the original studies, including what each dataset's columns mean.

Each dataset has its own little quirks and decisions to be made that are representative of what you'll face when analysing real-life data.


## What do I need to report?

The following information must be provided somewhere in your write-up.

- **The dataset:** Which dataset did you choose? 
What is the associated research question?

- **Your chosen variables:** Which variables from this dataset will help you address the research question? 
What kind of variable are each of these? 
Give the appropriate summary measures (mean, median, mode; standard deviation, range) and visualisation(s) of the variables you will use.

- **Preparing the data for analysis:** How will categorical variables be coded?
For continuous variables, what transformations (if any) will you use?

- **The model:** What model did you fit? 
Why is this model appropriate for the data?

- **The model's results:** Provide the model summary formatted as a table. 
In writing, explain the coefficients that the model estimated and what they mean.

- **Conditional posterior probability distributions:** Which combinations of levels (for categorical variables) or values (for continuous variables) will you use to compute the model's conditional posteriors? 
Summarise the conditional posteriors in a table and in a plot (or multiple plots, if you wish).

- **Address the research question:** What do the model's estimates mean for the research question?


## Some tips

- **One model is enough** to answer both parts of your chosen research question.
The model you should be fitting will look pretty similar to models we've worked with in the course.

- **It is up to you how to structure your report.**
You might find it helpful to have one section for a descriptive approach to the data first (including summary measures and plots) and a separate section for the model and its results.
You can also think about how this information was presented in published academic papers that you enjoyed reading and aim to emulate that.

- If you're having a hard time choosing one datset to use, you could base your decision on which one is most similar to data you might want to work with in your own research.

- Writing figure captions is a great place to use your skills at summarising the patterns you see in plots.
It's really nice when figure captions give the audience a clear description and take-away.



## Any other questions?

Ask on Piazza.


## To submit your work

When you are satisfied, you can **submit your assessment** by:

1. rendering your Rmd file to PDF,
2. renaming the PDF to your exam number only, and
3. uploading it to Learn under Assessment. Choose the correct submission link for your program (undergraduate, postgraduate).

