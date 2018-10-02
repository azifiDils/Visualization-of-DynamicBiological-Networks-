# Visualization-of-DynamicBiological-Networks-
Data and code for the DILS-Publication: construction and Visualization of DynamicBiological Networks: Benchmarking the Neo4JGraph Database

Two data sets were analyzed
1) Based on very small subset of data from FANTOM 
2) Based on cardiac myocyte data from FANTOM 

The input is provided as files in comma separated values (CSV) format. 
The following files are included per dataset:
1) genenames: file with all distinct gene names
2) enhids: file with all distinct enhancer identfiers
3) tfpairs: file with all transcription factor pairs (represented by two PWMs,additionally the boolean flag whether the pair is a known Compel pair, the boolean flag whether the pair is a known BioGrid pair and the unique name as a concatenation of the two PWMs is included)
4) enh2promo: file with all relationships between enhancer identifiers and the gene names (whose promoters are analyzed)
5) tf2gene: file with all relationships between transcription factor pairs and the gene names
6) tf2enh: file with all relationships between transcription factor pairs and the enhancer identifiers

The commands used to load and analyze data in Neo4J are given in pdf format.
