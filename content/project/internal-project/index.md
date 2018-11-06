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

This section describes a set of analytical tools for delineating a geographical space. A `geographical space` refers to a large geographical area, such as a town or a  city, subdivided into a set of smaller administrative or non-administrative units.  An example of an administrative unit is a district, neighbourhood, county or ward demarcation, while an example of a non-administrative unit is a system of regular grid or street network.

In spatial analysis, it is often required to **modify** (as in the example of an administrative unit) or **create** (as in the example of a non-administrative unit) some of these units, based on a given geographical specification. The following subsection will introduce two tools and how to download them. 

# 1. Spatial grid creator: 
This tool creates a regular grid system over a geographical space. The tool requires a user to supply a spatial boundary of an area (in Esri format - .shp) and specify the grid size. The tool detects the spatial extent of the boundary and automatically create a system of regular grids, of the size specified, over the area. Below are examples regular grid systems of varying sizes, created by this tool, over the City of Chicago.

**Insert figs. here:**

**Applications**
The use of arbitrary grid system is common in crime analytics for some special reasons, which include confidentiality protection and as alternative in absence of a reasonably small adminstrative units. In particular, the grid systems have been used in hotspot policing in order to enable a more focussed targetting of problematic areas (Mohler et al. 2011).

This tool can be downloaded directly from: https://github.com/MAnalytics/Creating-a-spatial-grid-system-over-a-study-area   

# 2. Geo_Converter: 
This tool is developed to complement an online tool called `Geoconverter` (http://geoconvert.mimas.ac.uk/index.html). The Geoconverted is an online tool for matching changed geographical units in the UK. 

**Problem:** Between 2001 and 2011 census periods, a number of smaller census units, such as LSOA and OA have changed.... 