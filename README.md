# DASC3240_Assignment2

# Assignment II: Group [A]

# Group member list

-   ZHANG, Chuxi (Leader & Owner)
-   HE, Bingyi
-   LIN, Zirong
-   YANG, Taoming
-   CHENG, Wing Him

# Dataset

Each group member may choose either of the following dataset:

**Built-in dataset**

-   `palmerpenguins::penguins`\
-   `ggplot2::msleep`\
-   `ggplot2::midwest`\
-   `datasets::Orange`\
-   `datasets::quakes`

**Public dataset**

BIOTIME (CC0) <https://biotime.st-andrews.ac.uk/usageGuidelines.php>

-   `BIOTIME_raw_data_192.csv` (uploaded on Canvas) (Whale data from <https://biotime.st-andrews.ac.uk/selectStudy.php?study=192>)\
-   `BIOTIME_raw_data_232.csv` (uploaded on Canvas) (Fish data from <https://biotime.st-andrews.ac.uk/selectStudy.php?study=232>)

# Introduction

-   [**Please describe the structure of this repository. Who are members? Who is the leader and who contributed the overall structure of this report and how?**]{style="color:darkred;"}\

# Group Project: Multi-Dimensional Nature Exploration

------------------------------------------------------------------------

## 1. Repository Overview & Structure

This repository is organized to support collaborative development for the **DASC3240** group project using a structured Git workflow and Quarto-based reporting system.

### Structure

-   The repository follows an **RStudio project structure**
-   Each member works on an individual **Quarto (`.qmd`) file**
-   All datasets are stored in the **`data/` folder**
-   Final outputs are rendered as `.html` files
-   Version control is managed via **GitHub branches**

------------------------------------------------------------------------

## 2. Branch Structure

Each team member developed their work in an individual branch.\
All branches were finally merged into the `main` branch by the team leader.

### Overview

-   **main (final integrated version)**
    -   ZhangChuxi → BIOTIME 192 analysis\
    -   HEBingyi → BIOTIME 232 + visualization + debugging\
    -   LinZirong → Penguins analysis\
    -   YangTaoming → msleep analysis\
    -   Cheng_Wing_Him → Earthquake visualization

------------------------------------------------------------------------

## 3. Team Leadership & Responsibilities

-   **Zhang Chuxi (Leader)**\
    Responsible for:
    -   Overall project coordination\
    -   Task allocation and dataset assignment\
    -   Managing project workflow\
    -   Merging all branches into the `main` branch\
    -   Ensuring consistency of the final report
-   **HE Bingyi (Technical Lead & Git Management)**\
    Responsible for:
    -   Managing GitHub **branch workflow and repository structure**\
    -   Maintaining version control\
    -   Debugging technical issues (e.g., plot errors, merge conflicts)\
    -   Supporting visualization implementation (`plotly`, `gganimate`)
-   **Lin Zirong**\
    Responsible for:
    -   Analysis and visualization of the **Palmer Penguins** dataset
-   **Yang Taoming**\
    Responsible for:
    -   Analysis of the **Mammalian Sleep (msleep)** dataset
-   **Cheng Wing Him**\
    Responsible for:
    -   Analysis and visualization of the **Fiji Earthquakes (quakes)** dataset

------------------------------------------------------------------------

## 4. Contribution to Overall Structure

The overall structure of this report was developed collaboratively.

-   **Zhang Chuxi** led coordination, task allocation, and final integration\
-   **HE Bingyi** contributed significantly to repository management, branch organization, and debugging

This division of responsibilities ensured efficient parallel development and a well-organized final report.

------------------------------------------------------------------------

## 5. Introduction

The goal of this project is to explore **spatiotemporal patterns and biological characteristics** across multiple domains using interactive and dynamic visualizations.

The project spans several key areas:

-   **Polar Ecological Evolution**\
    Analysis of **BIOTIME (Study 192 & 232)** to examine long-term changes in Antarctic ecosystems

-   **Biological Traits & Behaviors**\
    Use of **Palmer Penguins** and **Mammalian Sleep** datasets to study morphology and physiological relationships

-   **Geophysical Dynamics**\
    Visualization of **Fiji Earthquakes** to analyze magnitude distribution and spatial depth patterns

------------------------------------------------------------------------

## 6. Team Division & Dataset Summary

| Member | Role | Dataset | Research Focus |
|:---|:---|:---|:---|
| **Zhang Chuxi (Leader)** | Coordination | **BIOTIME 192** | Spatiotemporal distribution of Antarctic species |
| **HE Bingyi** | Technical Lead | **BIOTIME 232** | Fish abundance and spatial heatmap animation |
| **Lin Zirong** | Member | **Palmer Penguins** | Morphological comparison |
| **Yang Taoming** | Member | **msleep** | Sleep and physiology relationships |
| **Cheng Wing Him** | Member | **quakes** | Earthquake spatial patterns |

------------------------------------------------------------------------

## 7. Detailed Dataset Profiles

### BIOTIME (Study 192 & 232)

-   Long-term biological monitoring in the Southern Ocean\
-   Data collected via bottom trawl surveys\
-   Key variables: `ABUNDANCE`, `BIOMASS`, `LATITUDE`, `LONGITUDE`, `YEAR`

------------------------------------------------------------------------

### Palmer Penguins

-   Observational data of Antarctic penguins\
-   Key variables: `species`, `island`, `bill_length_mm`, `flipper_length_mm`, `body_mass_g`, `year`

------------------------------------------------------------------------

### Mammalian Sleep (msleep)

-   Sleep and physiological traits of mammals\
-   Key variables: `sleep_total`, `sleep_rem`, `bodywt`, `brainwt`, `vore`

------------------------------------------------------------------------

### Fiji Earthquakes (quakes)

-   Seismic activity data near Fiji\
-   Key variables: `lat`, `long`, `depth`, `mag`, `stations`

------------------------------------------------------------------------

## 8. Branching & Collaboration Workflow

The team adopted a **branch-based Git workflow**:

-   Each member worked on an individual branch\
-   Changes were committed independently\
-   The leader merged all branches into `main`\
-   Technical issues were handled during development and merging

### Advantages:

-   Supports parallel development\
-   Reduces conflicts\
-   Improves organization and traceability

------------------------------------------------------------------------

## 9. AI Declaration

Generative AI tools (e.g., ChatGPT, Gemini, DeepSeek) were used to assist with:

-   Debugging technical issues (e.g., `gganimate` rendering errors)\
-   Improving code structure and visualization implementation\
-   Refining written explanations

All AI-generated content was reviewed and validated to ensure accuracy and alignment with project requirements.
