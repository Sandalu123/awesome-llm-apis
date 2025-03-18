# 🚀 Ultimate Guide to LLM Models and APIs 🌟

Welcome to your comprehensive guide for selecting the perfect Large Language Model (LLM) or API for your projects! Whether you're looking for free options, self-hostable solutions, or powerful paid APIs, we've got you covered. Let's dive in! 💻🔍

## Free LLM APIs 🎁

These APIs offer free access to powerful LLMs with some limitations on usage volume or features.

| Name | Description | Link | Limitations |
|------|-------------|------|-------------|
| OpenRouter | Access to multiple LLMs including DeepHermes 3 and Llama 3 | [OpenRouter](https://openrouter.ai/) | 20 requests/minute, 200 requests/day |
| DeepSeek R1 | Family of models with various sizes and distillations | [DeepSeek](https://deepseek.ai/) | Rate limits vary by model |
| Dolphin 3.0 Mistral 24B | Implementation of the Mistral model | [Dolphin](https://dolphin-tech.io/) | Rate limits apply |
| Gemini 2.0 Flash Lite Preview | Google's experimental AI model | [Google AI Studio](https://ai.google.dev/) | Data usage restrictions outside UK/CH/EEA/EU |
| Mistral (La Plateforme) | Free tier requires opting into data training | [Mistral](https://mistral.ai/) | Requires phone number verification |
| HuggingFace Serverless Inference | Inference for various open models | [HuggingFace](https://huggingface.co/inference-api) | Limited to models smaller than 10GB |
| Cerebras | Offers Llama 3.1 8B model | [Cerebras](https://cerebras.com/) | Free tier restricted to 8K context |
| Together AI | Platform for developing and deploying AI models | [Together AI](https://together.ai/) | Rate limits apply |

## Self-Hostable LLM Models (RTX 4090 Compatible) 🏠

Run these models locally on consumer-grade hardware like the RTX 4090.

| Model Name | Description | Strengths | Parameter Size | License | Quantization Support | Memory Requirements | Link |
|------------|-------------|-----------|----------------|---------|----------------------|---------------------|------|
| LLaMA 2 | Meta's open-source language model | Strong general-purpose performance, multilingual capabilities | 7B, 13B, 70B | Custom (non-commercial) | Yes | 7B: 10GB VRAM, 13B: 20GB VRAM | [Meta LLaMA 2](https://ai.meta.com/llama/) |
| Mistral | Efficient architecture with strong performance | High efficiency, good reasoning capabilities | 7B, 70B | Apache 2.0 | Yes | 7B: 10GB VRAM, 70B: 40GB VRAM | [Mistral AI](https://mistral.ai/) |
| Falcon | Open-source model from Technology Innovation Institute | Strong coding and reasoning abilities | 7B, 40B | Apache 2.0 | Yes | 7B: 10GB VRAM, 40B: 35GB VRAM | [Falcon LLM](https://falconllm.tii.ae/) |
| Qwen | Alibaba Cloud's open-source model | Strong multilingual support and reasoning | 7B, 14B | Apache 2.0 | Yes | 7B: 10GB VRAM, 14B: 20GB VRAM | [Qwen AI](https://qwen.ai/) |
| OpenAssistant | Community-developed conversational model | Strong dialogue capabilities | 7B, 12B | Apache 2.0 | Yes | 7B: 10GB VRAM, 12B: 25GB VRAM | [OpenAssistant](https://openassistant.io/) |
| RedPajama | Open-source model based on LLaMA architecture | Good performance with efficient training | 3B, 7B | Apache 2.0 | Yes | 3B: 8GB VRAM, 7B: 15GB VRAM | [RedPajama](https://redpajama.info/) |
| Phi-4 | Microsoft's open-source model | Strong reasoning and mathematical abilities | 14B | MIT | Yes | 20GB VRAM | [Microsoft Phi](https://microsoft.github.io/phi/) |
| GPT4All | Collection of models optimized for local deployment | Easy to deploy, good performance on consumer hardware | 3B, 7B | Varies by model | Yes | 3B: 8GB VRAM, 7B: 15GB VRAM | [GPT4All](https://gpt4all.io/) |
| h2oGPT | H2O.ai's open-source model with RAG capabilities | Strong for document understanding and retrieval | 7B, 13B | Apache 2.0 | Yes | 7B: 10GB VRAM, 13B: 20GB VRAM | [h2oGPT](https://gpt.h2o.ai/) |

## Paid LLM APIs 💰

These APIs offer powerful LLM capabilities with flexible pricing models.

| Model | Provider | Input Price ($/million tokens) | Output Price ($/million tokens) | Context Length | Max Output Tokens | Link |
|-------|----------|---------------------------------|----------------------------------|----------------|-------------------|------|
| gpt-4.5 | OpenAI | 75.00 | 150.00 | 128k | 16,384 | [OpenAI](https://openai.com/) |
| gpt-4o | OpenAI | 2.50 | 10.00 | 128k | 16,384 | [OpenAI](https://openai.com/) |
| o1-2024-12-17 | OpenAI | 15.00 | 60.00 | 200k | 100,000 | [OpenAI](https://openai.com/) |
| o3-mini-high | OpenAI | 1.10 | 4.40 | 200k | 100,000 | [OpenAI](https://openai.com/) |
| Claude 3.7 Sonnet | Anthropic | 3.00 | 15.00 | 200k | 128,000 | [Anthropic](https://anthropic.com/) |
| DeepSeek-R1 | DeepSeek | 0.55 | 2.19 | 64k | 8,000 | [DeepSeek](https://deepseek.ai/) |
| DeepSeek-V3 | DeepSeek | 0.27 | 1.10 | 64k | 8,000 | [DeepSeek](https://deepseek.ai/) |
| Gemini-2.0-Flash-001 | Google | 0.10 | 0.40 | 1,000k | 8,192 | [Google AI](https://ai.google.dev/) |
| Qwen2.5-Max | Alibaba | 1.60 | 6.40 | 32k | 8,192 | [Qwen AI](https://qwen.ai/) |
| Qwen-Plus-0125 | Alibaba | 0.40 | 1.20 | 131k | 8,192 | [Qwen AI](https://qwen.ai/) |

## How to Choose the Right LLM Model or API? 🤔

1. **Budget**: Determine if you need a free solution or if you're willing to pay for enhanced capabilities.
2. **Use Case**: Match the model's strengths to your specific needs (e.g., coding, multilingual support, reasoning).
3. **Hardware**: If self-hosting, ensure your hardware meets the model's memory requirements.
4. **Scalability**: Consider if you need to scale usage up or down based on demand.
5. **Integration**: Check if the API or model works with your existing systems and workflows.

## Tools for Self-Hosting 🛠️

- **OpenLLM**: Simplifies running open-source LLMs with API endpoints
- **llama.cpp**: Optimized C/C++ implementation for running models on CPU/GPU
- **vLLM**: High-performance inference engine for LLMs
- **Text Generation Inference (TGI)**: Fast inference solution from Hugging Face

## Contributing 🤝

If you know of other free LLM APIs or self-hostable models that should be included in this list, please submit a pull request with the relevant information.

## License 📜

This repository is licensed under the MIT License.
