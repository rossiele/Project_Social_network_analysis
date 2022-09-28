# Project_Social_network_analysis
Progetto svolto per il corso di Social Network Analysis (2021-2022)

L'analisi è stata svolta secondo le seguenti linee guida:

Part 1: Data collection:
1. Identify an online data source,
2. Identify the entities (nodes) and relationships among them (edges),
3. Identify the available additional information to be collected (e.g., nodes’ attributes,
edge weights...),
4. Obtain the data from the selected data source (through API - if available - or by
crawling),
5. Build a network from the data!

Part 2: Network Analysis
1. Perform Degree distribution analysis;
2. Perform Connected components analysis;
3. Perform Path analysis;
4. Perform Clustering Coefficient, Density analysis;
5. Perform Centrality analysis.

Moreover, the statistics computed on the crawled data must be compared with the ones
of (i) ER, (ii) BA, and (iii) WS graphs having (almost) the same number of nodes and edges.

Part 2.1: Network Analysis: Analytical Tasks
1. Community Discovery: Identify, evaluate and validate the modular structure of the
crawled network sample. The results of at least 3 CD algorithms (e.g., K-clique, Label
Propagation, Louvain, Infomap, Demon/Angel) must be evaluated and compared. If additional semantic information for the analysed graph are available use them to make sense of
the identified partitions. For CD algorithm implementations (as well as for their evaluation
and comparison) refer to the CDlib (https://github.com/GiulioRossetti/cdlib) library. The
analysis can be extended selecting approaches considered interesting among the one present
in such library.
2. Opinion Dynamics: Simulate, using the NDlib python library, the opinion dynamics models discussed during the course (i.e., Voter, Snayzd, Majority Rule, Q-Voter, Deffuant w/o
bias) both on the crawled data and in mean-field settings (i.e., complete graph). Analyse
the simulation results varying both model parameters and initial conditions;

Part 3: Open Question
1. Analysis of the most relevant user sentiments and topics in the most populated communities identified with the Louvain and K-clique algorithms using Sentiment Analysis and Topic Modeling techniques
