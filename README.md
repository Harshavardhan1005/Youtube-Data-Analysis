# Youtube-Data-Analysis
## Building data pipeline for Youtube data analysis using AWS Cloud Services
This project perform analysis on the structured and semi-structured youtube videos data based on the video categories and the trending metrics.

## Dataset Description
This Kaggle [dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new) contains statistics (CSV files) on daily popular YouTube videos over
the course of many months. There are up to 200 trending videos published every day
for many locations. The data for each region is in its own file. The video title, channel
title, publication time, tags, views, likes and dislikes, description, and comment count
are among the items included in the data. A category_id field, which differs by area, is
also included in the JSON file linked to the region.

## Tech Stack
* Languages: SQL,Python
* Services: AWS S3, AWS Glue, QuickSight, AWS Lambda, AWS Athena, AWS IAM

## Architecture
![Alt text](Architecture.jpg?raw=true "Title")

## Visualization using QuickSight
![Alt text](Youtube_Data_Analysis.pdf?raw=true "Title")
