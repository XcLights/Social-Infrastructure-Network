# Social Infrastructure Network Project

*What is social infrastructure*: The facilities, groups, and organizations, excluding goervnment agencies, that foster social cohesion and support.

**Research Question**: What can the nature of social infrastructure tell us about a population's ability to adapt to changes?

<ins>**Project Description**<ins>
Mapping and evaluating social infrastructure beginning at the County level with the potential to scale globally.

## Introduction

Since the time of Heraclitus, perhaps even earlier, we have suspected that change is constant (Graham, 2023). Effects of climate change today are increasingly apparent from reports of natural disasters, record-breaking storm intensity, displaced people, outbreaks of contagious disease, conflict and disagreement around how to address these challenges, departure from arduous progress, and even occasional denial that there is a climatic problem that can be mitigated. What we do is 100% in our control, so studying social infrastructure from the perspective of social networks at an institutional/organizational level could provide practical and actionable insights for decision makers and the public.

## Protocol Summary

1. **Data Collection and Coding**

Using public records and public databases, such as from State and municipal government (Vermont Secretary of State, n.d.; Town of Bennington, VT, n.d.), gather source data (e.g., group/organizational names, location, type, size) for social infrastructure datasets, which will serve as node data. Determine and execute method for gathering relational data, such as a survey, which will serve as edge data. Code non-numerical data (e.g., entity type, relation type).

2. **Network Construction**

Arrange data into adjacency matrix and adjacency list for construction and analysis of a multilayer network.
  - Creating the graph Laplacian and/or modularity matrix would expand network construction and analysis possibilities.

3. **Network Analysis**

Calculate local and distributed network measurements which include degree distribution, various centrality measures, and assortative mixing metrics. These metrics can be calculated with the adjacency matrix.
  - The graph Laplacian and modularity matrix can expand analysis into diffusion simulations and community detection.

4. **Random Model(s) Comparison**

Utilize exponetial random graph models (ERGMs) to compare the observed network to a randomly generated network(s).


# References
Graham, D. W. (2023). *Heraclitus*. Stanford Encyclopedia of Philosophy. <https://plato.standord.edu/entries/heraclitus/>  
Town of Bennington, VT. (n.d.). *Assessors*. Retrieved on December 1, 2024 from <https://benningtonvt.org/services/assessors.php#collapse290b0>  
Vermont Secretary of State. (n.d.). *Corporations Division*. Vermont.gov. Retrieved December 1, 2024 from <https://bizfilings.vermont.gov/online/BusinessInquire>
