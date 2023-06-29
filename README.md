# Document QA Experiment using LangChain + ChromaDB + OpenAI API

This project intends to take my personal Markdown document collection (my notes) and make them searchable through a GPT engine. This can be used further on as a corporate knowledge management system or an AI trainer for company knowledge.

## Methodology

This is a fork of an example repository provided from LangChain: https://python.langchain.com/docs/use_cases/question_answering/

In this case, some adaptions were made for the implementation, including custom GitHub search path, authentication for querying the GitHub API, and local-system modifications to match file types into the LangChain process chain. 

## Objectives

The objective is to experiment and create a functional prototype that can aid in the creation of a functioning QA bot, both for things related to internal company trainings, but also to things related to HR, Meetings Docs, between others. Ideally, the prototype will derive in a fully-functioning Slack bot. 

## Limitations

For now, the quality of the answers is constrained to the data provided, and therefore, could provide inexact answers. This can be solved increasing the quality and range of the data, as well as tweaking LLM model parameters. 


# Architecture and Process

The following diagram depicts the process that the documents follow to be processed by the engine. 

![Documentation for Chroma+LangChain+GPT Custom Markdown GPT](https://github.com/dfcantor/chroma-langchain-custom/assets/88911560/132ea0a9-2b55-4645-8ca2-3639c7f43487)
