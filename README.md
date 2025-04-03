# Information Processing and Retrieval Project (FEUP-PRI)

## Overview
This repository contains the complete documentation for an advanced Information Retrieval (IR) system developed as part of the Information Processing and Retrieval course at FEUP. The project explores various aspects of information retrieval, including data processing, evaluation, indexing, ranking, and query processing, all implemented using Apache Solr.

## What is Solr?
[Apache Solr](https://solr.apache.org/) is a powerful open-source search platform built on Apache Lucene. It provides distributed indexing, replication, load-balanced querying, automated failover and recovery, and centralized configuration. Solr is highly scalable, providing fault-tolerant distributed search and indexing, making it ideal for enterprise-level search applications.

## Project Milestones

### Milestone 1: Data Processing
- Selected a relevant dataset for information retrieval tasks
- Performed comprehensive data processing:
  - Data preparation and cleaning
  - Setup processing pipelines
  - Data characterization and analysis
- Defined document structure and schema for the selected dataset

### Milestone 2: Search Systems & Evaluation
- Gathered and defined information needs
- Developed queries to satisfy these information needs
- Implemented two distinct search systems:
  1. **Simple System**: Basic Solr configuration
  2. **Boosted System**: Enhanced schema with field boosting
- Conducted pooling methodology:
  - Ran each query on both systems
  - Retrieved top 40 results from each system
  - Evaluated relevance of each result
  - Merged results and removed duplicates
- Created qrels (query relevance) files
- Evaluated system effectiveness using trec_eval metrics

### Milestone 3: Advanced Search & Web Application
- Refined the information retrieval process
- Developed two new advanced systems:
  1. **Semantic Search System**: Implemented semantic search capabilities
  2. **Hybrid System**: Combined semantic search with boosted system
- Built a user-friendly web application:
  - Interface for user queries
  - Integration with Solr backend
  - "More Like This" feature implementation
- Implemented re-ranking using Gemini API
- Conducted comparative evaluation of all systems

## Key Learnings
- **Data Processing**: Mastered extraction, preparation, characterization, and pipeline setup techniques
- **Information Needs**: Learned to identify and formalize user information requirements
- **Relevance Assessment**: Developed skills in evaluating document relevance to queries
- **Evaluation Methodologies**: Applied standard IR evaluation metrics and methodologies
- **Query Processing**: Implemented efficient query parsing and processing techniques
- **Ranking Algorithms**: Explored various ranking strategies and their impact on retrieval performance

## Repository Contents

This repository contains two main documents:

1. **PowerPoint Presentation**: A comprehensive overview of the project, including methodologies, key findings, and a demonstration of the web application.

2. **Report**: Detailed documentation of every step taken throughout the project, including:
   - Dataset selection and processing methodology
   - System design and implementation details
   - Query development process
   - Evaluation metrics and results analysis
   - Comparative performance of all systems
   - Conclusions and future work

## Getting Started

To explore this project:
1. Review the Report for detailed information on the methodology and implementation
2. Check the PowerPoint Presentation for a visual overview and application demo

## Technologies Used
- Apache Solr
- Trec_eval (for evaluation)
- Gemini API (for re-ranking)
- NextJs (for the web app)


## Project Grade
- 19.5/20

## Final Grade
- 18/20

---

*This project demonstrates the complete lifecycle of developing an information retrieval system, from data processing to evaluation and user interface implementation.*