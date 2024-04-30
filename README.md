
<!-- ABOUT THE PROJECT -->
## About This Repo

I'm using this repo to work on AI-related projects. The goal is to learn how to use local open-source LLMs and finetune them with domain-specific data.

My local setup:
1. Ubuntu 22 via Windows WSL2
2. NVIDIA 3080TI
3. 32 GB RAM

<!-- GETTING STARTED -->
## Project 1: Getting Started

The first project is called [LLM_with_memory](https://github.com/nmarcella/AI_projects/tree/main/LLM_with_memory). Here, the goal is to start learning how to use and build on top of OLLAMA. I'll be taking inspiration from [Matthew Berman](https://www.youtube.com/watch?v=rIRkxZSn-A8&list=PLYeQgFYNGJtJ5k37wkeQGjMoHtbEXp4Sv)

1. The modelfile was created to create a mistral-based LLM with a custom temperature and system prompt. In this case, I'm attempting to convince the LLM that it is a nanomaterials scientist.
2. main.py utilizes gradio to launch a chat with this LLM.
3. the converation_history list stores the conversation's history. This is eventually limited by the maximum number of tokens.

## Project 2: Applying what I've learned so far.

In my second project, I'm building a functional application called [Dog Detector](https://github.com/nmarcella/AI_projects/tree/main/Dog_Detector) on top of OLLAMA. The goal of my application is to use the multimodal vision/text capabilities of the LLaVa model to analyze a video camera feed and determine whether or not my dogs are on the couch :).

1. I'm using a remote [Google Colab](https://colab.google/) instance to run OLLAMA on a T4 GPU. Thanks to [Tech With Marco](https://www.youtube.com/watch?v=Qa1h7ygwQq8)
2. [ngrok](https://ngrok.com/) is used to make the Colab instance accessible on the internet.
3. The GPU_server.ipynb is used to setup OLLAMA on the GPU and forward with ngrok.
4. The Camera_dog_test.ipynb notebook is where the magic happens.

<img src="https://raw.githubusercontent.com/nmarcella/AI_projects/main/Dog_Detector/src/common/images/test1.webp" width="300" height="300" alt="alt text">
