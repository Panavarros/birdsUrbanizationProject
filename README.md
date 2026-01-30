This repository contains a reproducible R workflow for analyzing functional diversity and coloration patterns in passerine bird communities.  
The project focuses on integrating community-level species data with species-level trait information to explore ecological patterns across habitats and sexes.

---

## Project overview

The goal of this project is to demonstrate a complete analytical workflow commonly used in biodiversity and functional ecology studies.  
The analysis covers data preparation, trait filtering, functional diversity estimation, statistical testing, and visualization.

The repository is designed to be clear, modular, and reproducible, making it suitable as a general research and data analysis portfolio.

---

## Data description

The analysis uses three main data sources:

- **Community matrix** (`MatrizDatosFinalesAves.csv`)  
  A matrix where rows represent communities or sampling units and columns represent species. Values correspond to species abundances or presences.

- **Color trait data** (`ColorMeasures.csv`)  
  Species-level coloration measurements, including sex-specific information (males and females).

- **Trait-colo metadata** (`ColorTraits.csv`)  
  File describing the type of variables used in functional diversity analyses.

> Species names must be consistent across all datasets for the analyses to run correctly.
