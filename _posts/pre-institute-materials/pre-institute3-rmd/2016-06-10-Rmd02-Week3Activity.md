---
layout: post
title: "Pre-Institute Week 3 Assignment"
description: "This page details how to complete the activity for pre-Institute week 3."
date: 2016-05-18
dateCreated: 2016-01-01
lastModified: 2016-05-26
estimatedTime:
packagesLibraries:
authors: [Megan A. Jones, Leah Wasser]
categories: [tutorial-series]
tags:
mainTag: pre-institute3-rmd
tutorialSeries: pre-institute3-rmd
code1:
image:
 feature: data-institute-2016.png
 credit:
 creditlink:
permalink: /tutorial-series/pre-institute3/rmd02
comments: true
---

## About
THis tutorial covers the NEON Pre-Institute Week 3 assignment. If you already
are familiar with R markdown and knitr, you may be able to complete the assignment 
without working through the next two tutorials. 

<div id="objectives" markdown="1">

## Deadlines
**Due:** Please have this activity merged into the
**NEON-WorkWithData/DI16-NEON-participants** GitHub repo by 11:59pm on
16 June 2016.

## Download Data

<a class="btn btn-inverse" href="https://ndownloader.figshare.com/files/5282317" target="_blank">Teakettle
Data</a>

</div>


To begin, please do the following:

1. Download data from the Teakettle Field site - from the NEON Data Skills 
Figshare Repository.
2. Unzip the data into a `data` directory on your computer. The path to your data 
will look like this:

`\data\data-institute-2016\NEONdata\TEAK\2013\`

We will be using the GeoTIFF raster files in the “lidar” subdirectory of the download.

## Create RMD File

Create a new .Rmd file. 


* Within the RMD file, create a script that does the following: 

  * Open and plot at least 2 raster files in the `/lidar/ directory using the `plot()` 
  function in the raster package.
  * Create a histogram for each raster file that shows the distribution of values 
  in the file.
  * Be sure to label your plots appropriately.
  
* Break up your code into RMD chunks that makes sense to you. Use Markdown to 
document the steps that you are taking to "process" the data. Provide some summary
discussion of the results at the end of the document. HINT: the raster: Teak_lidarCHM 
represents TREE HEIGHT for the field site. You might comment on how tall the 
trees are on average at the site.

Please include the following in your Rmd file:

* Your name as an author of the file.
* Explanatory text that describes your workflow in the Markdown portions of the
R Markdown document. This text may include the data being used and plotted.
* 3 or more named R code chunks.
* OPTIONS: Code chunk options in at least 1 chunk. E.G.: warnings = 'hide'

## Knitr: RMD to HTML

Once you have completed the steps above:

* Knit your .Rmd file to html.  
* Submit both the .Rmd and the .html documents to the **/participants/TEAKRmd-week3**
directory in the **NEON-WorkWithData/DI16-NEON-participants** GitHub repository.

## Supporting Materials

The next two tutorials, will walk you through how to create an RMD file and knit 
to HTML in R. Visit the NEON Data Skills tutorial below for help opening and plotting
rasters in R:

<a class="btn btn-inverse" href="http://neondataskills.org/R/Plot-Rasters-In-R/" target="_blank">Plot Raster Data in R</a> 


Now continue on to the
[next tutorial]({{site.baseurl}}/tutorial-series/pre-institute3/rmd03)
to learn about R Markdown.