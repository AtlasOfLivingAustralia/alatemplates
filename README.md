# alatemplates
Create R Markdown files that conform to the Atlas of Living Australia (ALA) style guide

# Installation

Install the `alatemplates` package
```{r}
if (!requireNamespace("devtools")) install.packages("devtools")
devtools::install_github("AtlasOfLivingAustralia/alatemplates")
```

# Load template files

To create a new template R markdown file, select **File** --> **New File** --> **New R Markdown** to open the "New R Markdown" pane

In the "New R Markdown" pane, select **From Template** and choose from the list of {alatemplates}.

The templates to choose from are:

* `rmarkdown-standalone` = A standalone `Rmd` file that renders to html. This is for documents intended to share with others (in webpage style html format), but will not be posted on the ALA Labs website
* `rmarkdown-website-post` = A document intended as a Post on the ALA Labs website. This template uses a template `Distill` heading to work correctly with the ALA Labs website
  
  *Note: If this template does not render correctly, you may need install the Distill package using* `install.packages("distill")`
