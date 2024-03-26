
<!-- ABOUT THE PROJECT -->
## About The Project

I'm using this repo to work on AI-related projects. The goal is to learn how to use local open-source LLMs and finetune them with domain-specific data.

My local setup:
1. Ubuntu 22 via Windows WSL2
2. NVIDIA 3080TI
3. 32 GB RAM

<!-- GETTING STARTED -->
## Project 1: Getting Started

The first project is called LLM_with_memory. Here, the goal is to start learning how to use and build on top of OLLAMA. I'll be taking inspiration from Matthew Berman
https://www.youtube.com/watch?v=rIRkxZSn-A8&list=PLYeQgFYNGJtJ5k37wkeQGjMoHtbEXp4Sv

1. The modelfile was created to create a mistral-based LLM with a custom temperature and system prompt. In this case, I'm attempting to convince the LLM that it is a nanomaterials scientist.
2. main.py utilizes gradio to launch a chat with this LLM.
3. the converation_history list stores the conversation's history. This is eventually limited by the maximum number of tokens.
