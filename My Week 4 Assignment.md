---
title: "README.md"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

Download the file and put the file in the data folder
Unzip the file
unzipped files are in the folderUCI HAR Dataset. Get the list of the files
Read data from the files into the variables
Read the Activity files
Read the Subject files
Read Fearures files
Look at the properties of the above variables
Concatenate the data tables by rows
set names to variables
Merge columns to get the data frame Data for all data
Subset Name of Features by measurements on the mean and standard deviation
Subset the data frame Data by seleted names of Features
Check the structures of the data frame Data
Read descriptive activity names from “activity_labels.txt”
facorize Variale activity in the data frame Data using descriptive activity names
check
appriopriately label the data set with descriptive variable names
check
create a second independent tidy data set, and out
then produce a codebook


