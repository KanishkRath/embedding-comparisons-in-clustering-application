
# embedding-comparisons-in-clustering-application

- This repository presents a novel autoencoder architecture designed for news article clustering.
- It compares its performance against established methods like TF-IDF, GLoVe, Word2Vec, and BERT.
- Evaluation metrics include Davies-Bouldin and Calinski-Harabasz Indices.

## Notebooks

### Comparison of Existing Models
- [`Comparison_Existing_Models.ipynb`](Comparison_Existing_Models.ipynb): Compares existing models such as TF-IDF, GLoVe, Word2Vec, and BERT for news article clustering.

### Autoencoder for News Clustering
- [`Autoencoder_News_Clustering.ipynb`](Autoencoder_News_Clustering.ipynb): Demonstrates an autoencoder-based approach for news article clustering, showcasing its superiority over traditional methods.

## Getting Started

### Cloning the Repository

1. Clone the repository:

    ```bash
    git clone https://github.com/KanishkRath/embedding-comparisons-in-clustering-application.git
    cd embedding-comparisons-in-clustering-application
    ```

2. Access the notebooks:

    - Locate the notebooks within the cloned repository to explore and execute them using Jupyter Notebook.

### Usage

- Ensure you have Jupyter Notebook installed.
- Open the notebooks to run and explore the functionalities.
- Customize code segments or parameters for experimenting with different datasets or settings.

### Comparison Summary

#### Model Comparison Table

| Method                            | Davies Bouldin Index | Calinski Harabasz Index |
|-----------------------------------|----------------------|-------------------------|
| TF-IDF                            | 8.5827               | 14.52                   |
| Word2Vec                          | 1.5521               | 484.77                  |
| GLoVe                             | 1.7722               | 369.76                  |
| BERT                              | 3.0890               | 125.49                  |
| Autoencoder                       | 0.8967               | 1250.82                 |
| Autoencoder with One Hot Encoding | 0.8288               | 3298.19                 |


