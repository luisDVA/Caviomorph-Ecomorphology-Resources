
<!-- README.md is generated from README.Rmd. Please edit that file -->
### Supplementary materials README guide

# Patterns in research and data-sharing for the study of form and function in caviomorph rodents
Luis D. Verde Arregoitia, Pablo Teta, & Guillermo D’Elía (2019) _Journal of Mammalogy_

<!-- badges: start -->
[![DOI](https://zenodo.org/badge/226196041.svg)](https://zenodo.org/badge/latestdoi/226196041)
<!-- badges: end -->

### Data description and general guide for working with the supplementary files.

Supplementary materials files are organized in the following three
folders:

📂 master\_lists

Comma-separated text files with aggregate data from all studies, the
reference taxonomy used throughout the analyses, and the data used to
standardize and geocode the collections housing caviomorph specimens.
  

| File                       | Description                                                                                         |
| -------------------------- | --------------------------------------------------------------------------------------------------- |
| asm-species-2018-10-02.csv | Reference taxonomy, downloaded from Mammaldiversity.org (downloaded November 2018)                  |
| master-accessions.csv      | DNA sequence identifiers                                                                            |
| master-diet.csv            | Feeding strategies/diets                                                                            |
| master-habitats.csv        | Habitat preferences                                                                                 |
| master-habits.csv          | Substrate use strategies/habits                                                                     |
| master-morphology.csv      | Morphology trait values                                                                             |
| master-specimens.csv       | Specimens examined with standardized and geocoded collection data                                   |
| museums.csv                | Standardized collection names (see main text for sources)                                           |
| museum\_locations.csv      | Collection locations, obtained through the Opencage geocoding service (<https://opencagedata.com/>) |

📂 relational\_data

Comma-separated text files containing all the redigitized data available
in the 41 studies reviewed. Two common variables in the files can be
used to establish relationships between them; the `sp` column contains
the study taxa (observational units) and the `study` column refers to
the source of the data.

These data can be explored interactively through a web application at
<https://github.com/luisDVA/Caviomorph-Ecomorphology-Resources-App>.

Each file name (shown below without the file extension) is labeled with
the following suffixes to identify its
content:

| File suffix       | Description                                                                             |
| ----------------- | --------------------------------------------------------------------------------------- |
| \*\_accessions    | Identifiers for DNA sequences                                                           |
| \*\_traits\_eco   | Ecological trait values                                                                 |
| \*\_traits\_morph | Morphology trait values                                                                 |
| \*\_specimens     | Specimens examined                                                                      |
| \*\_linear        | Names and descriptions of the linear traits and compound indices examined or calculated |
| \*\_landmarks     | Description of landmark configurations used in geometric morphometrics analyses         |

📂 shiny\_app

Source code and data for the current version (December 2019) of the web application that
can be used to explore the data in this repository.


#### This dataset ("Caviomorph Ecology Resources") is made available under the Open Data Commons Attribution License: http://opendatacommons.org/licenses/by/1.0.

