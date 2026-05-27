[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/drive/1RjfAjjoBB5kIK1O4eKXBhsWtOOHROhNQ?usp=drive_link

\##Exoplanet Detection using 1D CNN

A deep learning model that detects exoplanets by analyzing 

stellar light curves from NASA's Kepler Space Telescope.



\## How it works

Uses the \*\*Transit Method\*\* — detecting periodic dips in 

starlight caused by a planet passing in front of its star.



\## Model Architecture

\- 3 layers of 1D Convolutional Neural Networks

\- BatchNormalization + Dropout for regularization

\- 445,825 trainable parameters

\- Binary classification: Planet vs No Planet



\## Results

| Metric | Score |

|--------|-------|

| Overall Accuracy | 99% |

| No Planet Recall | 100% |

| Has Planet Recall | 60% |

| Has Planet Precision | 60% |



\## Dataset

\- NASA Kepler Space Telescope data

\- 5087 training stars, 570 test stars

\- 3197 flux measurements per star

\- Severe class imbalance handled with SMOTE



\## Tech Stack

Python, TensorFlow, Keras, scikit-learn, 

imbalanced-learn, pandas, numpy, matplotlib



\## How to Run

Open in Google Colab:

1\. Mount Google Drive

2\. Load exoTrain.csv and exoTest.csv

3\. Run all cells

