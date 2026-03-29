# Project-3---FHWA-
-------------------------------------------------------------------------------
Introduction
-------------
This Project was completed for the Federal Highway Administration (FHWA). We were tasked with creating relevant plots/graphs/charts to identify trends in the national highway travel survey data. 5 graphs were created for this data. A bar chart, histogram, boxplots, and two time series plots. The Intelligent Driver Model (IDM) Simulation was also created in Python. After creating the function for this simulation it was then graphed and compared to real data from the NGSIM data set

----------

This repository has a fully reproducible Python workflow for cleaning, processing, and visualizing data from the NHTS and NGSIM survey/observation data. The project takes the raw variables and processes them into visual summaries in the form of bar charts, histograms, boxplots, time series plots, and a simulation. These help identify trends in household travel behavior and vehicle characteristics.

Data Requirements:
The data needs to contain the following variables to have the same plots as this workflow: Vehicle Type, Vehicle Age, Vehicles Per Household, Speed, Acceleration, and Position

To run this script pandas, numpy, matplotlib, and seaborn will need to be imported into the code.

--------------------------------------------------------------------------------
Overview of Charts
--------------------------------------------------------------------------------
Histogram - 
  Displays the distribution of vehicles per household helping to identify common household vehicle counts

Bar Chart - 
  Shows the number of vehicles per household and how many households there are of each type

Boxplots - 
  Shows the vehicle age across different vehicle types

Line Series Plots - 
  An acceleration vs time and position vs time graph showing how a cars trajectory and dynamics change over the observed time period


--------------------------------------------------------------------------------
IDM Simulation
--------------------------------------------------------------------------------
The IDM simulation has defined functions that compare the trajectory of the leader and create a simulated follower. This simulation follower is compared to a real follower data for that leader trajectory. Different trajectories can be tested and shown on the graph by changing the trajectory_number (anything from 1-16). 

Contents
---------------------------------------------------------------------------------
NHTS(in).csv - 
  NHTS Survey Data used in the coding file

NGSIM(in).csv - 
  NGSIM Simulation Data used for creating the IDM simulation

Project 3 Code - 
  An .ipynb coding file with the code for creating each visualization and for the IDM simulation

README - A description of the project and guide of how to use the contents

Annotated Code Document - 
  Document that explains what each line of code does and why it's there

Scope of Work - 
  Document that outlines the tasks that would be taken on for this project, the timeline, and the deliverables

Gantt Chart - 
  A chart that outlines all tasks, when they will be done, and who they will be done by

Report - 
  A report that outlines the methods in a reproducible way and that explains the results of the project

