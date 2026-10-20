# student-performance-prediction

Predicts whether a student will pass or fail (final grade of 10 or more out of 20)
using study time, absences, past failures, and family background.

## Dataset
UCI Student Performance dataset (`student-mat.csv`, 395 students), included in `archive.zip`.

## Models and results
| Model | Accuracy |
|-------|----------|
| Decision Tree (max_depth=4) | 64.56% |
| KNN (k=5) | 60.76% |

G1 and G2 were removed on purpose because they almost give away the final grade.

## How to run
Install the libraries: `pip install pandas scikit-learn matplotlib`

Unzip `archive.zip`, then open `student-pass-fail-prediction.ipynb` in Jupyter or Google Colab.
