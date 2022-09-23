---
date: "2021-04-15T00:00:00Z"
external_link: ""
image:
  caption: Photo by <a href="https://unsplash.com/@at8eqeq3?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Dmitry Grigoriev</a> on <a href="https://unsplash.com/s/photos/bee?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  focal_point: Smart
summary: This project shows how to download and combine climate data from the NCDC with data on bee colonies from the USDA using R.
tags:
- Data Science
title: Bee Colonies and Climate—A Data Project
url_code: "https://github.com/pawelrybacki/bee-colony-stressor-climate/blob/main/stressor_climate.csv"
url_dataset: "https://github.com/pawelrybacki/bee-colony-stressor-climate/blob/main/stressor_climate.csv"
url_slides: ""
url_video: ""
---

### Combine Data on Bee Colonies and Climate

## Project Description:
This coding project was originally a part of a larger team project whose goal was to establish relationships among variables related to bee colony losses, bee colony stressors, and climate.

The data describing bee colonies come from the Bee Colonies dataset from
[TidyTuesday](https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-01-11/readme.md#bee-colonies).
This source has two datasets – related to colonies and stressors. The
stressor dataset has 5 variables and 7,332 observations.

Climate data come from the National Climatic Data Center using
API through the `rnoaa` package, an R interface to NOAA climate data.

The code uses `rnoaa` to download, transform, and
merge data so that the temperature, precipitation, and bee colony
stressor types and effects for all 50 states (if applicable) and all
quarters of the years 2015-2021 are present in one final dataset called
`stressor_climate.csv`.

## The Dataset:
The dataset is [here](https://github.com/pawelrybacki/bee-colony-stressor-climate/blob/main/stressor_climate.csv).

## The Code:
To see how to obtain and combine the two datasets, check out [my code on GitHub](https://github.com/pawelrybacki/bee-colony-stressor-climate).



