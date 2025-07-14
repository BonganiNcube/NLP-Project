
# NLP Unsupervised Text Analysis

## Project Overview

This project explores **unsupervised text analysis** using two techniques:
1️. **Text Clustering** — to group similar documents automatically.
2️. **Topic Modeling** — to discover hidden topics in unlabelled text data.

These methods help make sense of large text collections without manual labeling.

 **Note:** This project was developed and run entirely on **Google Colab**, taking advantage of its free compute resources and easy notebook environment.

---

## Project 1: Text Clustering

**Description:**

* Uses **TF-IDF vectorization** and **KMeans clustering**.
* Groups similar documents based on their content.
* Reveals natural clusters or patterns in the data.

**Key methods:** TF-IDF, KMeans
**Example use cases:** News categorization, document grouping, content recommendation.

---

## Project 2: Topic Modeling

**Description:**

* Uses **Latent Dirichlet Allocation (LDA)** to extract hidden topics.
* Shows the most important keywords for each topic.
* Helps summarize and understand large text datasets.

**Key methods:** LDA, bag-of-words, tokenization
**Example use cases:** Research papers, news articles, customer reviews.

---

## ⚙️ How to Run

1️. **Open on Google Colab**

Open each notebook directly in Google Colab for easy access:

* `clustering.ipynb` – Unsupervised text clustering
* `topic_modeling.ipynb` – Topic modeling with LDA

 2. **Install required libraries** (run this in a Colab cell if needed)

```python
!pip install pandas scikit-learn nltk gensim
```

---

## Results

* **Clustering:** Visualizes which documents belong to which cluster.
* **Topic Modeling:** Prints top keywords for each discovered topic.

---

## Example Outputs

| Project        | Example Output                   |
| -------------- | -------------------------------- |
| Clustering     | Table with text + cluster ID     |
| Topic Modeling | List of topics with top keywords |

---

## Libraries Used

* Python
* scikit-learn
* gensim
* NLTK
* pandas

---

## Author
Bongani Ncube

---
