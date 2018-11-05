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

This section will introduce a set of analytical tools for delineating a geographical space will be introduced. A `geographical space` refers to a large geographical area, such as a town or a  city, subdivided into a set of smaller administrative or non-administrative units.  An example of an administrative unit is the district, neighbourhood, counties or ward demarcations, while an example of a non-administrative unit is a system of spatial grids and a street network.
In spatial analysis, it is often required to **modify** (as in the example of an administrative unit) or **create** (as in the example of a non-administrative unit) some of these units, based on a certain geographical specification. Below are examples:

# 1. Spatial grid creator: 
This tool creates a system of square spatial grids over a geographical space. Given a spatial boundary (.shp) of a city, this tool would detect the spatial extent of the city and generate a system of square grid, of a specified size, over the city. Below are examples of grid systems, created by this tool, of varying sizes created over the City of Chicago.

