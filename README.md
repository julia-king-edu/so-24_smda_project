
# Conspiracy Narratives and Public Perception of 15-Minute Cities on YouTube

## Project Overview

This project investiages the public discourse surrounding the concept of 15-minute cities on YouTube, focusing on the emergence and impact of conspiracy narratives during the COVID-19 pandemic. Through analysis of YouTube videos and their  comments, this project seeks to understand the development of the conspiracy theory and analyze engagement metrics over time.

## Research Objectives

The hypotheses tested in this project are:

1. Videos produced before the first spike in public interest are more likely to be non-conspirative compared to those uploaded during and after the spike.

2. Comments under conspirative videos express higher levels of negative sentiment compared to comments under non-conspirative videos.

3. The engagement metrics (e.g., likes, comments, shares per view) of conspirative videos differ significantly from those of non-conspirative videos, with conspirative videos having higher engagement rates per view.

## Methodology

The following steps were taken to answer the above hypotheses:

1. Google Trends was used to identify spikes in public interest concerning 15-minute cities during the COVID-19 pandemic.

2. For each week within the relevant timeframe, the IDs of the most-viewed YouTube videos related to 15-minute cities were collected.

3. Relevant metadata and comments for the identified videos were obtained using the YouTube API.

4. A sample of videos was classified as either conspirative or non-conspirative based on their title and description.

5. Multiple supervised text analysis models were trained to classify the remaining dataset, with performance evaluation ensuring that the best-performing model was used to classify the videos.

6. The LEIA emotion classification model was used to analyze the sentiment expressed in the comments under each video.

7. Statistical tests were conducted to evaluate the hypotheses.

## Repository Structure

    /data: Contains datasets generated & used in analysis

    /img: Contains the visualizations generated in the jupyter notebooks

    /presentation: Contains files used to generate the project presentation on 03.07.2024 and the registration

    /report: Contains the files used to generate the report handed in on 21.08.2024

    jupyter notebooks: implement the data collection, processing and analysis steps. Should be run in order and can regenerate the entire data folder.

    common_functions.py: helper file to organize functions used in multiple of the jupyter notebooks