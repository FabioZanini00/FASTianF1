###
<div align="center">
  <a href="https://github.com/FabioZanini00/FASTianF1">
    <img src="Logo/FASTianF1Logo_V2.png" width="200" alt="FASTianF1 Logo"/>
  </a>
</div>

# FASTianF1
Group project for [Database 2](https://didattica.unipd.it/off/2022/LM/IN/IN2547/004PD/INQ0091645/N0) course, developed by Christian Marchiori and Fabio Zanini.

The aim of this project was to create a graph database representing the world of Formula 1. Formula 1 (a.k.a. F1 or Formula One) is the highest category of single-seat auto racing sanctioned by the Fédération Internationale de l'Automobile (FIA) and owned by the Formula One Group.
The datasets used to create this database contain information regarding races, drivers, driver ratings, constructors, qualifying, circuits, lap times, pit stops, and championships from 1950 until the last season 2023.
The repository also contains some SPARQL queries to show how the database works.

---
### This repository contains:
- the ontology designed to model the F1 world (\Ontology)
- the visual graph (.png and .svg)
- the datasets used (\data)
- the jupyter notebook developed for data cleaning, ingestion and serialization (\Serialization)
- the turtle files produced by serialization (\data\rdf\)
- a notebook containing the queries (\Queries)
- the logo for our project
- other useful files (also for presentation)

---
### Data sources:
- Formula 1 data: [Ergast API](https://ergast.com/mrd/) or [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
- Ratings 2023 data: [EA Ratings API](https://ratings-api.ea.com/v2/entities/f1-23-drivers-ratings) of [F1 2023 official game](https://www.ea.com/it-it/games/f1/f1-23)
- Ratings older data: [GitHub](https://github.com/toUpperCase78/formula1-datasets)
- Country to Nationality csv: [GitHub](https://github.com/Imagin-io/country-nationality-list/tree/master)

---
### Various instruction to make the jupyter notebook work:
- the path are compliant with windows os, so they use '\\\' . To make them work with macOS or Linux, they need to be changed with '/'.

---
### Schema of the FASTianF1 ontology:
<div align="center">
  <a href="https://github.com/FabioZanini00/FASTianF1">
    <img src="FASTianF1schemeWhite.png" width="800" alt="FASTianF1 ontology schema"/>
  </a>
</div>
The [list of all data properties](Ontology/DataPropertiesList.md) for each class is available in the Ontology folder.
