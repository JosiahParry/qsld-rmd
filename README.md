## Introduction to R Markdown

This repository contains the materials used for an introduction to R Markdown for the Queensland Department of Treasury. 

The presentation files are `presentation.Rmd` and `presentation.html`.

A number of sample documents were created to display the different forms that an Rmd can take. 

- `pop-proj-eda.Rmd`: This file is intended to illustrate how an Rmd can be used for literate exploratory data analysis.
- `pop-proj-report.Rmd`: Illustrates that you can create pdf reports using an Rmd. Combine this with `pagedown` and you can make a beautiful pdf reports. Moreover this document can be knit to both an html document or a pdf, each with it's own unique character. Knit to html to see the floating table of contents.
- `age-pop-parameterized.Rmd`: Looks at utilizing input parameters for semi-customizable reporting.
- `pop-proj-flexdb.Rmd`: Combines parameterization with `flexdashboard` and uses `plotly::ggplotly()` to illustrate how simple charts can become an interactive dashboard. 
  - This examples can be interacted with on RStudio's demo Connect server [here](https://colorado.rstudio.com/rsc/content/6407/pop-proj-flexdb.html).

If you have any questions, please either submit an issue, send me a DM on twitter (@josiahparry), or email me! 
