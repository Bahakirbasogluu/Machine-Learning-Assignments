# Machine Learning Assignments

Assignments for AIN313 Machine Learning Laboratory at Hacettepe University (fall 2022), by Baha Kırbaşoğlu. Each notebook has a short theory part (answers embedded as images) followed by a programming part; the notebooks were written for Google Colab.

| File | Task | Methods | Dataset |
| --- | --- | --- | --- |
| `Assignment1/assignment_1_Baha_Kırbaşoğlu.ipynb` | Disease detection from chest X-ray images (covid, pneumonia, normal) | k-NN and distance-weighted k-NN written from scratch with Euclidean distance, on Canny edge and Gabor filter features of 32x32 images; evaluated with confusion matrix, precision, recall and accuracy | [Multiclass chest X-ray disease dataset (Kaggle)](https://www.kaggle.com/datasets/saifurrahmanshatil/multiclass-chest-xray-disease-dataset) |
| `Assignment2/Assignment_2_Baha_Kırbaşoğlu.ipynb` | Book genre classification from book descriptions | Naive Bayes written from scratch with Laplace smoothing; bag-of-words (unigram, bigram) and TF-IDF features, each with and without stop words | [Book dataset (Google Drive)](https://drive.google.com/drive/folders/1wqWj9XsyStvAXohzYNjOIIQQ2SOwCkpD) |
| `Assignment3/Assignment_3_Baha_Kırbaşoğlu.ipynb` | Flower species classification from images, with a bonus run on the chest X-ray data | Multi-layer perceptrons and small CNNs in PyTorch, compared across hidden layer sizes, optimizers (SGD, Adam), learning rates and batch sizes | [Flowers dataset (Google Drive)](https://drive.google.com/file/d/1PyTLK4lCJR7kvntCTxyiTSU5vegDw2dz/view) |

Requirements: Python 3, Jupyter or Google Colab, numpy, pandas, matplotlib, opencv-python, scikit-learn, nltk, torch, torchvision.
