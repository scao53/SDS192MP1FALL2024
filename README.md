# Mini-Project 1

*Due Monday 9/30 at 9pm.*

## Basic outline

Your project will create **two non-redundant data visualizations** by **each person** using the travel dataset in the data folder. Each project needs to generate at least two types of graphs including bar graph, histogram, boxplot, and scatterplot, etc. You and your partner will then write up your findings in a short data-driven article of **no more than 900 words**. Your deliverable will be written in Quarto.

## Background reading

The transport system is a pillar for ensuring social equity (Pagliara & Di Ciommo, 2020). People often need to travel to work, study, connect with other people, shop groceries, attend medical appointments, and participate in fun events. There have been uneven distributions of travel resources in the current built evnrionment for disabled people, which casue barriers to access for them (Levine & Karner, 2023). The built environment needs to be more inclusive, so disabled people can travel more easily and freely and disability can be shown as human diversity (Levine & Karner, 2023). 

Read <strong>Transportation patterns demonstrate inequalities in community participation for working-age Americans with disabilities</strong> (access Perusall via our course Moodle page) to learn how the National Household Travel Survey (NHTS) data can be used to study inequality and economic and social participation from a critical disability lens and provide policy implications of building a more equitable and inclusive transport system. <strong>You only need to focus on the qualitative part of this paper and please be creative in conducting your own analysis!</strong>

## Datasets

Conducted by the Federal Highway Administration, the [NHTS](https://nhts.ornl.gov/) is the authoritative source on the travel behavior of the American public. It is the only source of national data that allows one to analyze trends in personal and household travel. It includes daily non-commercial travel by all modes, including characteristics of the people traveling, their household, and their vehicles.

I have constructed the travel dataset from the 2017 NHTS data. This dataset focuses on travel behaviors by length of disability and other demographic information. The NHTS asks respondents whether they have a medical condition "that makes it difficult to travel outside of home". Those who respond yes are defined to have a travel disability in this project.

Before producing your analysis, you will study the [**NHTS_OUR_DATASET_CODEBOOK**](codebook/NHTS_OUR_DATASET_CODEBOOK.pdf) to select variables for your analysis. To help you make sense of the travel dataset, I will note that the unit of observation in this dataset is a person. You can review [the user guide](codebook/NHTS2017_UsersGuide_04232019_1.pdf) and [the original codebook](codebook/original_codebook.pdf) to understand the context of the data. 

## Getting started

1. In RStudio, File > New Project > Version Control > Git and then copy and paste the "Clone" URL from your group's repo. Open `MP1.qmd` in RStudio.

## Suggestions

1. Complete your minimally viable product (MVP)! When working on any project:

* Don't try to do everything completely and perfectly from the beginning. This leads to perfectionist thinking, which leads to procrastination and "analysis paralysis."
* Do start by finishing a [MVP](https://www.forbes.com/sites/quora/2018/02/27/what-is-a-minimum-viable-product-and-why-do-companies-need-them/#178bd8a2382c). In other words:
    + [Done is better than perfect](https://lifehacker.com/done-is-better-than-perfect-5870379)
    + [Don't let perfect be the enemy of good](https://www.huffpost.com/entry/dont-let-the-perfect-be-t_b_158673)
* Once you're done your MVP, gather feedback on how your project works. Based on this feedback, then iterate and improve.

2. You **don't** need to do data wrangling for this project.

## Submitting the assignment

1. When you are done, render the document to an `.html` file, commit changes, and then push both the `.qmd` file and the `.html` file to GitHub. That's it for submission. You don't need to submit anything on Moodle.
2. Both group members: Fill out the peer evaluation [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSeply0dM7JAgv4Ot00ASRtBbSGdOmuFKsQGD9nxLBbAJ8MQ0Q/viewform?usp=sf_link).

## Assessment

You will be evaluated on the extent to which your mini-project demonstrates fluency in the following standards (the number in () indicates the maximum points you can earn for a paticulrar standard for this mini-project):

VISUALIZATION AESTHETICS (1.5)

* Do you use visual cues effectively on the plots?
* Are the values on your plots legible and clear?
* Are all visualizations mindful of the [data-ink ratio](https://sudharsanasai.medium.com/declutter-your-chart-with-data-ink-ratio-6f6908727842)?

VISUALIZATION CONTEXT (1.5)

* Do all visualizations have appropriately labeled axes, legends, titles, etc.? 
* Do your labels and titles accurately identify each row your data presents, variables, filters, geographic context, and temporal context?
* Are your axes set to an appropriate scale?

COMPOSING & INTERPRETING PLOTS (1.5)

* Have you selected appropriate plots based on the variable types presented in the dataset?
* Have you created two non-redundant data visualizations by each person?
* Has your project generated at least two types of graphs including bar graph, histogram, boxplot, and scatterplot, etc.?
* Have you customized the plots, making use of two available geoms and/or color palettes?
* Have you interpreted the data visualizations?
* Does your interpretation detail each row your data presents?
* Does your interpretation detail how the values in the variables you selected were measured?

GITHUB (1)

* Have you successfully followed the workflow, including cloning repositories, committing, pulling, pushing, and resolving simple merge conflicts if any?

AUTHORING MARKDOWN DOCUMENTS (1)

* Have you successfully formatted the report in Quarto as we discuss in class?
* Have you successfully authored the report in Quarto so that the final submission is production-quality, replete with data graphics and correct spelling and grammar?
* Have you explicitly stated your research question motivating your analysis?
* Does written text make a logical argument supported by your data analysis and communicate your findings effectively? From the report reader’s perspective, there should be no “superfluous” and non-informative output (e.g. instructions text). 
* Are all accompanying write-ups are coherent and respect the word count limit?
* Have you included citations (if any) as footnotes?
* Have you cited AI-generated content if you get help with your programming tasks?

CODE STYLING (1)

* Is your code clean, commented, and well-indented?

DATA ETHICS (1)

* Have you included at least one ethical concern in your summary?
* Have you included what you have learned from the assigned disability inclusion readings in your report and at least one policy implication for disabled people from the results of your data analysis?

## Disclaimer
The travel dataset used in this project are a subset of the NHTS data and **unweighted**. The results of your analyses **cannot** be generalized beyond the samples collected in this dataset.
