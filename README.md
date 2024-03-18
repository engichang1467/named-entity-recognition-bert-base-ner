# Named Entity Recognition with BERT-base-NER

Welcome to the Named Entity Recognition with BERT-base-NER project! This repository focuses on utilizing the [`dslim/bert-base-NER`](https://huggingface.co/dslim/bert-base-NER) model to perform Named Entity Recognition (NER) tasks.

## Introduction

Named Entity Recognition (NER) is a natural language processing task where the goal is to identify and classify named entities mentioned in unstructured text into predefined categories such as person names, organizations, locations, dates, etc. `BERT-base-NER`, based on the powerful BERT architecture, offers state-of-the-art performance in NER tasks.

## Getting Started

### Environment Setup

To get started, create a virtual environment and activate it:

```bash
virtualenv venv
source venv/bin/activate
```

### Install Dependencies

Next, install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

### Run the Application

Now, you can run the application:

```bash
gradio app.py
```

This will start the application, allowing you to input text and the DistilBART-CNN model can now classify named entities.

## Usage

Simply input the text you want into the application's interface. The model will then process the input and provide a named entity of the text.

## Additional Resources

- Check out the model on [![Hugging Face Spaces](https://img.shields.io/badge/🤗%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/mca183/named-entity-recognition-bert-base-ner)
- Check out the Colab notebook for this project on [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/engichang1467/named-entity-recognition-bert-base-ner/blob/main/colab/test.ipynb)
- Explore more about the BERT-base-NER model [here](https://huggingface.co/dslim/bert-base-NER)

Feel free to reach out if you have any questions or feedback!
