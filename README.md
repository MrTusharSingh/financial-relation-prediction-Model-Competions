# financial-relation-prediction-Model-Competions

ModelQuest is a competition designed to challenge participants in relation extraction using machine learning models. In this challenge, you will develop a model that predicts the relationship between two entities given within a sentence. This task is fundamental in Natural Language Processing (NLP) and plays a key role in knowledge graph construction, automated text understanding, and many other applications.

Problem Statement:
Financial Relation Prediction:
Participants will be provided with a dataset containing sentences along with two marked entities and their associated relationship labels. Participants are required to develop AI/ML/DL models to predict the relation between two given entities in a given sentence.

Your goal is to build a model that generalizes well and accurately predicts relationships on unseen data.

Example:

Sentence - "The latest RBI policy has affected the economic growth of the banking sector".

Entity_1 - "RBI Policy"

Entity_2 = "economic growth".

The model should predict "affects" as the relation between the two entities in the given sentence.

Dataset
The dataset consists of two files:

train.csv: Contains labeled examples with entity pairs and their corresponding relationships.
test.csv: Contains unseen data where relationships need to be predicted.
Each row in the dataset includes:

id: A unique identifier for the instance.
sentence: The text containing the two entities.
entity_1: The first entity in the sentence.
entity_2: The second entity in the sentence.
relation: The relationship between entity_1 and entity_2 (only in train.csv).
The test data contains the same structure but lacks the relation column, which participants must predict.

Evaluation
Submissions will be evaluated based on accuracy — the percentage of correctly predicted relationships compared to the ground truth labels.

Public Leaderboard: Scores are calculated using 6% of the test data.
Private Leaderboard: Final rankings will be based on the remaining 94% of test data, revealed at the end of the competition.
Submission Format
Your submission file must be a CSV with two columns:

id: The corresponding ID from test.csv.
relation: The predicted relationship for the given entity pair.
Example:
id,relation
1,affects
2,involves
3,sells
etc.
