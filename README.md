# Integrating Multi-Source Spatial Data into a Graph Framework for Carbon Storage Suitability Analysis

### Project Overview

This repository contains the relational spatial dataset developed for the project:

Artificial Intelligence-driven Selection of Safe CO₂ Injection Sites in Louisiana

The dataset supports the study:

Integrating Multi-Source Spatial Data into a Graph Framework for Carbon Storage Suitability Analysis

Authors:
Mariam Valladares-Castellanos, Sreekanta Das, Supratik Mukhopadhyaya, Thomas Douthat, Chris McLindon, Chris Alvin, Costas Varotsos

Affiliation:
Louisiana State University (LSU), Baton Rouge, Louisiana, USA

### Purpose

The purpose of this work is to introduce a relational, multi-source spatial dataset designed to support the development of an AI-driven framework for CO₂ geological storage site selection. Carbon storage suitability assessment requires integrating heterogeneous datasets describing geological, environmental, infrastructural, and socio-economic conditions. Traditional spatial datasets are typically stored as independent layers, limiting their ability to represent interactions among systems. This dataset addresses that limitation by organizing spatial information into a graph-structured framework suitable for machine learning applications, particularly Graph Neural Networks (GNNs).
The framework enables AI models to:

- Learn from interconnected spatial systems rather than isolated variables
- Detect spatial and functional relationships among candidate storage locations
- Evaluate site suitability using integrated environmental and infrastructure constraints
- Produce scalable, reproducible, and flexible optimization metrics for decision support

### Dataset Description

The dataset integrates multiple spatial data sources across Louisiana into a unified relational structure composed of nodes and edges.

#### Node-Level Features

Nodes represent spatial entities relevant to CO₂ storage suitability, including geological formations and subsurface characteristics, candidate CO₂ storage locations, industrial emission sources, population density and demographic indicators, critical habitats, and environmental constraints. Each node contains attributes describing physical, environmental, or socio-economic properties used as model inputs.

Edges describe relationships and interactions between nodes, such as, hydrological connectivity, transportation and pipeline proximity, spatial adjacency and distance relationships, source-to-sink connectivity. 

### Files Description

The repository includes the following supplementary materials:

Supplementary Material 1
Describes the metadata and data dictionaries for both the edge list and node attribute databases, including variable definitions, units, and data sources.

Supplementary Material 2
Contains the Python notebooks documenting the full processing workflow used to generate the graph structure.

Supplementary Material 3
Includes the finalized edge list and node attribute databases used for graph construction and machine learning applications.

### Citation

Valladares-Castellanos, M., Das, S., Mukhopadhyaya, S., Douthat, T., McLindon, C., Alvin, C., & Varotsos, C. (Year). Integrating Multi-Source Spatial Data into a Graph Framework for Carbon Storage Suitability Analysis. Louisiana State University (Submitted).


