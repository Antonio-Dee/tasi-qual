# LLM-Enhanced Semantic Data Integration for Retrieving Electronic Component Qualifications from Heterogeneous Sources

This repository contains exemplary notebooks for some of the experiments described in the paper:

> Antonio De Santis, Marco Balduini, Matteo Belcao, Andrea Proia, Marco Brambilla, and Emanuele Della Valle.
> **LLM-Enhanced Semantic Data Integration for Retrieving Electronic Component Qualifications from Heterogeneous Sources**. Submitted to ISWC 2024 - In-Use Track.

# Abstract
Large manufacturing companies face challenges in information retrieval due to data silos maintained by different departments, leading to inconsistencies and misalignment across databases. This paper presents an experience in integrating and retrieving qualification data for electronic components used in satellite board design by Thales Alenia Space. Due to poor data silos, designers cannot immediately determine the qualification status of individual components. However, this process is critical during the planning phase, when assembly drawings are issued before production, to optimize new qualifications and avoid redundant efforts.
To address this, we propose a pipeline that leverages Virtual Knowledge Graphs for a unified view over heterogeneous data sources and Large Language Models (LLMs) to enhance retrieval and reduce manual effort in data cleansing. The retrieval of qualifications is then performed through an Ontology-based Data Access approach for structured queries and a vector search mechanism for retrieving qualifications based on similar textual properties. We conduct a comparative cost-benefit analysis, demonstrating that the proposed pipeline also outperforms approaches relying solely on LLMs, such as Retrieval-Augmented Generation (RAG), in terms of long-term efficiency.
