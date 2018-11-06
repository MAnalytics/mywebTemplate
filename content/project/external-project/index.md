+++
# Project title.
title = "Predictors: Geographical Processes"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "A set of tools for generating predictive hotspots of geographical point processes"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Predictors"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by Toa Heftiba on Unsplash"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++


# Introduction

This section introduces a set of predictive analytics for different geographical processes, such as crime and footfalls. The links to downloading these tools are also provided.

# 1. Crime Hotspot Predictors

This...

# 2. Footfall Predictor

This tool was developed as a part of [Surf Project](http://surf.leeds.ac.uk/) funded by [ESRC Future Research Leaders](https://esrc.ukri.org/funding/funding-opportunities/future-research-leaders/) scheme. The tool, named as `Leeds Footfall Predictor`, built on the work led by [Nick Malleson](http://www.nickmalleson.co.uk/) which determined that the daily footfall rates observed in the Leeds city centre can be explained in terms of external variables, such as temperature, rainfall and holidays. The research involved the application of different machine learning algorithms to a combination of these variables (predictors) and subsequently compared the accuracies of the former. It was established that the `Random Forest` algorithm [Breiman, 2001](https://link.springer.com/article/10.1023/A:1010933404324) is the most accurate for forecasting footfall rates. Therefore, the Random Forest algorithm, as implemented in R [Liaw and Wiener, 2002](https://www.r-project.org/doc/Rnews/Rnews_2002-3.pdf), was employed in the development of the ‘Leeds Footfall Predictor’, using the `RShinydashboard` platform. 
