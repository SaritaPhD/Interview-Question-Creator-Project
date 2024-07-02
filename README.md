# Interview-Question-Answer-Creator-Project (Generative AI Project)
## Overview
-The Interview Question Creator is a web application that automates the generation of interview questions and answers from PDF documents. It utilizes FastAPI for the backend, LangChain for document processing, and OpenAI API for generative AI capabilities.

### Features
- File Upload: Users can upload PDF documents containing interview-relevant content.
- Automated Processing: LangChain processes uploaded PDFs to extract key information.
- Question Generation: Utilizes OpenAI API and LangChain to generate interview questions based on extracted content.
- Answer Generation: Generates corresponding answers using a language model pipeline integrated with OpenAI API.
- CSV Export: Saves generated questions and answers in a structured CSV format for easy analysis and sharing.

### Dependencies:
- FastAPI: Web framework for building APIs with Python.
- LangChain: Library for document processing and text generation.
- OpenAI API: Provides generative capabilities for question and answer generation.

### How to run?

1. Create an environment

```bash
conda create -n interview python=3.10 -y


conda activate interview

```

2. install requirements

```bash
pip install -r requirements.txt
```


```bash
python app.py
```



