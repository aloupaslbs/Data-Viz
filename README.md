# GPU Computing Power Distribution and Global Inequality in AI Research

This project conducts a cross-country analysis of GPU computing power to understand how access to high-performance AI infrastructure is distributed globally. As modern AI development increasingly depends on large-scale GPU clusters, especially H100-equivalent compute, the availability of such resources determines which countries can meaningfully participate in frontier AI research. By bringing together compute infrastructure data, population figures, and economic indicators, this project provides a systematic, data-driven look at the emerging global divide in AI capabilities and how it mirrors broader patterns of economic inequality.

## Research Question

**How is GPU computing power distributed across countries, and what does this distribution reveal about global inequality in AI research and development?**

This central question is motivated by the observation that AI progress is becoming compute-intensive at an unprecedented rate. While a handful of high-income nations are rapidly expanding their GPU clusters and supercomputing capacity, many others lack even minimal access to the infrastructure required to train or deploy state-of-the-art models. Understanding the geography of compute helps clarify who will be able to innovate, who will depend on imported AI systems, and how unequal access may shape the future of global AI governance, economic competitiveness, and scientific contribution.

## Data Sources

This project integrates several openly available datasets from international organizations and research groups:

- **GPU Cluster Data — Epoch AI**  
  https://epoch.ai/data/gpu-clusters  
  Contains locations of commercial GPU clusters, H100-equivalent estimates, capacity, and operator details. This forms the backbone of the compute dataset.

- **World Population Data — World Bank**  
  https://data.worldbank.org/indicator/SP.POP.TOTL  
  Provides standardized population counts for every recognized country, enabling compute-per-capita metrics.

- **GDP Ranking and Economic Indicators — World Bank**  
  https://datacatalog.worldbank.org/search/dataset/0038130/GDP-ranking  
  Supplies GDP data and rankings used to analyze correlations between economic output and access to GPU compute.

- **Global Supercomputing Data — TOP500 List (June 2025)**  
  https://www.top500.org/lists/top500/2025/06/  
  Provides performance rankings and country distribution of the world’s top supercomputers, complementing commercial GPU cluster data with national HPC capacity.

These datasets are harmonized at the country level, making it possible to compare compute access in relation to demographic and economic context.

## Project Overview

The project compiles GPU cluster information, supercomputing rankings, GDP data, and population statistics for 231 countries. GPU capacity is expressed in **H100-equivalents**, a normalized measure representing the compute performance of NVIDIA’s current-generation high-performance AI accelerators. Countries are categorized into three groups:

- **Compute Core** — roughly the top 10% of countries by compute capacity  
- **Compute Periphery** — countries with non-zero but limited GPU or supercomputing resources  
- **Compute Deserts** — countries with *zero* commercial GPU cloud availability  

The analysis reveals a highly skewed distribution of compute power. A very small number of wealthy, industrialized countries (primarily in North America, Western Europe, and East Asia) dominate global GPU resources and host nearly all commercial cloud-scale AI infrastructure and top-ranked supercomputers. By contrast, around **87% of countries lack any commercial GPU clusters accessible through cloud providers**, and many also lack supercomputers capable of running modern machine learning workloads. These countries face structural disadvantages in conducting AI research, training large models, or building domestic AI industries.

The study additionally examines the relationship between compute access, GDP, and population size. Results point to a strong positive correlation between economic strength and compute availability, highlighting how existing economic inequalities are reproduced, and in some cases amplified, when access to frontier AI hardware is unevenly distributed.

## Purpose and Significance

The goal of this project is to provide a clear, empirical foundation for understanding the global landscape of AI compute access. As AI becomes a transformative general-purpose technology, unequal access to compute risks deepening divides between countries that can contribute to AI innovation and those that become dependent consumers of imported AI systems. By quantifying the geographic concentration of GPU and HPC resources, this project supports broader discussions about equitable compute access, international AI cooperation, capacity-building in developing regions, and the long-term implications of an AI ecosystem dominated by a small number of compute-rich nations.
