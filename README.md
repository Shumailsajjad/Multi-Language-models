### Multi-Language-Models
Machine Learning Project

This project serves as a bridge between theoretical knowledge and practical application in real-world research scenarios. It has equipped me with skills essential for my further industry pursuits. 

The classification project employed a mixed-method approach to develop a multi-language recognition model utilizing three prominent supervised machine learning techniques. To facilitate this, I conducted a survey on the SurveyCTO application comprising 100 everyday questions in Urdu, English, and a mix of both languages. Using Praat software, I recorded responses and represented them as 13-dimensional Mel-frequency Cepstral Coefficients (MFCCs), a widely adopted representation for speech classification tasks.

The collected data was divided into 80:20 train-test sets. KNN, Support Vector Machines, and Neural Networks algorithms were trained on these MFCC coefficients to classify audio recordings into three classes: "English (en)," "Urdu (ur)," and "Mixed (ue)." Each supervised technique underwent 5-fold cross-validation, and the validation and training losses were plotted using Python. The models' robustness was evaluated based on accuracy, macro-average (precision, recall, F1), and confusion matrices on the test set.

## Dataset

MFCC features extracted from audio recordings of the project team

## Files

- **MFCC from audio recordings.ipynb:** Extracting features from audio recordings linked and saving them as a CSV file.
- **dataset.csv:** MFCC features for the entire group across three classes: "English (en)," "Urdu (ur)," and "Mixed (ue)."
- **KNeighbours Classifier.ipynb:** Training and testing the KNeighbours model on the dataset.
- **SVC + Hyperparameter tuning.ipynb:** Training and testing the SVC model on the dataset with hyperparameter tuning.
- **Multilayer Perceptron.ipynb:** Training and testing the Multilayer Perceptron model on the dataset.
- **Comparative Study of Models.ipynb:** Selection of the best model across all three using performance metrics on the test set.



