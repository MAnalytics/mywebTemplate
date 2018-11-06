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

This tool can be downloaded directly from: https://github.com/MAnalytics/Creating-a-spatial-grid-system-over-an-area   

# 2. BDC_GeoConverter: 

This tool is developed to complement an online tool called `Geoconverter` (http://geoconvert.mimas.ac.uk/index.html). The Geoconverter is used for matching changed geographical units in the UK, or apportioning a dataset from an original geographical demarcation to a modified/changed geographical demarcation. For example, during 2011 census in the UK, it can be observed that some of the census units, namely LSOAs and OAs, have been modified (either merged or split) when compared to their corresponding 2001 census units. In Birmingham city for example, 10%* of 2011 LSOA units have been affected. 

In a longitudinal analysis as an example, the aforementioned changes is `problematic`. In an effort to address this, the Geoconverter tool is created, and to apportion any data from 2001 unit demarcation to 2011 unit demarcation, and vice versa. Alternatively, the tool can be used to generate a `look-up table` that provide a summary of those changes for the entire UK.

The look-up table is particularly useful for anyone who might want to carry out the apportioning tasks programmatically.

Now, the `BDC_Geoconverter` is created to deal with two problems that are not addressed by the online Geoconverter. First, the online Geoconverter fails to capture some OAs that exist in 2001 and still exist in 2011, but have now been renamed. This is scenario is most common in Greater Glasgow where high-rise building were demolished and re-built as smaller building units, and therefore renamed.

Please note that the work of BDC_Geoconverter still depends largely on the look-up table generated from the online Geoconverter.

This tool can be downloaded directly from: https://github.com/MAnalytics/BDC-Geoconverter.








