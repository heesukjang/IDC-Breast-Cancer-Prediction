# Project Overview
###### <i>UC Berkeley MIDS `Natural Language Processing with Deep Learning` Group Project</i>

**Objective:** 
As part of a collaborative project, we have developed an Automated Essay Scoring (AES) system, employing Natural Language Processing (NLP) technology. This system is specifically designed to autonomously grade argumentative essays, focusing on aiding English Language Learners (ELLs) from grades 8 to 12.

**Scoring Criteria:**
The AES system evaluates essays based on six analytical dimensions: cohesion, syntax, vocabulary, phraseology, grammar, and conventions. Each dimension is indicative of a specific aspect of essay writing proficiency, with higher scores denoting greater proficiency. The scoring scale ranges from 1.0 to 5.0, with increments of 0.5.

**Technical Approach:**
We utilize BERT-based and BERTweet-based models to process student essays, capturing semantic nuances. These models map linguistic features to scores within an ordinal framework. To refine the scoring accuracy, we apply a Mean Columnwise Root Mean Square Error (MCRMSE) regression loss, ensuring a more constrained and accurate scoring range.

**Performance Enhancement Techniques:**
To enhance the system's effectiveness, we implemented K-means clustering combined with stratified two-fold cross-validation on each of the BERT-based models. This approach allows for a more robust and reliable assessment of essay writing skills, tailored to the needs of ELL students.
