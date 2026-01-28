ONE-NOTEBOOK NLP PIPELINE (Python 3.11)

Files:
- full_pipeline_end_to_end.ipynb  (run top-to-bottom)
- requirements.txt

Expected inputs (edit paths in the notebook CONFIG cell):
- train.csv
- test.csv
- labels.csv  (must include columns: demand_id, exclude; exclude==1 means drop)

Expected columns in train/test:
- text
- demand_id
- group_id
- relevant OR relevance (0/1)
Optionally: other columns are preserved.

Outputs (created in ./artifacts):
- train_clean.csv, test_clean.csv
- relevance_model.joblib
- group_model.joblib
- cross_encoder/ (HF model + tokenizer)
- hierarchical_transformer.pt + metadata.json
- comparison_metrics.csv
