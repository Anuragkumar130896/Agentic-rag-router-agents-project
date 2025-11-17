🔹 Agentic RAG Router & Multi-Agent System using LlamaIndex

This repository contains my implementation of an Agentic RAG (Retrieval-Augmented Generation) system powered by LlamaIndex, featuring:

✅ A Router Engine that dynamically selects query paths

✅ An Agent Reasoning Loop capable of step-by-step tool use

✅ A Multi-Document Research Agent with multi-index retrieval

The goal of this project is to demonstrate intelligent retrieval, automatic reasoning, tool-use, and agent behavior across multiple document sources — using only open-source frameworks.

🚀 Features
🔹 Router Engine

Dynamically picks the right query engine based on user request

Supports summarization vs deep retrieval mode

Uses LLM reasoning instead of hard-coded if/else logic

🔹 Agent Reasoning Loop

Multi-step self-correction and iteration

Tool usage through LlamaIndex’s agent framework

Designed for tasks that require planning, reflection, and reasoning

🔹 Multi-Document Agent

Works with multiple document indexes

Uses retrievers, vector stores, and indexes together

Enables cross-document reasoning and contextual synthesis

🧩 Files in This Repository
Notebook	Purpose
Router_Engine_using_Multi_Index_RAG.ipynb	Implements the router engine using multiple indexes and query engines

Building_an_Agent_Reasoning_Loop.ipynb	Creates a reasoning agent capable of multi-step tool usage

Building_a_Multi-Document_Agent.ipynb	Extends the agent to handle multiple documents and indexes

Each notebook is independent but can be combined to form a complete agentic RAG system.

🔧 Tech Stack
Component	Used
LLM Framework	LlamaIndex
Language Models	Open source (can be replaced with HF models)
Embeddings	Open-source or API-based
Runtime	Google Colab
Storage	Local / Colab / GitHub
Tools & Agents	LlamaIndex Query Engines & Tooling
▶️ How to Run
Option 1: Run in Google Colab after adding the api key



Option 2: Run Locally
pip install llama-index
pip install sentence-transformers
pip install nest_asyncio


Then open any notebook with Jupyter or VS Code.
