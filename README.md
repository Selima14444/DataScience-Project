# Indoor Air Quality Analysis Project

## Overview
This project focuses on the analysis of Indoor Air Quality, which is crucial for public health given that people spend over 80% of their time indoors. 
Indoor environments often have higher concentrations of pollutants compared to outdoor environments due to limited air exchange and various pollution sources such as renovation work, household items, and daily human activities.

## Project Objectives

The main goal of this project is to analyze and improve the understanding of indoor air quality by processing and analyzing data collected from multiple sensors. 
The project is divided into three sessions, each session involves several key tasks:

### Task 1: File Aggregation
**Objective**: Combine data from multiple files into single, comprehensive files for each sensor system.

**Process:**
- Aggregate all files with the same name into a single file.
- Ensure that the data is organized chronologically.
- Remove duplicate samples.

### Task 2: Data Synchronization
**Objective:** Synchronize data from different sensor modules to create a unified database.

**Process:**
- Standardize the sampling rate across all sensor data.
- Merge data from various files into a single .csv file.
- Ensure that there are no missing (NaN or NULL) values in the final dataset.

### Task 3: Signature Extraction
**Objective:** Identify and extract the average signature of various indoor activities.

**Process:**
- Segment the data based on different activities.
- Calculate the average time series for each activity, representing its typical signature.

### Task 4: Activity Recognition
**Objective:** Develop a methodology for recognizing different indoor activities based on sensor data.

**Process:**
- Propose and justify techniques for activity recognition.
- Implement the proposed methodology.
- Evaluate the performance of the activity recognition system.

## Sensor Modules Used
The project utilizes data from several sensor modules with varying characteristics. These modules measure different environmental parameters and are used to capture comprehensive data on indoor air quality. The modules include:

- Libelium New: 6 MOX sensors, sampled every 4 seconds
- PODs: 4 MOX sensors, sampled every 10 seconds
- Piano Thick: 9 MOX sensors, sampled every 10 seconds
- Piano Thin: 10 MOX sensors, sampled every 10 seconds
- Piano PICO: 3 MOX sensors, sampled every 10 seconds
