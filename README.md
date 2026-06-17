# Awesome Free LLM APIs 🚀

*A curated, auto-updated directory of Large Language Model (LLM) APIs with permanent free tiers or trial credits. Updated daily by Hermes bots.*

## Quick Comparison Table

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit | Key Models | API Key Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇨🇳 **BigModel (Zhipu AI)** | First-Party | 🇨🇳 | ✅ Yes | GLM-4-Flash and GLM-4.6V-Flash are permanently free with credit card-free signup | `glm-4-flash`, `glm-4v-flash` | [Get Key 🔑](https://open.bigmodel.cn/) |
| 🇺🇸 **Cerebras** | Inference Provider | 🇺🇸 | ✅ Yes | Free tier, no credit card. Ultra-fast inference (~2,600 tok/s). 1M tokens/day cap. 8K context cap on free tier. | `llama3.1-8b`, `llama3.1-70b` | [Get Key 🔑](https://cloud.cerebras.ai/) |
| 🇨🇦 **Cohere** | First-Party | 🇨🇦 | ✅ Yes | 20 requests/minute 1,000 requests/month | `command-r`, `command-r-plus`, `command-r7b` | [Get Key 🔑](https://dashboard.cohere.com/api-keys) |
| 🇺🇸 **Fireworks AI** | Inference Provider | 🇺🇸 | ✅ Yes | $1 in free trial credits on signup | `llama-v3p1-405b-instruct` | [Get Key 🔑](https://fireworks.ai/) |
| 🇺🇸 **Google AI Studio** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Gemini 1.5 Flash: 15 RPM, 1500 RPD
Gemini 1.5 Pro: 5 RPM, 50 RPD
Gemini 2.5 Flash: 15 RPM, 1500 RPD | `gemini-1.5-flash`, `gemini-1.5-pro`, `gemini-2.5-flash` (+1 more) | [Get Key 🔑](https://aistudio.google.com/app/apikey) |
| 🇺🇸 **Groq** | Inference Provider | 🇺🇸 | ✅ Yes | Free tier, no credit card. Ultra-fast LPU inference. [^2] | `llama-3.3-70b-versatile`, `llama-3.1-8b-instant`, `mixtral-8x7b-32768` (+1 more) | [Get Key 🔑](https://console.groq.com/keys) |
| 🇫🇷 **Mistral AI** | First-Party | 🇫🇷 | ✅ Yes | Free "Experiment" plan, no credit card. ~1B tokens/month. Prompts may be used to improve models. | `mistral-large-latest`, `mistral-small-latest`, `codestral-latest` | [Get Key 🔑](https://console.mistral.ai/api-keys) |
| 🇺🇸 **NVIDIA NIM** | Inference Provider | 🇺🇸 | ✅ Yes | 40 requests/minute | `llama-3.1-405b-instruct`, `llama-3.1-nemotron-70b-instruct` | [Get Key 🔑](https://build.nvidia.com/) |
| 🇺🇸 **Novita AI** | Inference Provider | 🇺🇸 | ✅ Yes | $0.50 in free credits, occasionally runs free models | `llama-3.1-8b-instruct`, `llama-3.1-70b-instruct` | [Get Key 🔑](https://novita.ai/) |
| 🌐 **OpenRouter** | Inference Provider | 🌐 | ✅ Yes | 20 RPM, 50 RPD free models (up to 1,000 RPD with $10 lifetime top-up) | `nex-n2-pro:free`, `nemotron-3.5-content-safety:free`, `nemotron-3-ultra-550b-a55b:free` (+12 more) | [Get Key 🔑](https://openrouter.ai/keys) |
| 🇺🇸 **SambaNova** | Inference Provider | 🇺🇸 | ✅ Yes | Free tier, no credit card. Ultra-fast RDU inference. 20 RPM, 200K tokens/day. [^8] | `Llama-3.1-8B-Instruct`, `Llama-3.1-70B-Instruct`, `Llama-3.1-405B-Instruct` | [Get Key 🔑](https://cloud.sambanova.ai/) |
| 🇨🇳 **SiliconFlow** | Inference Provider | 🇨🇳 | ✅ Yes | Permanently free models, no credit card required. 200+ paid models also available. | `DeepSeek-V3`, `DeepSeek-R1-Distill-Qwen-7B`, `Qwen2.5-Coder-7B-Instruct` | [Get Key 🔑](https://siliconflow.cn/zh-cn/) |

## 🌐 OpenRouter Dynamic Free Models

*OpenRouter dynamically updates its free model catalogue. Current free text-models (26 models detected on 2026-06-17 23:55:59):*

| Model ID | Context Window | Description |
| :--- | :--- | :--- |
| `cognitivecomputations/dolphin-mistral-24b-venice-edition:free` | 32K | Venice Uncensored Dolphin Mistral 24B Venice Edition is a fine-tuned variant of Mistral-Small-24B-In... |
| `google/gemma-4-26b-a4b-it:free` | 262K | Gemma 4 26B A4B IT is an instruction-tuned Mixture-of-Experts (MoE) model from Google DeepMind. Desp... |
| `google/gemma-4-31b-it:free` | 262K | Gemma 4 31B Instruct is Google DeepMind's 30.7B dense multimodal model supporting text and image inp... |
| `google/lyria-3-clip-preview` | 1048K | 30 second duration clips are priced at $0.04 per clip. Lyria 3 is Google's family of music generatio... |
| `google/lyria-3-pro-preview` | 1048K | Full-length songs are priced at $0.08 per song. Lyria 3 is Google's family of music generation model... |
| `liquid/lfm-2.5-1.2b-instruct:free` | 32K | LFM2.5-1.2B-Instruct is a compact, high-performance instruction-tuned model built for fast on-device... |
| `liquid/lfm-2.5-1.2b-thinking:free` | 32K | LFM2.5-1.2B-Thinking is a lightweight reasoning-focused model optimized for agentic tasks, data extr... |
| `meta-llama/llama-3.2-3b-instruct:free` | 131K | Llama 3.2 3B is a 3-billion-parameter multilingual large language model, optimized for advanced natu... |
| `meta-llama/llama-3.3-70b-instruct:free` | 131K | The Meta Llama 3.3 multilingual large language model (LLM) is a pretrained and instruction tuned gen... |
| `nex-agi/nex-n2-pro:free` | 262K | Nex-N2-Pro is an agentic mixture-of-experts model from Nex AGI, with 17B active parameters out of 39... |
| `nousresearch/hermes-3-llama-3.1-405b:free` | 131K | Hermes 3 is a generalist language model with many improvements over Hermes 2, including advanced age... |
| `nvidia/nemotron-3-nano-30b-a3b:free` | 256K | NVIDIA Nemotron 3 Nano 30B A3B is a small language MoE model with highest compute efficiency and acc... |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | 256K | NVIDIA Nemotron™ 3 Nano Omni is a 30B-A3B open multimodal model designed to function as a perception... |
| `nvidia/nemotron-3-super-120b-a12b:free` | 1000K | NVIDIA Nemotron 3 Super is a 120B-parameter open hybrid MoE model, activating just 12B parameters fo... |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | 1000K | NVIDIA Nemotron 3 Ultra is an open frontier-reasoning and orchestration model from NVIDIA, with 55B ... |
| `nvidia/nemotron-3.5-content-safety:free` | 128K | NVIDIA Nemotron 3.5 Content Safety is a compact 4B-parameter multimodal guardrail model from NVIDIA,... |
| `nvidia/nemotron-nano-12b-v2-vl:free` | 128K | NVIDIA Nemotron Nano 2 VL is a 12-billion-parameter open multimodal reasoning model designed for vid... |
| `nvidia/nemotron-nano-9b-v2:free` | 128K | NVIDIA-Nemotron-Nano-9B-v2 is a large language model (LLM) trained from scratch by NVIDIA, and desig... |
| `openai/gpt-oss-120b:free` | 131K | gpt-oss-120b is an open-weight, 117B-parameter Mixture-of-Experts (MoE) language model from OpenAI d... |
| `openai/gpt-oss-20b:free` | 131K | gpt-oss-20b is an open-weight 21B parameter model released by OpenAI under the Apache 2.0 license. I... |
| `openrouter/free` | 200K | The simplest way to get free inference. openrouter/free is a router that selects free models at rand... |
| `openrouter/owl-alpha` | 1048K | Owl Alpha is a high-performance foundation model designed for agentic workloads. Natively supports t... |
| `poolside/laguna-m.1:free` | 262K | Laguna M.1 is the flagship coding agent model from [Poolside](https://poolside.ai), optimized for co... |
| `poolside/laguna-xs.2:free` | 262K | Laguna XS.2 is the second-generation model in the XS size class from [Poolside](https://poolside.ai/... |
| `qwen/qwen3-coder:free` | 1048K | Qwen3-Coder-480B-A35B-Instruct is a Mixture-of-Experts (MoE) code generation model developed by the ... |
| `qwen/qwen3-next-80b-a3b-instruct:free` | 262K | Qwen3-Next-80B-A3B-Instruct is an instruction-tuned chat model in the Qwen3-Next series optimized fo... |

## Detailed Provider Profiles

### 🇨🇳 BigModel (Zhipu AI)
- **URL**: https://open.bigmodel.cn/
- **OpenAI Base URL**: `https://open.bigmodel.cn/api/paas/v4`
- **Quota Limits**: GLM-4-Flash and GLM-4.6V-Flash are permanently free with credit card-free signup
- **Supported Models**:
  - `glm-4-flash`
  - `glm-4v-flash`

### 🇺🇸 Cerebras
- **URL**: https://cloud.cerebras.ai/
- **OpenAI Base URL**: `https://api.cerebras.ai/v1`
- **Quota Limits**: Free tier, no credit card. Ultra-fast inference (~2,600 tok/s). 1M tokens/day cap. 8K context cap on free tier.
- **Supported Models**:
  - `llama3.1-8b`
  - `llama3.1-70b`

### 🇨🇦 Cohere
- **URL**: https://dashboard.cohere.com/api-keys
- **OpenAI Base URL**: `https://api.cohere.com/v2`
- **Quota Limits**: 20 requests/minute 1,000 requests/month
- **Supported Models**:
  - `command-r`
  - `command-r-plus`
  - `command-r7b`

### 🇺🇸 Fireworks AI
- **URL**: https://fireworks.ai/
- **OpenAI Base URL**: `https://api.fireworks.ai/inference/v1`
- **Quota Limits**: $1 in free trial credits on signup
- **Supported Models**:
  - `accounts/fireworks/models/llama-v3p1-405b-instruct`

### 🇺🇸 Google AI Studio
- **URL**: https://aistudio.google.com/app/apikey
- **Quota Limits**: Gemini 1.5 Flash: 15 RPM, 1500 RPD
Gemini 1.5 Pro: 5 RPM, 50 RPD
Gemini 2.5 Flash: 15 RPM, 1500 RPD
- **Supported Models**:
  - `gemini-1.5-flash`
  - `gemini-1.5-pro`
  - `gemini-2.5-flash`
  - `gemini-2.5-pro`

### 🇺🇸 Groq
- **URL**: https://console.groq.com/keys
- **OpenAI Base URL**: `https://api.groq.com/openai/v1`
- **Quota Limits**: Free tier, no credit card. Ultra-fast LPU inference. [^2]
- **Supported Models**:
  - `llama-3.3-70b-versatile`
  - `llama-3.1-8b-instant`
  - `mixtral-8x7b-32768`
  - `gemma2-9b-it`

### 🇫🇷 Mistral AI
- **URL**: https://console.mistral.ai/api-keys
- **OpenAI Base URL**: `https://api.mistral.ai/v1`
- **Quota Limits**: Free "Experiment" plan, no credit card. ~1B tokens/month. Prompts may be used to improve models.
- **Supported Models**:
  - `mistral-large-latest`
  - `mistral-small-latest`
  - `codestral-latest`

### 🇺🇸 NVIDIA NIM
- **URL**: https://build.nvidia.com/
- **OpenAI Base URL**: `https://integrate.api.nvidia.com/v1`
- **Quota Limits**: 40 requests/minute
- **Supported Models**:
  - `meta/llama-3.1-405b-instruct`
  - `nvidia/llama-3.1-nemotron-70b-instruct`

### 🇺🇸 Novita AI
- **URL**: https://novita.ai/
- **OpenAI Base URL**: `https://api.novita.ai/v1`
- **Quota Limits**: $0.50 in free credits, occasionally runs free models
- **Supported Models**:
  - `meta-llama/llama-3.1-8b-instruct`
  - `meta-llama/llama-3.1-70b-instruct`

### 🌐 OpenRouter
- **URL**: https://openrouter.ai/keys
- **OpenAI Base URL**: `https://openrouter.ai/api/v1`
- **Quota Limits**: 20 RPM, 50 RPD free models (up to 1,000 RPD with $10 lifetime top-up)
- **Supported Models**:
  - `nex-agi/nex-n2-pro:free`
  - `nvidia/nemotron-3.5-content-safety:free`
  - `nvidia/nemotron-3-ultra-550b-a55b:free`
  - `openrouter/owl-alpha`
  - `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free`
  - `poolside/laguna-xs.2:free`
  - `poolside/laguna-m.1:free`
  - `google/gemma-4-26b-a4b-it:free`
  - `google/gemma-4-31b-it:free`
  - `google/lyria-3-pro-preview`
  - `google/lyria-3-clip-preview`
  - `nvidia/nemotron-3-super-120b-a12b:free`
  - `openrouter/free`
  - `liquid/lfm-2.5-1.2b-thinking:free`
  - `liquid/lfm-2.5-1.2b-instruct:free`

### 🇺🇸 SambaNova
- **URL**: https://cloud.sambanova.ai/
- **OpenAI Base URL**: `https://api.sambanova.ai/v1`
- **Quota Limits**: Free tier, no credit card. Ultra-fast RDU inference. 20 RPM, 200K tokens/day. [^8]
- **Supported Models**:
  - `Llama-3.1-8B-Instruct`
  - `Llama-3.1-70B-Instruct`
  - `Llama-3.1-405B-Instruct`

### 🇨🇳 SiliconFlow
- **URL**: https://siliconflow.cn/zh-cn/
- **OpenAI Base URL**: `https://api.siliconflow.cn/v1`
- **Quota Limits**: Permanently free models, no credit card required. 200+ paid models also available.
- **Supported Models**:
  - `deepseek-ai/DeepSeek-V3`
  - `deepseek-ai/DeepSeek-R1-Distill-Qwen-7B`
  - `Qwen/Qwen2.5-Coder-7B-Instruct`

## 🤝 Contribution Guidelines & Automation

This repository is maintained automatically by Hermes agents. Daily jobs scan upstream sources and GitHub Issues.

- **Reporting changes**: If a free tier has changed or a provider has sunsetted credits, please **open an issue** with the specific provider name and details. The bot will automatically verify the claim via web search and update the catalog within 24 hours.

- **Submitting updates**: PRs updating `free-llm-providers.json` or scripts are welcome. Please don't edit `README.md` directly since it's dynamically generated.

---
*Last updated: 2026-06-17 23:55:59 (IST) | Build ID: 20260617235559*