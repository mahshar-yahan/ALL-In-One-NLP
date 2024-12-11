# NLP and LLMs for Anime Series Analysis

In this project, we will analyze an anime series using NLP and LLMs. The project includes scraping your own dataset, using zero-shot classifiers, building a custom LLM text classifier, using Named Entity Recognition (NER) to create a character network, and developing a character chatbot to chat with your favorite characters. Finally, all components will be integrated into a web GUI with Gradio.

## Overview

This project is divided into 5 main parts, each with its own folder containing the necessary code:

### 1. `crawler`
- This folder contains the code for web scraping the internet to build a comprehensive dataset about the anime using **Scrapy**.

### 2. `character_network`
- This folder contains the code for creating a character network using **Spacy's NER model**, **NetworkX**, and **PyViz**.

### 3. `text_classifier`
- This folder contains the code for training a **text classifier** that can classify text into multiple categories.

### 4. `theme_classifier`
- This folder contains the code for extracting the main themes of the series using **Zero-shot classifiers**.

### 5. `character_chat_bot`
- This folder contains the code for building a **character chatbot** using LLMs to chat with your favorite characters from the series.

## Requirements

Before running the code, make sure to install all necessary packages by running:

```bash
pip install -r requirements.txt
