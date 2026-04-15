# Textmining_for_understanding_SmartHomeService

This repository provides the reproducible structure of the analysis workflow used in the manuscript.

## Research Objective
- [Write 2-4 sentences describing the objective of this study.]
- [Example: This study applies text mining to smart home service literature to identify major research topics and inter-topic relationships.]

## Research Workflow
The analysis is conducted in the following four stages:
1. Data preprocessing
2. Keyword extraction
3. Research topics identification
4. Identification of the relationships between topics

## Data Source
- Database: Web of Science Core Collection (Clarivate Analytics)
- Search date: 2024-01-12
- Search type: Topic Search (not Advanced Search)
- Language: English
- Retrieved elements: Title, Abstract, Author Keywords

## Exact WoS Search String
```
("smart" AND "home" AND "service*") OR ("smart home service*")
```

## Inclusion Criteria
- Document type: Article
- Final corpus for analysis: 3,840 records

## Notes and Cautions
- Results may vary depending on package versions, Python version, and operating system.
- Results may also vary if random seeds are not fixed in stochastic steps (e.g., clustering).

## Scope Note
Only the core reproducible workflow and search strategy are shared in this public repository.  
Intermediate artifacts and extended outputs are intentionally minimized.
