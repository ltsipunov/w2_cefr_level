# w2_cefr_level
 Project to estimate English CEFR level of subtitle files

The model is teached on  preestimated subtitles files  to predict CEFR levels of new files.


Essential catalogs structure:
- English_scores - database of preestimated subtitle files in .srt format
- Oxford_CEFR_level - Oxford Dictionaries with 5000 words demanded for CEFR levels A1-C2
- datasets - featured datasets  for model's teaching
Files structure :
data_collector.ipynb - program to get features from subtitle files
model.ipynb - model to be teached and predict   
movies_params.py - short interface file to explain features to model

The project is a workshop of Yandex Practicum
