---
date: "2016-04-27T00:00:00Z"
external_link: https://maricultura-gp.shinyapps.io/maricultura-app/
image:
  caption: Photo by Toa Heftiba on Unsplash
  focal_point: Smart
summary: An interactive web-based tool to identify the most suitable, productive, and profitable sites for offshore marine aquaculture development in Brazil.
tags:
- Demo
title: Maricultura Planning Tool
---

My peers and I built an interactive Shiny application that can guide planning efforts for aquaculture development. First, we defined input and output parameters for the app. Then, we integrated these parameters to our three suitability models (site suitability, productivity, and profitability). The interface of the app was created with Shiny using R version 3.6.1.
 
Inputs 
All the constraints used in the site suitability analysis were transformed into inputs that can be modified by the app users, as well as the life history parameters in the productivity assessment, and the costs in the profitability assessment.  The app will run all the suitability models based on the inputs provided by the user. 
 
Outputs
The main outputs created by the app are three maps, one for each model. The site suitability map shows parcels identified as suitable for aquaculture, the productivity map shows biomass (MT/cell), and the profitability map shows profits (USD/cell). All maps can be downloaded in TIFF grid format for further analysis. Two additional outputs are a total suitable area chart and percentage exclusion chart.
