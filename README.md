This project aims to explore and analyze topics from Arabic texts using the powerful BERTopic library. The project leverages the [saudinewsnet](https://huggingface.co/datasets/saudinewsnet) dataset to train the model and apply topic analysis.

## 🌟 Key Features

* **Text Preprocessing**: Includes a `clean_text` function for processing Arabic texts, which removes links, replaces numbers, standardizes spaces, and performs tokenization.
* **Advanced Topic Analysis**: Utilizes the BERTopic model to accurately and efficiently identify key topics within the dataset.
* **Model Saving and Reloading**: Allows you to easily save and reload the trained model for later use or to resume work.

## 🚀 Quick Start

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following packages installed in your Python environment:

```bash
pip install bertopic==0.16.0 datasets==2.16.1 Arabic-Stopwords==0.4.3 pandas nltk matplotlib seaborn
