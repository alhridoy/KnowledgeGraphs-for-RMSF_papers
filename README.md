# KnowledgeGraphs-for-RMSF_papers
Knowledge Graph Construction from Scientific Text
This project aims to build a knowledge graph from scientific text, specifically focusing on the topic of Rocky Mountain Spotted Fever (RMSF). The project involves several steps, including:
1. Data Preprocessing

Reading and preprocessing the dataset of candidate sentences from scientific papers related to RMSF.
Performing sentence segmentation using spaCy's natural language processing library.

2. Entities Extraction

Extracting entities (subjects and objects) from the sentences using a custom function get_entities().
Handling cases where entities span across multiple words and dependency parsing challenges.

3. Relations Extraction

Extracting relations (predicates) between entities using a custom function get_relation().
Identifying the main verb in a sentence as the predicate using spaCy's rule-based matching.

4. Knowledge Graph Construction

Creating a dataframe with entities (source and target) and their relations (edges).
Using the NetworkX library to create a directed graph from the dataframe.
Visualizing the knowledge graph using Matplotlib.

The project utilizes various Python libraries, including:

pandas
spaCy
NetworkX
Matplotlib
tqdm
