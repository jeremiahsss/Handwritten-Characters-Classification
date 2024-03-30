# Handwritten-Characters-Classification

## Project Description
This study presents a detailed analysis of the performance of three supervised machine learning models in classifying handwritten characters using the subset version of the EMNIST by-class dataset. The three models used in this study are k-Nearest Neighbors (KNN), Random Forest, and Multi-Layer Perceptron (MLP). The models followed the same preprocessing pipeline, including normalization and Principal Component Analysis (PCA). The performance of the models was evaluated based on accuracy, precision, recall, and F1-score. Our experiment results demonstrated that while KNN and Random Forest achieved satisfactory results, MLP outperformed the other models in all metrics evaluated and with the shortest tuning time. Furthermore, our results highlighted the presence of class imbalance, with all models exhibiting lower accuracy in the minority class compared to the majority class. This observed disparity confirms the importance of handling class imbalance appropriately to achieve accurate and reliable performance across all classes.



## Dataset Description
Download EMNIST_Byclass_Small.zip required for the study using the provided link below.
https://drive.google.com/file/d/1qEoWitIzaRUWRFJsy7BKWZdvKecuck4X/view?usp=sharing

The EMNIST ByClass dataset was introduced in 2017 and consists of a total of 814,255 images of handwritten characters including numerical digits and the English alphabet. The smaller subset version of this dataset is used in this study due to the limitation in computing resources. The subset comprises 100,000 training data and 20,000 test data. Each input image is a 28x28 pixel grey-scale image, and there are 62 classes in total, corresponding to the 10 digits, 26 lowercase alphabet letters and 26 uppercase alphabet letters. The subset dataset also maintains the unbalanced class distribution as the original dataset, meaning there is a high variation in the number of samples per class. This poses several challenges for machine learning models, which may lead to biased models and overfit to the majority classes and struggle to classify the minority classes accurately.
