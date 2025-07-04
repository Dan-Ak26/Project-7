# 🏃‍♂️ Analysis of Activity Monitoring Data

**Author:** Daniel Aklilu  
**Date:** July 4, 2025

---
## 💻 Link to Project : 
file:///C:/Users/Danie/Desktop/John%20Hopkins%20University%20Data%20Science%20Certification/Project-7/PA1_template.html




## 📘 Project Description

This project is part of the **Johns Hopkins University Data Science Specialization** and explores data from a personal activity monitoring device.
The device recorded the number of steps taken in 5-minute intervals each day over a two-month period (October–November 2012).

The main goals of this analysis are to:

- Summarize the total number of steps taken per day
- Explore average daily activity patterns
- Impute missing data
- Compare activity patterns between weekdays and weekends

---

## 📁 Files

- PA1_template.Rmd: R Markdown file with code and analysis
- PA1_template.html: Final rendered HTML report
- activity.csv: Raw dataset used in the analysis
- README.md: This file

---

## 📦 Packages Used

- **dplyr** – for data wrangling
- **ggplot2** – for visualization
- **lubridate** – for date parsing
- **knitr** – for report generation

---

## 🔍 Analysis Summary

- **Step counts per day:** Summarized with histograms and descriptive statistics.
- **Daily activity pattern:** Calculated average steps per 5-minute interval.
- **Missing data:** Imputed using the interval mean.
- **Weekday vs. Weekend:** Compared average interval activity patterns using faceted plots.

---

## 📊 Final Plot

The final graph shows step activity patterns for weekdays and weekends side-by-side, using facet_wrap() in ggplot2.
This reveals differences in behavior based on the day type.

---

## 🚀 How to Run

1. Open PA1_template.Rmd in RStudio
2. Make sure the dataset activity.csv is in the correct folder (./Project-7)
3. Click **Knit** to generate the PA1_template.html report

---

## 📚 Dataset Source

Data for this project comes from [this activity monitoring dataset](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip),
provided by Coursera's Reproducible Research course.

---
