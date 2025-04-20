# Langchain Research Agent

A simple AI agent built with Python and LangChain that uses Large Language Models (LLMs) via the Groq API and the Tavily Search API to research a given topic and provide a summary.

## Description

This project demonstrates how to build a basic autonomous agent capable of:
- Receiving a user-defined research topic.
- Interacting with an external search tool (Tavily Search API) to gather relevant, real-time information from the web.
- Utilizing a Large Language Model (e.g., Llama 3, Gemma, Mixtral hosted on Groq) to reason, process search results, and synthesize a concise summary.
- Operating within the ReAct (Reasoning and Acting) framework to show its step-by-step thought process.

## Features

-   Automated web research on any given topic.
-   Dynamic tool usage (Tavily Search) driven by LLM reasoning.
-   Summarization of findings using powerful LLMs.
-   Verbose output option to observe the agent's step-by-step thought process (ReAct).
-   Utilizes fast inference via the Groq API.

## Technologies Used

-   **Python 3.8+**
-   **LangChain:** Core framework for orchestrating LLM interactions and tool usage.
-   **Groq API:** Provides access to fast Large Language Models (e.g., Llama 3, Gemma).
-   **Tavily Search API:** Specialized search engine for AI agents.
-   **Jupyter Notebook:** For interactive development and demonstration.
-   **python-dotenv:** For managing API keys securely.

