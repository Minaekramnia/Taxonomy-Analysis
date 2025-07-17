# World Bank PAD and Taxonomy Analyzer
An AI-powered application for analyzing, extracting insights, and interacting with World Bank documents.

Overview
The World Bank PAD Analyzer is an AI-powered tool designed to streamline the analysis of Project Appraisal Documents (PADs). Developed as part of the World Bank Education Global Practice's data science initiative, this tool enables teams to extract insights, classify project components, and enhance planning through advanced natural language processing (NLP) and Retrieval-Augmented Generation (RAG) workflows.

Key Features

* Smart Document Parsing: Leverages high-fidelity OCR (using Mistral) for accurate text extraction from complex World Bank PDFs.
* AI Chat with Documents: Interact with PADs using a question-answering interface powered by GPT-based models, trained to understand education project language.
* Automated Insights & Classification: Extract key topics and match them against a curated education taxonomy, with support for both semantic similarity and fine-tuned model classification.
* Interactive Analytics Dashboard: Monitor processing status, token usage, model costs, and topic extraction metrics in real-time.
* Multi-Model & Fine-Tuned Pipeline: Includes OpenAI GPT-4, open-source LLMs, and custom fine-tuned classifiers for taxonomy tagging.
* Advanced RAG Pipeline: Combines FAISS-based semantic search with LLMs to provide accurate, evidence-based responses from long-form PAD documents.
