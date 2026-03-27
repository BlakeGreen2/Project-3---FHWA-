# Project-3---FHWA-
-------------------------------------------------------------------------------
This repository has a fully reproducible Python workflow for cleaning, processing, and visualizing data from the NHTS and NGSIM survey/observation data. The project takes the raw variables and processes them into visual summaries in the form of bar charts, histograms, boxplots, time series plots, and a simulation. These help identify trends in household travel behavior and vehicle characteristics.

Data Requirements:
The data needs to contain the following variables to have the same plots as this workflow: Vehicle Type, Vehicle Age, Vehicles Per Household, Speed, Acceleration, and Position

To run this script pandas, numpy, matplotlib, and seaborn will need to be imported into the code.
--------------------------------------------------------------------------------
Overview of Charts
--------------------------------------------------------------------------------
Histogram
  Displays the distribution of vehicles per household helping to identify common household vehicle counts

Bar Chart
  Shows the number of vehicles per household and how many households there are of each type

Boxplots
  Shows the vehicle age across different vehicle types

Time Series Plots
  There are two time series plots, one that shows the leader position vs time and one that shows the leader acceleration vs time

--------------------------------------------------------------------------------
IDM Simulation:
--------------------------------------------------------------------------------
The IDM simulation has defined functions that compare the trajectory of the leader and create a simulated follower. This simulation follower is compared to a real follower data for that leader trajectory. Different trajectories can be tested and shown on the graph by changing the trajectory_number (anything from 1-16). 
