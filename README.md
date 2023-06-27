# Text Personality and Emotion Computing

### Datasets used in this research
- [PELD](https://github.com/preke/PELD)
- [WASSA 2022](https://codalab.lisn.upsaclay.fr/competitions/834#learn_the_details-datasets)

Technology is evolving quickly, and Text-based Personality Computing (TPC) and automatic emotion assessment have attracted a lot of research interests. This study explores their efficiency as a replacement of traditional methods in personality and emotion assessment. To accomplish the aim of investigation of correlations between personality traits and emotions in automated detection two datasets with annotated emotions and Big Five personality traits are used, and supervised transformer-based methods are implemented to predict personality traits and emotions. The utilized evaluation metrics are accuracy, precision, recall and F1-score. Correlations between emotions and traits are computed, and the alignment between the correlations from the original and the predicted data is assessed using the Pearson correlation, RMSE, MAE, and the Wilcoxon signed-rank test. Furthermore, the correlations from the original data are compared to established theories. The findings reveal that DistilBERT and DeBERTa perform the best in predicting personality traits and emotions. The correlations from the predicted data closely agree with those from the original data. Some of the pairs (e.g., fear-stability, anger-conscientiousness) align with established theories while some others do not (e.g., neutralism-all personality traits). This research contributes to the understanding and applicability of TPC in personality and emotion assessment.

### Citation
Beyond Words: Unmasking the Relationship between Emotions and Personality Traits, Pinelopi Theotoki,  June 2022
