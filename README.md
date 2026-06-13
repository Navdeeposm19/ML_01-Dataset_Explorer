# ML_01 — Dataset Explorer

## Overview
This project is for getting a basic understanding of Data Handling in ML. 
It loads, inspects, cleans, visualizes, and splits the data.

## Dataset
- Data is about median house prices in California.
- Sourced from scikit-learn.
- Has 20640 rows (examples), 8 feature columns, and 1 label column.
- House values are capped at $500k.

## Objective
The goal is to predict the median house price in California using 8 features. 
This is a **regression** problem.

## Features & Label
| Feature | Meaning |
|---------|---------|
| MedInc | Median income of the block |
| HouseAge | Median age of houses |
| AveRooms | Average rooms per household |
| AveBedrms | Average bedrooms per household |
| Population | Block population |
| AveOccup | Average household occupancy |
| Latitude | Location (north–south) |
| Longitude | Location (east–west) |

**Label:** MedHouseVal — median house value (the value we predict)

## Steps Performed
- Loading
- Inspection
- Cleaning
- Visualization
- Train–Test Split

## Tech Stack
- Python
- pandas
- matplotlib
- scikit-learn
- Google Colab

## What I Learned
I got hands-on experience working with a dataset. This gave me a basic 
understanding of data handling that will help me build further projects.
