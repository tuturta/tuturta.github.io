---
layout: page
title: Language Proficiency and Authorship Classification Strength
description: Course Project (CS-433) | 2023.12 - 2024.02
img: assets/img/nlp.jpg
importance: 7
category: Academic
---

As part of the CS-433 Machine Learning course at EPFL, I contributed to a research project investigating how **language proficiency influences stylometric authorship classification** in online text. Our work explored whether differences between native and non-native English speakers affect the performance of traditional stylometric models.  

We built a large-scale dataset of **over one million Reddit comments** from users in *r/languagelearning*, where authors self-reported their English proficiency levels. Using this data, we developed **multi-class Support Vector Machine (SVM)** models with **Writeprints-inspired stylometric features**, and evaluated them across three author cohorts: native, non-native, and mixed-proficiency writers.

Our results showed that **models trained on mixed-proficiency datasets** achieved the **highest classification accuracy (up to 100%)**, outperforming both native-only and non-native-only models. We also found that **non-native authors benefited most from parameter tuning**, with an F1-score improvement of +22%, highlighting the importance of data diversity in authorship attribution.

This project strengthened my skills in machine learning, natural language processing (NLP), feature engineering, and high-performance computing, using tools such as Python, scikit-learn, spaCy, langdetect, and the EPFL SCITAS supercomputer. It also deepened my interest in fair and interpretable AI, particularly in the context of language and communication.

--- 

**Supervisors:**  
[Dr. Rebekah Overdorf](mailto:rebekah.overdorf@unil.ch) – Faculty of Law, Criminal Justice and Public Administration, UNIL

**Resources:**
- 📄 [Read the report](assets/pdf/nlp.pdf)  
- 🧬 [EPFL Course – CS-433: Machine Learning](https://edu.epfl.ch/coursebook/en/machine-learning-CS-433)  
- 💻 [GitHub Repository](https://github.com/CS-433/project2-authclass)
