# w2_cefr_level
 Project to estimate English CEFR level of subtitle files

The objective is to predict recommended English level of a movie basing on it's subtitre file
The project consists if two tasks:
- to prepare data for teaching a model from subtitles files with prestimated levels
- to teach the model to make predictions 

That is multiclass classification with 4 classes.
In current version , final test predicts target with accuracy 0.52.

Essential catalogs structure:
- English_scores - catalogs of preestimated subtitle files in .srt format and  table of levels in .xls format
- Oxford_CEFR_level - Oxford Dictionaries with 5000 words demanded for CEFR levels A1-C2
- datasets - featured datasets composed from subtitres  for model's teaching

Files structure :
data_collector.ipynb - program to get features from subtitle files
model.ipynb - model to be teached and predict   

This project is a workshop in Data Science Yandex Practicum Course