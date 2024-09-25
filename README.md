# Automated-Text-to-SQL
This repository contains code related to my personal project of automating raw plain text to sql queries. This is one of my ongoing projects, I am currently exploring various transformer models to implement the same sich as T5, BERT etc.

## Goal of this work
To automate SQL queries from plain text
datasets used are spider: Yale Semantic Parsing and Text-to-SQL Challenge and WikiSQl 

## Models used
Experimented with T-5 model which still has scope for improvement but still has shown good performance for the same.
Created a custom pytorch dataset for the sql data to fine-tune my T5 model in this case, modifying the hyperparameters further could further enhance the model's performance

## T-5 Architecture

![image](https://github.com/user-attachments/assets/8bb73e3a-15ef-4979-9fe1-495e408d4580)

T5 transformers, also known as Text-to-Text Transfer Transformers, is a cutting-edge transformer-based language model developed by researchers at Google. It has gained widespread attention and acclaim in the field of Natural Language Processing (NLP) due to its innovative and unified approach to handling diverse NLP tasks. T5 represents a significant advancement in NLP models, as it introduces a novel text-to-text framework. Unlike traditional models that are designed to address specific tasks, T5 transformers treat all NLP tasks as text-to-text transformations. In this framework, both the input and output for various NLP tasks are treated as textual sequences, making the model more adaptable and versatile. Under this approach, T5 transformers can perform various tasks, including text classification, translation, summarization, question-answering, and more, by rephrasing the problem as a text generation task. This simplifies the model's architecture and training process, enabling it to leverage its pre-training knowledge effectively for downstream tasks.

