FULL NLP PIPELINE (Python 3.11)

PIPELINE ORDER
00_filter_and_resplit.ipynb
01_relevance_models.ipynb
02_group_classifier.ipynb
03_cross_encoder.ipynb
04_hierarchical_transformer.ipynb
05_compare_models.ipynb
06_topN_hardneg_improvement.ipynb

STEP 00:
- merge train+test
- drop demand_id with exclude==1
- resplit 70/30
- single-sample labels stay in train
