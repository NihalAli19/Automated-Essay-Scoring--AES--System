# KnowledgeRepresentationandReasoning-ML-AutomaticEssayEvaluation-ResearchPaperImplementation

Overview:

This project implements an Automatic Essay Scoring (AES) system using Linear Regression and ontology-based evaluation. The system predicts essay scores based on semantic relevance to a predefined ontology created using OntoGen. Essays are preprocessed, tokenized, and evaluated for features like word count, domain-specific relevance, and correctness. The ontology helps identify key concepts relevant to the essay topic and guides the scoring process.


Features:

1. Ontology-Based Scoring:

Utilizes OntoGen2-generated ontology for evaluating essay relevance. Link for the OntoGen2 Software provided below 👇:

https://ailab.ijs.si/wp-content/uploads/2022/05/OntoGen2-2007-11-22.zip

Ensures semantic alignment with the expected topic domain.


2. Preprocessing:

Removes extra spaces, stop words, and punctuation marks.

Applies word embedding techniques to improve semantic understanding.


3. Feature Extraction:

Essay length (word and sentence count).

Domain-specific word frequency.

Parts of speech (POS) tagging for vocabulary analysis.

Similarity metrics using cosine similarity and Latent Semantic Analysis (LSA).


4. Score Prediction:

Linear Regression model predicts scores based on extracted features.

Output aligns essay content with the most relevant ontology concepts.


5. Download the OntoGen tool and ontology dataset:

OntoGen Tool : https://ailab.ijs.si/wp-content/uploads/2022/05/OntoGen2-2007-11-22.zip
Dataset : Download form Repository files


Dataset:

The project uses essays on topics such as Human-Computer Interaction for training.

Features extracted include: Character and word counts.

Domain relevance as defined by the ontology.

Semantic similarity.


Results:

Supervised learning achieved best similarity, outperforming unsupervised approaches.


Key insights:

Essays with higher word counts and domain-relevant vocabulary score higher.

Ontology-driven evaluation ensures precision in assessing essay quality.


Future Scope:

Incorporate advanced sentiment analysis and context understanding.

Expand datasets to evaluate system robustness.

Add student feedback recommendations for improved essay writing.


References:

OntoGen Tool: Download

Research Paper: "Automated Essay Scoring with Ontology based on Text Mining and NLTK tools" (see accompanying document).
