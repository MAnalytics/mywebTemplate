+++
# Project title.
title = "Delineators: Geographical Space"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "A set of tools for delineating a geographical space"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Delineators"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = " "
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

# Introduction

This section describes a set of analytical tools for delineating a geographical space. A `geographical space` refers to a large geographical area, such as a town or a  city, subdivided into a set of smaller administrative or non-administrative units.  An example of an administrative unit is the district, neighbourhood, counties or ward demarcations, while an example of a non-administrative unit is a system of regular grid or street network.

In spatial analysis, it is often required to **modify** (as in the example of an administrative unit) or **create** (as in the example of a non-administrative unit) some of these units, based on a given geographical specification. The following subsection will introduce two tools and how to download them. 

# 1. Spatial grid creator: 
This tool creates a system of regular grids over a geographical space. Given a spatial boundary of a city (in Esri format - .shp), this tool would detect the spatial extent of the city and generate a system of square grid over the city, in accordance with the specified size. Below are examples regular grid systems of varying sizes created over the City of Chicago.

**Insert figs. here:**

This tool can be downloaded directly from: https://github.com/geoMADE/Creating-a-spatial-grid-system-over-a-study-area   

# 2. Geo_Converter: 
This tool is developed to complement an online tool called `Geoconverter` (http://geoconvert.mimas.ac.uk/index.html). The Geoconverted is an online tool for matching changed geographical units in the UK. 

**Problem:** Between 2001 and 2011 census periods in the UK, a number of smaller census units, such as LSOA and OA have changed. 