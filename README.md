# vLLM_Interface
Jupyter interface for running and testing LLMs using the vLLM inference server with support for HuggingFace and GGUF models.

# vLLM Interface Runner 🚀

This repository contains code and configuration to run large language models (LLMs) using the [vLLM](https://github.com/vllm-project/vllm) inference engine. It enables fast and memory-efficient deployment of transformer models for various NLP tasks.

## 🔧 Features

- ⚡ Efficient LLM serving using vLLM
- 🧠 Supports models like Mistral, LLaMA, Falcon, and more
- 🌐 REST API endpoint exposure for easy integration
- ✅ Jupyter Notebook included for testing and interface control

## 📁 Contents

- `serve_model.ipynb`: Notebook to start and interact with the vLLM server
- `model_runner.py`: Optional script to run models as Python script
- `requirements.txt`: Dependencies for setting up the environment

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/vLLM-Interface-Runner.git
   cd vLLM-Interface-Runner
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Start the vLLM server:
   ```bash
   vllm serve <model-name> --dtype auto

5. Run the Jupyter notebook:
   ```bash
   jupyter notebook serve_model.ipynb
