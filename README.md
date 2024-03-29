# Summary of the GitHub Repository: Analysis of the Modern Olympic Games Dataset

## Overview
The ‘dataset on the modern Olympic Games’ comprises all the Games from Athens
1986 to Rio 2016. The Olympics is more than just a quadrennial multi-sport
world championship. It is a lens through which to understand global history,
including shifting geopolitical power dynamics, women’s empowerment, and the
evolving values of society.
In this analysis, our goal is to shed light on major patterns in Olympic history.
How many athletes, sports, and nations are there? Where do most athletes
come from? Who wins medals? What are the characteristic of the athletes (e.g.,
gender and physical size)?


Our analytical journey within this repository is twofold. Initially, we dive deep into Exploratory Data Analysis (EDA), Statistical Analysis, and Data Visualization to unearth fundamental patterns and characteristics within the Olympic history. Subsequently, we pivot towards a more focused inquiry: assessing the impact of hosting the Olympics on a country's performance in terms of medals won.

## Dataset Description
The dataset encapsulates a comprehensive collection of 271,116 entries across 17 descriptive fields, each entry representing an individual athlete's participation in an Olympic event. The fields encompass:

- `ID`: Unique identifier for each athlete
- `Name`: Athlete's name
- `Sex`: Gender (M or F)
- `Age`: Age in years
- `Height`: Height in centimeters
- `Weight`: Weight in kilograms
- `Team`: Team name
- `NOC`: National Olympic Committee 3-letter code
- `Games`: Year and season of the games
- `Year`: Year of the event
- `Season`: Season (Summer or Winter)
- `City`: Host city
- `Sport`: Sport category
- `Event`: Specific event
- `Medal`: Type of medal (Gold, Silver, Bronze, or NA)
- `Region`: Country that clinched the title
- `Notes`: Ancillary notes pertinent to the event

## Repository Structure

### Notebook 1: Project_Olympics
The first notebook in this repository is dedicated to a comprehensive EDA, Statistical Analysis, and vivid Data Visualization. The analysis pivots around several pivotal questions:

- What is the distribution of athletes, sports, and nations throughout the Olympic history?
- Which nations have been predominant, and how has this dominance evolved?
- What are the defining characteristics of the athletes, in terms of gender, physicality, and performance?
  
This initial analysis sets the stage for a deeper understanding of the dataset, providing a foundation for the subsequent, more focused inquiries.

### Notebook 2: Olympics_Hypothesis
The second notebook takes a more targeted approach, exploring the influence of hosting the Olympics on a nation's performance, specifically in the context of medal tallies. The analysis unfolds through a series of methodical steps:

1. **Identification of Frequent Hosts**: Pinpointing countries that have hosted the Olympics at least twice, recognizing their unique position in the dataset.
2. **Aggregation of Medal Tally**: Collating the total medal counts for these nations, presenting a holistic view of their Olympic achievements.
3. **Comparative Analysis**: Dissecting the medal tally of hosting versus non-hosting scenarios for these nations, offering a comparative perspective.
4. **Statistical Testing**: Employing rigorous statistical methods to validate whether hosting the Olympics significantly influences a country's performance in terms of medals won.

The culmination of this exercise is to address the pivotal question: "Does hosting the Olympics improve performance on the medals table?"

## Conclusion
This repository offers a detailed and structured analysis of the Olympic Games, aiming to understand the historical, cultural, and societal narratives reflected in the data, and to ascertain the impact of hosting the Olympics on a country's medal tally.

Dataset : https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results?resource=download
