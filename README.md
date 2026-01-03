# Hollywood Actors Network Analysis

## Assignment
Social network analysis of Hollywood actors examining collaboration patterns through film co-appearances. Analysis includes centrality measures and community detection using Girvan-Newman and Louvain algorithms.

Code is in the index.Rmd file of the repo

## Key Findings
* 11 actors analyzed with 14 weighted connections
* **Al Pacino** and **Robert De Niro** are most central (high Eigenvector) but isolated within tight cliques
* **Tom Hanks** is the primary network bridge with highest betweenness and closeness
* Girvan-Newman algorithm achieved higher modularity than Louvain for community detection

## Data Source
Hollywood actors network from DACSS course materials - actors connected if they appeared in the same film, weighted by number of collaborations.

