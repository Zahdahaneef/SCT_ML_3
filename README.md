# 🐱🐶 Cat vs Dog Image Classification using SVM

This project classifies images of cats and dogs using a Support Vector Machine (SVM) model. The dataset comes from the popular [Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats) on Kaggle. The images are preprocessed, flattened, and then used to train and evaluate an SVM model with a linear kernel.

---

## 📁 Dataset:

- **Contents**:
   * train.zip: Contains 25,000 labeled images of cats and dogs.
   * test1.ziP: Contains 12,500 unlabeled images for testing.
 
 # 🔓 Data Extraction
        
Unzipped train.zip and test1.zip.

 # 🖼️ Image Preprocessing

* Resized all images to 64x64.

* Flattened them into 1D arrays for SVM compatibility.

# Labels:

* 0 = Cat

* 1 = Dog

# 📊 Model Training

* Used SVC(kernel='linear') from sklearn.svm.

* Split dataset into 80% training and 20% testing using train_test_split.

# 📈 Model Evaluation

* Accuracy: 53.75%

* Metrics: Precision, Recall, F1-Score via classification_report.

#  🧪 Prediction on New Images
Loaded images from the test folder (test1/).


