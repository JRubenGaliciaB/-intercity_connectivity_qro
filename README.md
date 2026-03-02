# Intercity Connectivity and Innovation - Querétaro


[TAKE ME TO THE MAP!]
[TAKE ME TO THE DATA!](https://github.com/JRubenGaliciaB/-intercity_connectivity_qro/tree/main/Data)


## Data 
We compiled subnational network and socioeconomic attributes to construct intercity connectivity measures for the state of Querétaro and its interregional linkages within Mexico. The spatial unit of analysis is the municipality (municipio) within Querétaro and selected connected metropolitan areas at the national level.

**Social Media Network**: Digital connectivity was approximated using publicly available subnational indicators. When available, we use the Social Connectedness Index (Meta/Facebook) to estimate the probability of social ties between municipalities. This is complemented with geolocated Twitter/X interaction data to infer intermunicipal digital linkages. Additionally, municipal-level internet penetration rates from the Federal Telecommunications Institute (IFT) are incorporated as control variables to capture digital infrastructure capacity.

**Mobility Network**: Human mobility flows were constructed using multiple public sources. Intra- and intermunicipal mobility patterns were estimated using Origin-Destination survey data (where available), urban transport statistics from INEGI and AMEQ (Qrobús system), and federal highway traffic counts from CAPUFE along key corridors (e.g., Querétaro–Mexico City, Querétaro–Celaya). Economic connectivity was further approximated using the spatial distribution of logistics and transportation firms from DENUE (INEGI), serving as a structural proxy for interregional economic flows.

**Scientific Collaboration Network**: The scientific collaboration network was derived from co-publication (co-authorship) relationships identified in Scielo and Redalyc databases, focusing on institutional affiliations located in Querétaro (e.g., UAQ, ITQ, UNAM Juriquilla, CINVESTAV). This was complemented with researcher-level data from the National System of Researchers (SNII-CONAHCYT) to estimate the concentration and distribution of research capacity across municipalities. Collaboration ties were constructed based on shared authorship across institutions.


## Method 

We use weighted degree centrality for the digital connectivity, mobility, and scientific collaboration networks to measure each municipality’s position and strength within the interurban system. Degree centrality captures the intensity of flows—of people, information, and knowledge—linking a municipality to others, thereby operationalizing its structural importance in the regional network.

To measure innovation, we use patent counts at the subnational level, complemented—where data availability allows—by patent classifications as a proxy for technological sophistication. In addition, given the strategic focus of this study, we incorporate sectoral indicators related to advanced digital infrastructure (e.g., data center–related activity and high-technology firm presence) as complementary measures of innovative and industrial complexity.

We estimate population-based urban scaling models with and without intercity connectivity variables. Consistent with the theoretical framework, we assess whether the inclusion of network centrality metrics increases the explanatory power of the model beyond population size alone. Our results evaluate whether municipalities with higher interurban connectivity exhibit systematically higher innovative output relative to what would be predicted by size. We further analyze residuals from the scaling models to identify municipalities that overperform or underperform in innovation, examining whether overperformance correlates with higher intercity connectivity after controlling for socioeconomic factors such as GDP and educational attainment.

This approach allows us to test whether connectivity functions as a structural amplifier of innovation at the subnational level in Mexico, particularly in emerging industrial hubs such as Querétaro.
