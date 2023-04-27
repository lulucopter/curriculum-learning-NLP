Data Cartography data is downloaded from https://github.com/allenai/cartography

Code used to train model is adapted from https://github.com/utcsnlp/cs378_fp

Use 
```
python3 run.py --do_train --task nli --dataset snli --output_dir ./trained_model_nli/ --max_train_samples 11000 --curr y --carto_dataset ../cartography/data/data_map_coordinates/snli_roberta_0_6_data_map_coordina
tes.jsonl
```
to run curriculum learning

