# Intro-to-NLP
NLP Course Hands-on: TF-IDF • LDA • LSA • LangChain • OpenAI API
My NLP Course Notes & Experiments 🚀
Student learning journey through 365 Data Science's Introduction to NLP course + extra AI projects

This repository contains my personal Jupyter notebooks from the Introduction to NLP course. I've added my own experiments with modern tools like LangChain, OpenAI API, and advanced topic modeling.

📖 What I've Covered
Classical NLP: TF-IDF, LDA, LSA topic modeling

Sentiment Analysis: VADER, TextBlob, transformers

Modern AI: LangChain chatbots, OpenAI GPT models

Hands-on debugging: Environment setup, API keys, Jupyter troubleshooting

🛠️ My Environment
text
conda create --name nlp_env python=3.10
conda activate nlp_env
pip install openai langchain langchain-openai python-dotenv jupyterlab notebook nltk pandas matplotlib spacy textblob vaderSentiment transformers scikit-learn gensim seaborn torch ipywidgets
python -m spacy download en_core_web_sm
python -m ipykernel install --user --name=nlp_env
Kernel: Select nlp_env in Jupyter when running notebooks.

📁 Notebooks You'll Find
01-tf-idf-experiments.ipynb - Manual TF-IDF calculations

02-lda-topic-modeling.ipynb - LDA hands-on

03-langchain-openai-chatbot.ipynb - Marv the sarcastic dog

04-sentiment-pipeline.ipynb - Multiple sentiment analyzers

setup-debugging.ipynb - All my .env + kernel fixes
