# Exploratory-Data-Analysis
Introduction
The prompt for this assignment can be found here. The goal is to produce a four of graphs using R's base plotting system. The code to produce each plot is found in a separate R file (plot1.R, plot2.R, etc) and each plot is found in a different png (plot1.png, plot2.png, etc).

Graph Descriptions
plot1: histogram for Global Active Power
plot2: line graph for Global Active Power over time
plot3: line graph for sub meterings 1-3 over time
plot4: line graphs for global active power, voltage, energy sub metering, and global reactive power over time
Data
This assignment uses data from the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets. In particular, we will be using the "Individual household electric power consumption Data Set". The data will be filtered to use only rows from 2/01/2007 and 2/02/2007.

Dataset: Electric power consumption [20Mb]

Description: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

The following descriptions of the 9 variables in the dataset are taken from the UCI web site:

Date: Date in format dd/mm/yyyy
Time: time in format hh:mm:ss
Global_active_power: household global minute-averaged active power (in kilowatt)
Global_reactive_power: household global minute-averaged reactive power (in kilowatt)
Voltage: minute-averaged voltage (in volt)
Global_intensity: household global minute-averaged current intensity (in ampere)
Sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
Sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
Sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.
Graph Descriptions
plot1: histogram for Global Active Power
plot2: line graph for Global Active Power over time
plot3: line graph for sub meterings 1-3 over time
plot4: line graphs for global active power, voltage, energy sub metering, and global reactive power over time
Usage
Each plot can be created by sourcing the plot's R code. For example, plot1.png can be created by running: source('plot1.R')

All plots can be created by running: source(create_plots.R) Note that this option reloads and reprocesses the data for each plot. This is because the assignment requires that each plot's R file contain the code to load the data.
