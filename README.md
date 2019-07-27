## Personalized_Cancer_Diagnosis
Predict the effect of Genetic Variants to enable Personalized Medicine

### Description
- Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/
- Data: Memorial Sloan Kettering Cancer Center (MSKCC)
- Download training_variants.zip and training_text.zip from Kaggle.

### Context:
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

## Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

### Source/Useful Links
Some articles and reference blogs about the problem statement

- https://www.forbes.com/sites/matthewherper/2017/06/03/a-new-cancer-drug-helped-almost-everyone-who-took-it-almost-heres-what-it-teaches-us/#2a44ee2f6b25
- https://www.youtube.com/watch?v=UwbuW7oK8rk
- https://www.youtube.com/watch?v=qxXRKVompI8
### Real-world/Business objectives and constraints.
- No low-latency requirement.
- Interpretability is important.
- Errors can be very costly.
- Probability of a data-point belonging to each class is needed.

### Data Overview
- Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
- We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
- Both these data files are have a common column called ID
- Data file's information:

  - training_variants (ID , Gene, Variations, Class)
  - training_text (ID, Text)
