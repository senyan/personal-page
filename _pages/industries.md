---
layout: archive
title: ""
permalink: /industries/
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

## Keyword Suggestion for In-site Search Engine
**Role: Project Owner of Winning Hackathon Project**

**Data Preparation:** Built easy-to-use data pipeline to extract training and evaluation data from PDF and Word documents by leveraging techniques like OCR model; further developed dataset cleansing pipeline to filter out invalid data, like de-duplication and typo fix

**Exact Match based Method Development:** Leveraged the full-text search function provided by Elasticsearch, which uses BM25/TF-IDF, indexed the extracted phrases from the large dataset, and then built an auto-complete suggestion system based on Elasticsearch indexes

**Deep Model based Method Development:** Studied word and sentence embedding-based methods, such as Word2Vec and Doc2Vec, finetuned a BERT-base model by taking the idea of sentence and phrase vectorization to vectorize the extracted phrases, and then combined cosine-similarity with hand-crafted features to do keyword suggestion with a multi-layer perception network

## Recommendation System of Government Opportunities

**Role: Technical Leader**

**Problem Investigation:** Investigated the in-site opportunities recommendation system, such as user dwelling time and click through rate; Analyzed the award history for opportunity recommendation; Gathered user feedback through anonymous survey which shows that the opportunity recommendation does not meet the expectation

**Model Design and Development:** Designed and developed a user interests model based on the users’ long-run interests, specifically leveraging TF/IDF model computed on the users’ public award history; Categorized the opportunities to several topics; Built a new recommendation system based on user interests and award history which push biddable opportunities to government contractors

**A/B Test:** DeployedA/B tests and designed several metrics to measure the gain of treatment over baseline, which shows that the new recommendation system has a higher user engagement and retention rate

**Deep Learning-based Model:** Designed and trained a BERT based siamese model as a POC, which vectorizes the user and opportunities to 100D vectors and recalls opportunities based on cosine similarity of user embedding and opportunity embedding

## Document Information Extraction
**Role: Technical Leader**

**Entity Extraction System:** Built a name entity extraction system based on Spark NLP to extract entities from documents, such as place, key personnel and clearance requirements

**Data Preparation:** Designed and developed a pipeline to facilitate human dataset annotation to gather more high-quality training data

**Model Fine-tune:** Implemented an exhaustive search method to try out different combinations of data preprocessing methods and model hyper-parameters

**Project:** Held brain-storming session in the team to bring up new ideas; Worked with business stakeholders to pivot from a labor-intensive approach to a ML approach; Piloted the initial POC implementation which transformed into multi-millions strategic investment in the next fiscal year

## Probability of Win
**Role: Technical Leader**

**Data collection and normalization:** Carefully designed a spark based data pre-processing framework on AWS to handle a large amount of unstructured data, such as public government transactions of a given vendor, and normalized the data into a standard format

**Model Development:** Adopted fussy clustering and hierarchical clustering algorithm to cluster the normalized data, and then computed the probabilities of winning the bid based on the project clustering and the vendor’s past award history

## Data Lake Project
**Role: Chief Architect**

**Data lake development:** Transformed a legacy Oracle PL/SQL based data pipeline into a modern Spark-based data lake on AWS



