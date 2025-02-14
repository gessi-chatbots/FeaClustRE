# FeaClustRE – A Feature Clustering and Analysis Visualization Tool
---

Documentation writing in progress...

---

before using install spacy en_core_web_sm

```python -m spacy download en_core_web_sm```


Example for calling csv_to_json.py

```python backend/data-preprocessing/csv_to_json.py -i data/COMMUNICATION/reviews_with_features.csv -o data/COMMUNICATION/features --from 2023-01-01 --to 2023-12-31```

Example for calling dendogram_generation.py client

```python client/dendogram_generation.py data/COMMUNICATION/all/features_org.telegram.messenger.json```

Example for calling visualizator.py client

```python client/dendogram_generation.py ./data/COMMUNICATION/all/features_com.discord.json bert-embedding-cosine average 0.2```
