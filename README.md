#  Next Word Predictor using Pruned LSTM

## Overview
This project implements a **Next Word Prediction** model using a **Long Short-Term Memory (LSTM)** network, trained on Wikipedia articles related to artificial intelligence, machine learning, and deep learning. To improve efficiency, the model incorporates **pruning techniques** that reduce unnecessary parameters without sacrificing performance.

##  Key Features
- **LSTM-based language modeling** for next-word prediction.
- **Structured and unstructured pruning** for model compression.
- **Wikipedia-based custom dataset** scraping and preprocessing.
- **97.39% prediction accuracy** after training.
- **Interactive next-word prediction** and sentence generation.


##  Technologies Used
- **PyTorch**
- **NLTK**
- **BeautifulSoup**
- **Matplotlib**
- **Wikipedia Scraping**

##  Performance Summary
| Metric                         | Value       |
|-------------------------------|-------------|
| Parameters Before Pruning     | 1,487,022   |
| Parameters After Pruning      | 1,122,672   |
| Final Model Accuracy          | **97.39%**  |


## Example Output
```
Input: They sometimes need a large
Output: They sometimes need a large database  ...
```

##  Visualization
- Loss and accuracy plotted over 30 epochs.
- Demonstrates efficient training and pruning.

##  Contributors
- Athul Krishna K L
- Govind Kumar
- Akshay P K
