# Coffee Classification using NDVI

This repository contains the source code used in the paper:

**"Scalable Coffee Crop Classification Using NDVI Time Series from SATVeg and Machine Learning Models"**  
Author: *Eva Laussac Diniz*

---

## Dependencies

Below are the main Python libraries used in each stage of the project:

### Data Pre-processing
- pandas
- datetime
- matplotlib
- scikit-learn

### Random Forest
- pandas
- matplotlib
- seaborn
- numpy
- os
- scikit-learn

### TiDE
- pandas
- numpy
- matplotlib
- seaborn
- copy
- torch
- os
- random
- datetime
- tqdm
- scipy

### XGBoost
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn
- xgboost

### KNN-DTW
- pandas
- matplotlib
- seaborn
- numpy
- os
- datetime
- scikit-learn
- tslearn
- tqdm

### SVM and Logistic Regression
- pandas
- matplotlib
- seaborn
- numpy
- os
- datetime
- scikit-learn

---

## Datasets

- **Main Dataset:** `satveg_coffee_merged_ndvi.xlsx`  
- **Validation Samples Folder:** `validation sample.zip`

---

## ⚠ Important Notice

This project was developed and tested using **Google Colab**, and the dataset paths are configured accordingly.

Make sure to update all file paths that reference datasets or input files.

```python
# Example - Data Pre-processing
full_dataset = pd.read_excel('/content/satveg_coffee_merged_ndvi.xlsx')

# Example - Validation Path
folder_path = '/content/dataset ndvi/validation sample'
