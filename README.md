# 🧮 Identifying the Best Predictor for Insurance Claims  
This project identifies the **single most effective feature** for predicting whether a customer will file an insurance claim. The dataset and problem setup are part of a DataCamp learning exercise. The dataset originally from [Accenture website](https://www.accenture.com/_acnmedia/pdf-84/accenture-machine-leaning-insurance.pdf).

---

## 🔍 What I Did
- Loaded and explored the dataset of customer insurance records.
- Removed the `id` column as it does not contribute to prediction.
- Trained a classification model for each feature individually to predict the `outcome`.
- Evaluated each model's accuracy on a validation set.
- Identified the feature with the highest predictive accuracy.
- Stored the result in a summary DataFrame called `best_feature_df`.

---

## 📊 Summary Output

| best_feature | best_accuracy |
|--------------|----------------|
| *driving_experience* | *0.7771* |



---

## 📁 Files

- `notebook.ipynb`: Jupyter notebook containing all code, analysis, and results.
- `README.md`: Summary and context of the project.
- `Data`: Folder containing the dataset and the image in the notebook.

---

## 📝 Credits  
This project is adapted from the "Which features best predict insurance claims?" project on [**DataCamp**](https://projects.datacamp.com/projects/1645).

Feel free to extend this analysis with additional models or feature engineering techniques!
