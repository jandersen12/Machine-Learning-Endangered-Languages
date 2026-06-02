
# Predicting a Language's Endangerment Level

> Experts estimate that 40% of the world's languages are currently endangered, but keeping track of a language's endangerment status is currently a highly manual and time intensive task. This project leverages machine learning techniques to answer the question *Can publicly available socioeconomic and geographic data approximate language endangerment status without requiring on-the-ground linguistic assessment?*.

[![Python](https://img.shields.io/badge/Python-3.10-blue)]()
[![UC Berkeley MIDS](https://img.shields.io/badge/UC%20Berkeley-MIDS-gold)]()

---

## Overview

This project leverages machine learning to predict the endangerment level of languages worldwide using demographic, technological, and legal status indicators. Drawing on five integrated datasets, it explores the relationship between factors such as speaker count, urbanization, internet use, and legal recognition, and their influence on language vitality. Multiple models, including ensemble methods, gradient boosting, and neural networks, were trained and evaluated, achieving high predictive performance. The results highlight the critical role of speaker population size while underscoring opportunities for improvement through the inclusion of additional socio-economic and historical features.

## Table of contents

- [Data](#data)
- [File structure](#file-structure)
- [Setup & reproduction](#setup--reproduction)
- [Methods](#methods)
- [Results](#results)
- [Key learnings](#key-learnings)
- [Contributors](#contributors)

## Data

| Dataset | Source | Description |
|---------|--------|-------------|
| Endangered Languages Project (ELP/ELCAT) | [ELCAT Github Link](https://github.com/cldf-datasets/elcat/tree/main) | Catalogue of Endangered Languages. 2023. University of Hawaii at Manoa. http://www.endangeredlanguages.com. Contains a list of ~3,000 languages with varying levels of endangerment. |
| List of languages by total number of speakers | [Wikipedia](https://en.wikipedia.org/w/index.php?title=List_of_languages_by_total_number_of_speakers&oldid=1350848572) | List of 20 non-endangered languages and their speaker counts. |
|List of official languages by country and territory | [Wikipedia](https://en.wikipedia.org/w/index.php?title=List_of_official_languages_by_country_and_territory&oldid=1348824802) | List of countries and their politically recognized official, regional, minority, national and widely spoken languages.|
|GDP per capita (current US$)|[World Bank](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD) | Countries and their GDP per capita.|
|Individuals using the internet (% of population)| [World Bank](https://data.worldbank.org/indicator/IT.NET.USER.ZS) | Percentage of population using the internet in each country.|
|Urban population (% of total population)| [World Bank](https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS) | Percent of the total population in a country that lives in an urban area|
|Urban population growth (annual %)| [World Bank](https://data.worldbank.org/indicator/SP.URB.GROW)| Yearly growth of urban populations in a country.|


## File structure

```
├── data/           # processed datasets
├── archive/        # version 1 of project
│   ├── notebooks/  # version 1 models and data cleaning notebooks
│   ├── data/       # version 1 project data
│   ├── docs/       # version 1 presentation and final report
│   └── README.md   
├── notebooks/      # current models and data analysis notebooks
├── images/         # charts and figures used in the README
├── README.md
└── requirements.txt
```

## Setup & reproduction

```bash
# Clone the repo
git clone https://github.com/jandersen12/Machine-Learning-Endangered-Languages.git
cd Machine-Learning-Endangered-Languages

# Install dependencies
pip install -r requirements.txt   # Python

# Run notebooks in order
# 01_... → 02_... → 03_...
```

> **Environment:** Python 3.10 

## Methods

*Version 2 is in progress. Check out the [archive/](archive/) folder for original models and results, where we achieved 88% accuracy in predicting a language's level of endangerment.*

## Results

*In progress*

## Key learnings

*In progress*

## Contributors

Helin Yilmaz | Courtney Chen | Brian Woods

UC Berkeley MIDS | July 2025
