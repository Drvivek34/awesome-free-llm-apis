# API-Pulse: 免费 LLM、搜索和 AI 工具 API 终极指南 ⚡

*精选并自动更新的大语言模型（LLM）API、搜索 API、语音转录和开发者命令行工具的永久免费层或测试额度目录。由 Hermes 机器人每日更新。*

🌐 **[English](README.md)** · **[简体中文](README.zh-CN.md)**

## 📌 LLM 推理与 API 提供商

| 提供商 | 类型 | 地区 | 兼容 OpenAI SDK? | 免费额度 / 速率限制 / 规则条件 | 关键模型 / 核心功能 | API 密钥 / 推荐链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇮🇱 **AI21** | 第一方厂商 | 🇮🇱 | ✅ 兼容 | Offers a free trial of $10 in credits valid for three months upon account creation. No permanent free tier. Once credits are exhausted or expired, users must transition to a paid plan. Commercial API access is usage-based (pay-as-you-go). Model usage via third-party cloud providers (AWS Bedrock, Azure) is governed by their respective rates. | `Jamba 1.5 Large`, `Jamba 1.5 Mini`, `Jamba 1.6` | [官网链接](https://www.ai21.com/) |
| 🇮🇱 **AionLabs** | 第一方厂商 | 🇮🇱 | ✅ 兼容 | Offers a free tier with a recurring daily credit allowance (approx. 20,000 tokens per day) for testing agent jobs, APIs, and browser chat with no credit card required. Paid options include Prepaid (pay-as-you-go) and monthly Business plans. API is OpenAI-compatible and can also be accessed via Puter.js. | `Aion-2.0`, `Aion-1.0`, `Aion-1.0-Mini` | [官网链接](https://www.aionlabs.ai/) |
| 🌐 **AkashML** | 第三方推理平台 | 🌐 | ✅ 兼容 | New users of the AkashML managed inference service receive $100 in free AI token credits for both playground and API usage. Additionally, the Akash Console for self-hosted container deployments offers a $100 free trial (requires credit card for verification, 24h limit per instance). Paid options are pay-per-use, operating as a decentralized marketplace with reverse auctions resulting in 60-85% savings compared to standard cloud providers. | `Llama 3.3 70B`, `DeepSeek V4 Flash`, `DeepSeek V3.2` (+1 更多) | [官网链接](https://akash.network/) |
| 🇨🇳 **Alibaba Cloud Int.** | 云服务商 | 🇨🇳 | ✅ 兼容 | Provides DashScope / Model Studio developer APIs and AI Coding Plans. New users receive a free token quota valid for 90 days (Singapore region only, sk- keys). Standard DashScope API is pay-as-you-go based on token usage. The AI Coding Plan is a fixed-price monthly subscription (Lite/Pro, sk-sp- keys) providing flat-rate prompt limits instead of token billing. | `Qwen3.7-Max`, `Qwen3.7-Plus`, `Qwen3.6-Plus` (+3 更多) | [官网链接](https://www.alibabacloud.com/) |
| 🇺🇸 **Amazon Bedrock** | 云服务商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | No permanent free tier. New AWS accounts receive up to $200 in promotional credits ($100 at signup, $100 via guided tasks) valid for 6 months. Startup programs offer $1,000 to $300,000+ in credits. Paid options: On-Demand pay-as-you-go per 1M tokens, Batch Inference (approx. 50% discount), and Provisioned Throughput (dedicated capacity billing). | `Anthropic Claude 3.5 Sonnet`, `Meta Llama 3.3`, `Amazon Titan` | [官网链接](https://aws.amazon.com/bedrock/) |
| 🇺🇸 **Anthropic** | 第一方厂商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Claude.ai interactive chat offers a permanent free tier with usage limits capped on a rolling 5-hour window. The developer API has no permanent free tier but provides a small one-time starter credit upon account creation. Paid options include Claude.ai Pro ($20/month) and consumption-based developer API billing. The CLAUDE_CODE_OAUTH_TOKEN environment variable can be used to authenticate coding tasks via Anthropic's OAuth device flow. | `Claude 4.6 Sonnet`, `Claude 4.7 Opus`, `Claude 4.5 Haiku` | [官网链接](https://console.anthropic.com/) |
| 🇺🇸 **Arcee AI** | 第一方厂商 | 🇺🇸 | ✅ 兼容 | Does not offer a traditional permanent free tier for its commercial API. However, the Trinity Builders Program offers free inference access for approved developer, research, and open-source projects. Otherwise, commercial API is pay-as-you-go (e.g., Trinity-Mini at ~$0.045/1M input tokens and ~$0.15/1M output tokens). Models are open-weight and can be downloaded for free local deployment. | `Trinity-Large-Thinking`, `Trinity-Large-Preview`, `Trinity-Mini` (+1 更多) | [官网链接](https://www.arcee.ai/) |
| 🇺🇸 **AtlasCloud** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Provides a unified API to access over 300 models on a pay-as-you-go consumption model (e.g., DeepSeek V3 at $0.07/1M tokens). GPU Cloud instances start around $2.95/hr with per-second billing. Standard developer subscriptions are currently noted as unavailable, and evaluation credits/promotions vary dynamically within the console. | `DeepSeek V3`, `Kling`, `Seedance` (+1 更多) | [官网链接](https://atlascloud.io/) |
| 🇺🇸 **Azure** | 云服务商 | 🇺🇸 | ✅ 兼容 | Offers $200 free credits for the first 30 days, 12 months of popular free services, and 65+ always-free services (subject to monthly limits) for new accounts. Unused credits expire and require manual upgrade to Pay-As-You-Go. Azure for Students offers $100 credits without credit card verification. | `GPT-5.5 (Azure OpenAI)`, `GPT-5.4 (Azure OpenAI)`, `Llama (Foundry)` (+2 更多) | [官网链接](https://azure.microsoft.com/) |
| 🇨🇳 **Baidu Qianfan** | 第一方厂商 | 🇨🇳 | ✅ 兼容 | Offers permanently free access to select lightweight models like ERNIE-3.5-8K and ERNIE-Speed-8K. Premium models like ERNIE-4.0-8K include introductory trial quotas (e.g., 1M free tokens in the first month). Paid options include pay-per-token consumption for proprietary ERNIE models and third-party models, as well as a paid 'Coding Plan' subscription for developer tools. | `ERNIE 5.1`, `ERNIE-4.0-8K`, `ERNIE-3.5-8K` (+1 更多) | [官网链接](https://cloud.baidu.com/product/wenxin.html) |
| 🇺🇸 **Baseten** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No permanent free tier. New workspaces receive $30 in free trial credits. Startup programs offer up to $25,000 for dedicated deployments and $2,500 for model APIs. Paid options are usage-based on a per-replica-hour or per-token basis with scale-to-zero capabilities to eliminate idle costs. | `Meta Llama 3`, `Mistral`, `Whisper` (+1 更多) | [官网链接](https://www.baseten.co/) |
| 🇺🇸 **Cerebras** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Generous free tier offering 1,000,000 free tokens per day (no credit card required). Paid options: Developer Tier (pre-paid starting at $10) with 10x higher rate limits and priority processing; Enterprise Tier with custom pricing for dedicated hosting and support. | `Llama 3.3`, `Llama 3.1 70B`, `Llama 4 Scout` (+1 更多) | [官网链接](https://cloud.cerebras.ai/) |
| 🇺🇸 **Chutes** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No longer offers a free tier as of March 15, 2026. Operates under a pay-as-you-go (PAYGO) model for token inference and hourly private GPU deployments. Optional paid monthly subscription plans, Plus ($10/month) and Pro ($20/month), provide daily request quotas and a 6-10% discount on excess PAYGO usage. Startup credits (up to $10,000) are available for qualifying companies. | `DeepSeek-R1`, `DeepSeek-V3.2-TEE`, `Mistral-Nemo-Instruct-2407` (+2 更多) | [官网链接](https://chutes.ai/) |
| 🇺🇸 **Clarifai** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Has transitioned from tier-based subscriptions to a credits-based Pay-As-You-Go model. New users can receive a one-time $5 welcome bonus (valid for 30 days) upon phone verification to test serverless API calls and custom deployments. Paid access requires purchasing additional credits to top up the account balance. | `general-image-recognition`, `DeepSeek-V3_2`, `Llama-3_2-3B-Instruct` (+1 更多) | [官网链接](https://www.clarifai.com/) |
| 🇺🇸 **Cloudflare** | 云服务商 | 🇺🇸 | ✅ 兼容 | Free tier provides a daily allocation of 10,000 Neurons across all accounts. Paid options: Workers Paid plan starts at $5/month, and usage beyond the daily free allocation is billed at $0.011 per 1,000 Neurons. | `llama-3.1-8b-instruct`, `mistral-7b-instruct-v0.2`, `stable-diffusion-xl-base-1.0` | [官网链接](https://dash.cloudflare.com/) |
| 🇨🇦 **Cohere** | 第一方厂商 | 🇨🇦 | ✅ 兼容 | Offers a free Evaluation (Trial) tier for developers with a rate-limited trial API key (1,000 API calls/month, 20 requests/minute). Paid options include the Production Tier with pay-as-you-go billing based on token usage (e.g., 500 RPM limit) and Enterprise agreements for dedicated hosting or custom SLA needs. | `Command A+`, `Command R`, `Command R7B` (+3 更多) | [官网链接](https://dashboard.cohere.com/api-keys) |
| 🇮🇱 **Decart** | 第一方厂商 | 🇮🇱 | ✅ 兼容 | Operates on a pay-as-you-go model with no monthly subscription fees. New accounts receive free trial credits to test the API and models. Paid options are charged based on execution metrics: realtime models are billed per second of active generation (e.g., Lucy 2.1 at ~$0.02/sec), video models per second generated, and image models per generation. | `Lucy 2.1`, `Lucy Image 2`, `Oasis 3` | [官网链接](https://www.decart.ai/) |
| 🇺🇸 **DeepInfra** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Does not offer a formal subscription-based free tier. However, users can perform unauthenticated testing of models with an empty api_key (rate-limited by IP address). Signing up can sometimes grant temporary token allotments. Paid options are strictly pay-as-you-go based on token usage (e.g., starting at ~$0.02/1M tokens) or execution time for non-LLMs. Cached tokens are discounted (e.g., ~$0.145/1M tokens). | `Llama 3.3`, `DeepSeek-V4-Pro`, `gemini-3.5-flash` (+2 更多) | [推荐注册链接]() / [官网普通链接](https://deepinfra.com/) |
| 🇨🇳 **DeepSeek** | 第一方厂商 | 🇨🇳 | ✅ 兼容 | The web chat interface (chat.deepseek.com) is permanently free. The API does not have an ongoing free tier but offers 5 million free trial tokens for new developer accounts. Paid options follow a pay-as-you-go model: DeepSeek V4-Flash is priced at $0.14/1M input and $0.28/1M output tokens, and DeepSeek V4-Pro is priced at $0.435/1M input and $0.87/1M output tokens. Significant discounts are offered for cache hits. | `DeepSeek V4-Flash`, `DeepSeek V4-Pro` | [官网链接](https://platform.deepseek.com/) |
| 🇺🇸 **Fireworks** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No permanent free tier. Offers $1 in free starter credits for new signups. Paid options: Serverless pay-per-token pricing based on model size (sub-4B: $0.10/1M tokens, 4B-16B: $0.20/1M tokens, 16B+: $0.90/1M tokens). Offers 50% discount for cached input tokens and batch inference. | `Llama 3.3`, `Qwen 2.5`, `DeepSeek-V3` (+1 更多) | [官网链接](https://fireworks.ai/) |
| 🇰🇷 **Friendli** | 第三方推理平台 | 🇰🇷 | ✅ 兼容 | No permanent free plan. Offers substantial startup/promotional GPU inference credits ranging from $10,000 up to $50,000 to help teams scale. Otherwise uses usage-based pay-as-you-go pricing optimized for high-throughput production workloads. | `Llama 3.1`, `Gemma 2`, `Mistral` (+1 更多) | [官网链接](https://friendli.ai/) |
| 🇺🇸 **GMI Cloud** | 云服务商 | 🇺🇸 | ✅ 兼容 | High-performance GPU cloud. No public permanent free tier. Offers free access to specific model endpoints (e.g. Llama 3.3, DeepSeek R1) for inference on the Model Hub dashboard. Paid options use a pay-as-you-go model with transparent pricing based on GPU hardware (e.g. NVIDIA H100, B200) and service type. | `DeepSeek`, `Llama`, `Qwen` (+1 更多) | [官网链接](https://gmicloud.com/) |
| 🇺🇸 **Google AI Studio** | 第一方厂商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Free tier available for the Gemini Developer API on non-billing-enabled projects, subject to RPM, TPM, and RPD rate limits (data may be used for model training). Access to Pro models on the free tier was restricted starting April 1, 2026. Enabling billing removes the free tier and transitions the project to pay-as-you-go pricing (prepaid billing for new users, with mandatory spend caps and context caching discounts). | `Gemini 1.5 Flash`, `Gemini 1.5 Pro`, `Gemini 2.5` (+1 更多) | [官网链接](https://aistudio.google.com/app/apikey) |
| 🇺🇸 **Google Vertex** | 云服务商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | No permanent free tier. New Google Cloud accounts receive $300 in free credits valid for 90 days. Vertex AI Express Mode offers limited free access hours or agent engines in a 90-day window. Paid options are pay-as-you-go. (Google AI Studio provides a separate, rate-limited free tier for developer prototyping). | `Gemini 1.5 Pro`, `Gemini 1.5 Flash`, `Imagen 3` (+1 更多) | [官网链接](https://cloud.google.com/vertex-ai) |
| 🇺🇸 **Groq** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Offers an always-free API tier (no credit card required) subject to organization-level rate limits (e.g., 30 RPM, 30,000 TPM, 14,400 RPD). Paid Developer Tier (pay-as-you-go) provides up to 10x higher rate limits, with input costs starting at $0.05/1M tokens (Llama 3.1 8B) up to $0.59 input / $0.79 output per 1M tokens (Llama 3.3 70B), plus a 50% discount for Batch API and prompt caching. | `Llama 3.1 8B`, `Llama 3.3 70B`, `Mixtral` (+2 更多) | [官网链接](https://console.groq.com/keys) |
| 🇦🇪 **Inception** | 第一方厂商 | 🇦🇪 | ✅ 兼容 | Provides 10 million free tokens upon account creation to test and prototype. OpenAI-compatible API operates on usage-based pricing with customizable user-defined billing limits and email alerts to block overages. | `Mercury 2`, `Mercury Edit 2`, `JAIS` | [官网链接](https://www.g42.ai/) |
| 🇺🇸 **Inceptron** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No direct free tier. Operates strictly on consumption-based pricing designed for EU data sovereignty. Access is typically provided through third-party gateways (e.g., Kilo.ai or Requesty) using per-million-token pay-as-you-go billing (e.g., $0.15/1M input tokens for MiniMax M2.5). Custom pricing is available for startups and enterprises. | `MiniMax M2.5`, `Kimi K2.6`, `GLM 5.1` | [官网链接](https://inceptron.com/) |
| 🇺🇸 **Infermatic** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Structured around flat-rate subscription tiers rather than token-based billing. Includes a Free Plan ($0/mo for select models like Rocinante-12B), Essential Tier ($9/mo), Standard Tier ($16/mo), and Plus Tier ($20/mo for unrestricted prompts/results, zero-logs policy, and advanced models). | `Rocinante-12B-v1.1`, `Fallen Llama 3.3`, `Strawberrylemonade L3` (+2 更多) | [官网链接](https://infermatic.ai/) |
| 🇺🇸 **Inflection** | 第一方厂商 | 🇺🇸 | ✅ 兼容 | The Pi consumer personal assistant app is completely free with no usage limits or premium tiers. The developer API operates on usage-based pricing (e.g., Inflection-3 billed at approx. $2.50 per million input tokens and $10.00 per million output tokens) with custom enterprise options. | `Inflection-3`, `Inflection-2.5`, `Pi` | [官网链接](https://inflection.ai/) |
| 💻 **Kilocode** | 第三方推理平台 | 💻 | ✅ 兼容 | AI-native gateway and assistant platform. Auto Free Tier routes to free models (e.g., Llama 3.1 8B, Qwen 2.5 7B) through Kilo Gateway. Supports Bring Your Own Key (BYOK) to route to user's OpenAI, Anthropic, or Gemini keys for free or paid usage. Paid Kilo Pass subscriptions start at $19/month (Starter) to $199/month (Expert) for hosted model credits. | `kilo-free`, `Llama series`, `Qwen series` | [官网链接](https://kilo.ai/) |
| 🇺🇸 **Liquid** | 第一方厂商 | 🇺🇸 | ✅ 兼容 | Free self-service open access to download, customize, and deploy models (via Hugging Face or LEAP platform) under the LFM Open License v1.0, which has a commercial use threshold: free for companies under $10 million in annual revenue; companies above this must purchase a commercial license. Liquid Apollo is also free for mobile devices. Enterprise tiers offer custom agreements. | `LFM-1B`, `LFM-3B`, `LFM-40B` (+1 更多) | [官网链接](https://www.liquid.ai/) |
| 🌐 **Mancer** | 第三方推理平台 | 🌐 | ✅ 兼容 | No monthly subscription free tier. Provides access to select 'free models' for initial testing. Otherwise uses a pay-as-you-go system with credit packs ranging from $4.99 (~1.25M credits) to $249.99 (~100M credits). No subscription lock-in. A 25% token discount is available if users opt into Anonymous Logging (data sharing for training). | `Weaver (alpha)`, `Magnum v4 72B`, `ReMM SLERP 13B` (+1 更多) | [推荐注册链接]() / [官网普通链接](https://mancer.tech/) |
| 🇨🇳 **MiniMax** | 第一方厂商 | 🇨🇳 | ✅ 兼容 | No permanent free tier. Provides limited trial credits to new developer accounts for testing. Paid options: Token Plan (monthly subscription starting at $10/month) or Pay-as-you-go (token packages starting at $5 for 5,000 credits). Standard rates for flagship models are typically around $0.30-$0.50/1M input tokens and $1.00-$1.20/1M output tokens. | `MiniMax-M3`, `MiniMax-M2.7`, `MiniMax-M2.5` (+1 更多) | [官网链接](https://platform.minimaxi.com/) |
| 🇫🇷 **Mistral** | 第一方厂商 | 🇫🇷 | ✅ 兼容 | API (La Plateforme) offers a permanent Free Tier for evaluation and prototyping, subject to strict rate limits (e.g., 1 request/second global limit). Paid options: Scale plan (pay-as-you-go). Startup programs provide up to $30,000 in credits. Le Chat consumer chat service offers a free plan capped at ~25 messages/day and a Pro plan at $14.99/month. | `Mistral Medium 3.5`, `Mistral Small 4`, `Mistral Large 3` (+1 更多) | [官网链接](https://console.mistral.ai/api-keys) |
| 🇨🇳 **Moonshot AI** | 第一方厂商 | 🇨🇳 | ✅ 兼容 | Kimi chat interface is free for casual users with query volume and context limits. Pro features (Agent Swarm, Deep Research) are available via monthly subscriptions: Moderato (~$19/mo), Allegretto, and Vivace (up to $199/mo). Developer API is pay-as-you-go ($0.55-$0.95 per million input, $2.50-$4.00 per million output tokens) with automatic context caching. Open-weight versions of Kimi K2 models are free to self-host. | `Kimi K2.6`, `Kimi K2.7`, `Moonshot-v1` | [官网链接](https://platform.moonshot.cn/) |
| 🇺🇸 **Morph** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Includes Morph LLM (developer assistant) which offers a free tier of 200 requests/month, and Morph Studio (video/image generation) which offers a free plan of 75 credits/month. Paid options: Morph LLM features Starter, Pro, and Scale plans with per-token billing (e.g., $0.80-$0.90/1M input tokens). Morph Studio plans start at ~$10/month (or $7/month billed annually) for 3,000 credits. | `Morph V3 Fast`, `Morph V3 Large`, `Morph-Video-1` (+1 更多) | [官网链接](https://www.morph.so/) |
| 🟢 **NVIDIA NIM** | 第三方推理平台 | 🟢 | ✅ 兼容 | Provides free developer access to hosted NIM APIs for development, prototyping, and testing (no credit card required, never expires). Subject to model-specific rate limits (approx. 40 RPM). Strictly for development and testing. Paid options require self-hosting NIM containers under an NVIDIA AI Enterprise license. | `llama-3.3-70b-instruct`, `nemotron-4-340b-instruct`, `deepseek-r1` | [官网链接](https://build.nvidia.com) |
| 🇳🇱 **Nebius Token Factory** | 第三方推理平台 | 🇳🇱 | ✅ 兼容 | No permanent free tier. Provides free promotional credits upon account sign-up ('Start Free' model) to test over 60 open-source models in the Playground or via API. Paid usage is pay-per-token for serverless access, or billed by compute hours for dedicated endpoints. | `DeepSeek-V3`, `Qwen 2.5`, `Qwen 3` (+2 更多) | [推荐注册链接]() / [官网普通链接](https://nebius.ai/) |
| 🇺🇸 **NextBit** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No public free tier. Operates on a pay-per-token serverless API platform or fixed-price dedicated instances for enterprise needs. | `Llama 3.3 70B`, `Qwen 2.5 72B`, `Llama 3.3 8B` | [官网链接](https://nextbit.ai/) |
| 🇺🇸 **NovitaAI** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No permanent free tier. New accounts receive $1 in free credits upon signup, with promotions offering up to $100 in Sandbox credits (valid for 90 days) or $10 for specific models. Startups can receive up to $10,000 in credits. Paid options: Pay-as-you-go based on token usage or hourly dedicated GPU instance hosting. | `Qwen3.7-Max`, `MiniMax-M3`, `Kimi K2.7 Code` (+1 更多) | [推荐注册链接]() / [官网普通链接](https://novita.ai/) |
| ☁️ **Ollama Cloud** | 第三方推理平台 | ☁️ | ✅ 兼容 | Hosted cloud service for Ollama models. Free tier ($0/month) provides access to a selection of cloud-enabled models, subject to base limits based on actual GPU compute/execution time rather than tokens. Paid plans: Pro ($20/month, 50x usage, 3 concurrent cloud models) and Max ($100/month, 5x Pro usage, 10 concurrent cloud models). | `Llama 3.3`, `Qwen 2.5`, `Mistral Small` | [官网链接](https://ollama.com/) |
| 🇺🇸 **OpenAI** | 第一方厂商 | 🇺🇸 | ✅ 兼容 | No permanent free API tier. New accounts receive a one-time trial credit (e.g., $5 to $18) expiring in 3 months. Users can opt into the Data Sharing Program to get a daily quota of free tokens on specific models (e.g., gpt-4o-mini, gpt-4.1-mini) in exchange for training data. General usage is pay-as-you-go per-token billing (e.g., GPT-5.5 at $5/1M input, $30/1M output; GPT-5.4-nano at $0.10-$0.20/1M input), with input caching and Batch API (50% off) discounts. | `GPT-5.5`, `GPT-5.4`, `GPT-5.4-mini` (+3 更多) | [官网链接](https://platform.openai.com/) |
| 🌐 **OpenRouter** | 第三方推理平台 | 🌐 | ✅ 兼容 | 20 RPM, 50 RPD free models (up to 1,000 RPD with $10 lifetime top-up) | `north-mini-code:free`, `nex-n2-pro:free`, `nemotron-3.5-content-safety:free` (+12 更多) | [官网链接](https://openrouter.ai/keys) |
| 🇺🇸 **Parasail** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Offers a 'Serverless - Free' tier for prototyping and testing, limited to 5 Requests Per Minute (RPM). Paid options: Pay-per-token serverless billing or hourly GPU instance billing, which typically requires a linked payment method and a $25 charging threshold. | `Qwen series`, `DeepSeek series`, `Llama series` | [官网链接](https://parasail.io/) |
| 🇺🇸 **Perplexity** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No permanent free tier. New accounts receive $25-$50 in trial credits. Perplexity Pro subscribers ($20/month) receive $5 in monthly API credits. Startup programs offer grants from $500 to $5,000+. Paid options: Pay-as-you-go token pricing. | `Sonar Small Online`, `Sonar Large Online`, `Sonar Huge Online` (+1 更多) | [推荐注册链接]() / [官网普通链接](https://www.perplexity.ai/pro) |
| 🇫🇷 **Poolside** | 第一方厂商 | 🇫🇷 | ✅ 兼容 | Enterprise-focused coding assistant and foundation models. Models are available with open weights (e.g., Laguna XS.2 is Apache-2.0 licensed). Free access to models is available via third-party integrations like OpenRouter, Puter.js, Requesty, and Krater.ai. Direct business model is custom enterprise deployment (on-premises or private VPCs), with no standard public self-serve pay-as-you-go pricing listed. | `Laguna M.1`, `Laguna XS.2` | [官网链接](https://poolside.ai/) |
| 🇺🇸 **Reka AI** | 第一方厂商 | 🇺🇸 | ✅ 兼容 | Developer API offers $10 in free credits monthly. Reka Vision API offers a free evaluation tier of 3 free hours (180 minutes) of indexed video. Paid usage is consumption-based (pay-as-you-go) per token (for text) or per-minute/request (for video/image/research tasks). | `Reka Core`, `Reka Flash`, `Reka Edge` (+1 更多) | [官网链接](https://www.reka.ai/) |
| 🇺🇸 **SambaNova** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | No perpetual free tier. Offers $5 in free API credits to new users (valid for 30 to 90 days, no credit card required) subject to Free Tier rate limits. Paid options: Developer Tier (pay-as-you-go) with higher rate limits (e.g., 20M tokens/day) once a billing method is linked. | `Meta-Llama-3.3-70B-Instruct`, `DeepSeek-V3.1`, `gemma-4-31B-it` (+1 更多) | [官网链接](https://cloud.sambanova.ai/) |
| 🇨🇳 **SiliconFlow** | 第三方推理平台 | 🇨🇳 | ✅ 兼容 | Offers a 'Get Started for Free' tier featuring select free models (e.g., Qwen2.5-7B-Instruct) subject daily rate limits (e.g., 50 requests/day). New accounts receive $1 in free trial credits. Paid options: Pay-as-you-go token pricing for Pro models. | `MiniMax-M3`, `Nex-N2-Pro`, `DeepSeek-V4-Pro` (+1 更多) | [推荐注册链接]() / [官网普通链接](https://siliconflow.cn/zh-cn/) |
| 🇨🇳 **StepFun** | 第一方厂商 | 🇨🇳 | ✅ 兼容 | Offers the Step series of multimodal models. Free tier is available under the V0 tier ($0 account balance) with rate limits of 10 RPM and 5,000,000 TPM. Certain models (like Step 3.5 Flash) are also free to use via OpenRouter. Paid tiers require topping up your account balance (starting from $15 up to $1,500+), which increases RPM, TPM, and concurrency limits. | `Step 3.5 Flash`, `Step 3.7 Flash`, `Step-1-128k` (+1 更多) | [官网链接](https://platform.stepfun.com/) |
| 🇺🇸 **Together** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Requires a minimum credit purchase of $5 to activate and maintain API access. New accounts generally receive $5 in free credits to test the API. Billed under a pay-as-you-go serverless model ranging from $0.05 to $9.00 per million tokens (e.g., Llama 3.3 70B is ~$0.88/M tokens; DeepSeek R1 is ~$3.00/$7.00 per M tokens). Offers input context caching discounts. | `DeepSeek R1`, `DeepSeek V3.1`, `Llama 3.3 (70B)` (+2 更多) | [官网链接](https://together.ai/) |
| 🌐 **Venice** | 第三方推理平台 | 🌐 | ✅ 兼容 | Freemium model. Free tier allows 10 text prompts and 15 image prompts per day without login. Paid plans: Pro ($18/mo for unlimited text, 1000 images/day, and 100 credits/mo), Pro Plus ($68/mo with 7,500 credits/mo), and Max ($200/mo with 22,500 credits/mo). API access is included in the Pro tier. | `Claude 3.5 Sonnet`, `Gemini 3 Flash Preview`, `Llama 3.1` (+2 更多) | [推荐注册链接]() / [官网普通链接](https://venice.ai/) |
| 🇨🇳 **Xiaomi** | 第一方厂商 | 🇨🇳 | ❌ 不兼容 (需使用 SDK) | No permanent free tier. Offers limited-time promotions (e.g., free access to flagship MiMo-V2.5 models or TTS model) and partner integrations (e.g., Cline, OpenCode) with models labeled 'FREE'. Paid options: Pay-as-you-go token billing (e.g., MiMo-V2.5 at ¥1.00/M tokens Cache Miss) and Token Plan subscription packages starting around ¥39/month. | `MiMo-V2.5 Pro`, `MiMo-V2-Flash`, `MiMo-V2-Omni` (+1 更多) | [官网链接](https://xiaoai.mi.com/) |
| 🇨🇳 **Z.ai** | 第一方厂商 | 🇨🇳 | ✅ 兼容 | Offers free-tier access for specific models like GLM-4-Flash and GLM-4.5-Flash. New users receive registration bonuses of free tokens (millions of tokens) valid for a limited period. Paid API usage is billed per token on a pay-as-you-go model. Offers GLM Coding subscription plans for premium/agentic models. | `GLM-5`, `GLM-5-Turbo`, `GLM-4.7` (+3 更多) | [官网链接](https://open.bigmodel.cn/) |
| 🇺🇸 **xAI** | 第一方厂商 | 🇺🇸 | ✅ 兼容 | Grok chatbot has a limited free tier (~10 messages every 2 hours) on grok.com/X app. The developer API (console.x.ai) offers $25 in promotional credits for new accounts. A data-sharing opt-in program offers up to $150/month in credits (requires minimum $5 spend to enroll). Paid API usage is consumption-based (e.g., Grok 4.3 at $1.25/M input and $2.50/M output tokens). | `Grok 4.3`, `Grok Build 0.1`, `Grok Imagine API` (+1 更多) | [官网链接](https://console.x.ai/) |

## 📌 免费搜索引擎 API

| 提供商 | 类型 | 地区 | 兼容 OpenAI SDK? | 免费额度 / 速率限制 / 规则条件 | 关键模型 / 核心功能 | API 密钥 / 推荐链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇺🇸 **Brave Search API** | 第一方厂商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Metered pricing model. Automatically provides $5 in free credits every month, covering approximately 1,000 free requests/month. The standard Search Plan is priced at $5 per 1,000 requests (includes Web, News, Images, LLM context). Answers Plan is priced at $4 per 1,000 queries plus token costs. | `Search API (No custom LLM models hosted)` | [官网链接](https://brave.com/search/api/) |
| 🔍 **Exa** | 第一方厂商 | 🔍 | ❌ 不兼容 (需使用 SDK) | AI-native web search and content extraction engine. Free tier provides 1,000 free search queries/month for developer accounts (resets monthly, no credit card required). Paid plan starts at $20/month (includes 10,000 queries, overages at $0.002/query). Enterprise plans offer custom limits and dedicated endpoints. Includes search, contents/scraping, and similarity endpoints. | `Search API`, `Extract API`, `Similarity API` | [官网链接](https://exa.ai/) |
| 🔥 **Firecrawl** | 第一方厂商 | 🔥 | ❌ 不兼容 (需使用 SDK) | Web scraping, crawling, and AI-powered extraction API. Free tier provides 500 to 1,000 credits/month (no credit card required) for evaluation. Paid plans start at $19/month (Hobby, 3,000 credits) to $599/month (Scale). Operations consume credits based on complexity (e.g. AI extract/stealth proxies cost more). Also available as a free self-hosted open-source version (Docker Compose) with custom FIRECRAWL_API_URL environment overrides. | `Scraping API`, `Crawling API`, `AI Extraction API` | [官网链接](https://www.firecrawl.dev/) |
| 🇺🇸 **Google Custom Search JSON API** | 第一方厂商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Closed to new signups. The API is in a sunset phase and will be fully discontinued on January 1, 2027. For existing customers, the free tier provides 100 queries/day. Additional queries cost $5 per 1,000 requests, up to a daily limit of 10,000 queries. | `Custom Search API (No LLM models hosted)` | [官网链接](https://developers.google.com/custom-search/v1/overview) |
| ⚡ **Parallel** | 第一方厂商 | ⚡ | ❌ 不兼容 (需使用 SDK) | AI-native search and extraction engine. Operates primarily on a pay-as-you-go consumption model with no standard monthly free tier for its hosted web APIs. Search requests are billed at ~$0.005/request and extraction at ~$0.001/request. The Parallel Search Model Context Protocol (MCP) server is free to run locally and does not require an API key. | `Search API`, `Extract API`, `Monitor API` | [官网链接](https://parallel.ai/) |
| 🔍 **SearXNG** | 第一方厂商 | 🔍 | ❌ 不兼容 (需使用 SDK) | Free, open-source metasearch engine that aggregates results from more than 70 search services. Completely free to self-host (using Docker or local installation) with zero API keys required. Integrates with agents via setting the SEARXNG_URL environment variable to point to the self-hosted instance endpoint. | `Self-Hosted Metasearch API` | [官网链接](https://github.com/searxng/searxng) |
| 🕵️ **Tavily** | 第一方厂商 | 🕵️ | ❌ 不兼容 (需使用 SDK) | AI-native search engine designed for LLMs. Free tier provides 1,000 search API queries/month (no credit card required, resets monthly). Billed by usage: Basic Search consumes 1 credit, Advanced Search consumes 2 credits, Extract consumes 1 credit/5 URLs. Paid plans: Pay-as-you-go at $0.008/credit, or monthly subscriptions starting at $15/month. | `Search API`, `Extract API`, `Crawl API` | [官网链接](https://tavily.com/) |

## 📌 语音识别与转录 API

| 提供商 | 类型 | 地区 | 兼容 OpenAI SDK? | 免费额度 / 速率限制 / 规则条件 | 关键模型 / 核心功能 | API 密钥 / 推荐链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇺🇸 **AssemblyAI API** | 第一方厂商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Free tier includes up to 185 hours of batch transcription and 333 hours of streaming transcription (no credit card required). Startup program offers up to 200,000 hours of free credits. Billed under a pay-as-you-go model for additional usage, with core transcription rates and extra add-ons (Diarization, sentiment, LeMUR LLM analysis). | `Universal-3 Pro`, `Universal-1`, `Universal-3 Pro Streaming` (+1 更多) | [官网链接](https://www.assemblyai.com/) |
| 🇺🇸 **Deepgram API** | 第一方厂商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Billed by usage (per-second billing). New users receive $200 in one-time free credits (approx. 12,000 minutes of transcription). Startup program provides up to $100,000 in credits over 12 months. Paid plans: Pay-As-You-Go, Growth (discounted rates with annual commitment), and Enterprise (custom rates/self-hosting). STT rates start at ~$0.0077/min, TTS starts at ~$0.015/1k characters, Voice Agent is ~$4.50/hour. | `Nova-3 (STT)`, `Flux (Conversational STT)`, `Aura-2 (TTS)` | [官网链接](https://deepgram.com/) |
| 🗣️ **ElevenLabs** | 第一方厂商 | 🗣️ | ❌ 不兼容 (需使用 SDK) | Premium AI speech synthesis and voice cloning. Free tier provides 10,000 characters/month (refreshes monthly) for personal use, limited to standard voices. Starter plan is $5/month ($1 first month, 30,000 characters, instant voice cloning). Paid plans range up to $330/month (Scale). Scribe STT offers a usage-based tier. | `Multilingual v2 (TTS)`, `Turbo v2.5 (TTS)`, `Scribe (STT)` (+1 更多) | [官网链接](https://elevenlabs.io/) |
| 🤖 **Mistral API (Voxtral)** | 第一方厂商 | 🤖 | ❌ 不兼容 (需使用 SDK) | Hermes audio integration using Mistral's Voxtral speech-to-text and text-to-speech engine. Billed under the standard Mistral API billing structure (La Plateforme). STT and TTS are billed based on usage (characters synthesized or minutes transcribed). | `mistral-embed`, `voxtral-stt`, `voxtral-tts` | [官网链接](https://console.mistral.ai/) |
| 🎙️ **Voice Tools (OpenAI)** | 第一方厂商 | 🎙️ | ❌ 不兼容 (需使用 SDK) | Hermes audio transcription and speech integration using OpenAI Whisper (STT) and OpenAI TTS. Billed directly via the configured OpenAI API key (pay-as-you-go). Whisper is priced at $0.006/minute of audio. OpenAI TTS is priced at $15/M characters (Standard) and $30/M characters (HD). | `whisper-1`, `tts-1`, `tts-1-hd` | [官网链接](https://platform.openai.com/) |

## 📌 命令行与 AI 开发工具

| 提供商 | 类型 | 地区 | 兼容 OpenAI SDK? | 免费额度 / 速率限制 / 规则条件 | 关键模型 / 核心功能 | API 密钥 / 推荐链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 📰 **BlogWatcher CLI** | 第一方厂商 | 📰 | ❌ 不兼容 (需使用 SDK) | Command-line tool to register, track, scan, and notify new blog and RSS feed updates on the fly. | *暂未配置 / 功能在下方列出* | [官网链接](https://github.com/) |
| 🐙 **GitHub API** | 第一方厂商 | 🐙 | ❌ 不兼容 (需使用 SDK) | GitHub API authentication token. Free accounts have standard API rate limits (60 requests/hour unauthenticated). Authenticating using a Personal Access Token (GITHUB_TOKEN) increases the rate limit to 5,000 requests/hour (up to 15,000 requests/hour for GitHub Enterprise/marketplace accounts). Used for Skills Hub publishing and repository syncing. | `GitHub REST API`, `GitHub GraphQL API` | [官网链接](https://github.com/settings/tokens) |
| ⚡ **Hermes Agent CLI** | 第一方厂商 | ⚡ | ❌ 不兼容 (需使用 SDK) | Local command-line wrapper enabling background agent task runs, persistent environments, and pairing triggers. | *暂未配置 / 功能在下方列出* | [官网链接](https://github.com/) |
| 🧠 **Honcho** | 第一方厂商 | 🧠 | ❌ 不兼容 (需使用 SDK) | AI-native persistent memory library for stateful agents (developed by Plastic Labs). Licensed under AGPL-3.0 and completely free to self-host locally or via Docker, with standard configuration overrides (HONCHO_BASE_URL). The managed cloud service (api.honcho.dev) offers a free trial of $100 in start credits to new organizations. | `Agent Memory Storage` | [官网链接](https://honcho.dev/) |
| 🦙 **Ollama** | 第一方厂商 | 🦙 | ✅ 兼容 | Fully local and permanently free. Run model architectures like Llama, Qwen, Mistral, and Gemma on local CPU/GPU. | *暂未配置 / 功能在下方列出* | [官网链接](https://ollama.com/) |
| 🤖 **Qoder** | 第一方厂商 | 🤖 | ❌ 不兼容 (需使用 SDK) | Local developer utility for AI assistance, code generation, and terminal integration. | *暂未配置 / 功能在下方列出* | [官网链接](https://qoder.io/) |
| 💬 **WaCLI** | 第一方厂商 | 💬 | ❌ 不兼容 (需使用 SDK) | WhatsApp CLI tool for sending, syncing, and alerting messages directly from the server command-line. | *暂未配置 / 功能在下方列出* | [官网链接](https://github.com/topics/whatsapp-cli) |

## 📌 基于浏览器和沙箱的工具

| 提供商 | 类型 | 地区 | 兼容 OpenAI SDK? | 免费额度 / 速率限制 / 规则条件 | 关键模型 / 核心功能 | API 密钥 / 推荐链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🤖 **Browser-use** | 第一方厂商 | 🤖 | ❌ 不兼容 (需使用 SDK) | Agent browser automation library and cloud platform. Core Python library is open-source (MIT License) and completely free to run locally (user pays for LLM tokens). Managed Browser Use Cloud offers browser hosting infrastructure; includes a free tier for individual testing and prototyping. Paid Developer/Business plans scale concurrency, proxy bandwidth, and runtime. | `Agentic Browser Navigation`, `Managed Chromium Nodes` | [官网链接](https://browser-use.com/) |
| 🌐 **Browserbase** | 第一方厂商 | 🌐 | ❌ 不兼容 (需使用 SDK) | Managed cloud browser platform for web scraping and AI agents. Free plan offers 1 hour (60 minutes) of concurrent browser session usage per month (max 15 mins/session, 1 concurrent browser, 7-day data retention). Developer plan is $20/month for 100 browser hours and 1 GB proxy bandwidth, with pay-as-you-go overage billing at $0.12/hour. | `Cloud Browser Session`, `Session Recording`, `Captcha Solver` | [官网链接](https://www.browserbase.com/) |
| 🦊 **Camofox** | 第一方厂商 | 🦊 | ❌ 不兼容 (需使用 SDK) | Open-source, headless anti-detection browser automation server designed for AI agents. Free to run and self-host locally or on own infrastructure (Docker/VPS) using the open-source Camoufox Firefox fork. Integrates with agents via local base URL overrides. Supports access security via custom CAMOFOX_API_KEY authentication tokens. | `Stealth Headless Firefox`, `Accessibility Snapshot API` | [官网链接](https://github.com/camoufox/camoufox) |
| 🔍 **ChangeDetection.io** | 第一方厂商 | 🔍 | ❌ 不兼容 (需使用 SDK) | Website monitoring and change detection service. Self-hosted version is free and open-source (MIT license). Managed Cloud SaaS subscription starts at $8.99/month for up to 5,000 URLs, including managed proxies and browser-based checks. | `Website Change Detection Engine (No LLM models hosted)` | [官网链接](https://changedetection.io/) |
| 🌐 **Novita AI Sandbox Browser** | 第一方厂商 | 🌐 | ❌ 不兼容 (需使用 SDK) | Secure runtime sandbox for multi-agent workloads. Offers $100 in free Sandbox credits to new users. Free tier limits session lengths to 1 hour, concurrency to 5, and resources to 2 vCPU + 4GB RAM. Paid tier (automatic upgrade when balance > $0) allows up to 24-hour sessions, 100 concurrent sandboxes, and up to 8 vCPU + 8GB RAM. | `DeepSeek-V4-Pro`, `Llama 3.3-70B`, `Qwen3-Max` (+2 更多) | [官网链接](https://novita.ai/products/sandbox) |

## 📌 其他免费 API 资源

| 提供商 | 类型 | 地区 | 兼容 OpenAI SDK? | 免费额度 / 速率限制 / 规则条件 | 关键模型 / 核心功能 | API 密钥 / 推荐链接 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇺🇸 **Akamai Cloud** | 云服务商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Infrastructure provider. Does not offer a permanent free tier. Provides $100 in free credits to new customers, valid for 60 days (requires payment verification). Standard flat-rate billing applies afterwards: shared instances start at $5/month, dedicated instances start at $36-$50/month. | `NVIDIA RTX PRO 6000 Blackwell Server Edition (GPU)`, `NVIDIA RTX 4000 Ada Generation (GPU)`, `NVIDIA Quadro RTX 6000 (GPU)` | [推荐注册链接]() / [官网普通链接](https://www.linode.com/) |
| 🇺🇸 **Azure Cloud** | 云服务商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Not configured yet. General Azure cloud $200 trial credits. | *暂未配置 / 功能在下方列出* | [官网链接](https://azure.microsoft.com/) |
| 🇺🇸 **DigitalOcean** | 云服务商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | Offers a Free tier with basic GPU access, 5GB storage, 12-hour auto-shutdown, and public projects. Paid options include Pro subscription ($8/month, 15GB storage, mid-range GPUs) and Growth subscription ($39/month, 50GB storage, high-end GPUs like A100/H100). Hourly compute costs apply additionally while instances are active, billed per second and stopped when powered down. | `NVIDIA H100`, `NVIDIA A100`, `RTX A6000` (+3 更多) | [推荐注册链接]() / [官网普通链接](https://www.digitalocean.com/) |
| 🎨 **Fal.ai** | 第一方厂商 | 🎨 | ❌ 不兼容 (需使用 SDK) | High-performance generative media (image/video/audio) API. No permanent free tier. New developer signups receive up to $20 in one-time free credits (especially for business domains) to test models in the Playground. Paid usage is pay-per-use (prepaid credit model, charged per generated image/video/second). Research grants program is available for open-source AI. | `FLUX.1 series`, `Stable Diffusion 3.5`, `Cosmos Video` | [官网链接](https://fal.ai/) |
| 🖌️ **Krea** | 第一方厂商 | 🖌️ | ❌ 不兼容 (需使用 SDK) | AI image and video generation platform. Web app offers a free plan with daily free credits (~50 generations/day). Developer API (via KREA_API_KEY) has no free tier and is billed independently via prepaid USD workspace balances on a per-generation cost model. | `Krea 2 Image Gen`, `Krea Video Gen` | [官网链接](https://www.krea.ai/) |
| 📊 **Langfuse** | 第一方厂商 | 📊 | ❌ 不兼容 (需使用 SDK) | Open-source LLM engineering, tracing, and observability platform. Cloud Hobby plan is permanently free, including up to 50,000 tracing units/month, 30 days data retention, and 2 users. Langfuse Cloud Pro is $199/month. Standard self-hosted version is fully open-source (MIT License) with no usage limits, though enterprise SSO/RBAC require commercial licensing. | `LLM Observability Traces`, `Prompt Management`, `Datasets & Evaluations` | [官网链接](https://langfuse.com/) |
| 🇺🇸 **OpenInference** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Offers hosted model inference. Historically provides free rate-limited access for certain models (such as Qwen, Kimi, and DeepSeek, e.g., 500 prompts per day) for academic and research purposes. Paid API access is based on token consumption (e.g., Gemma 4 31B at $0.06/M input and $0.35/M output tokens; GPT-OSS 120B at $0.03/M input and $0.15/M output tokens). | `Gemma 4 (31B)`, `gpt-oss-120b`, `gpt-oss-20b` | [官网链接](https://openinference.io/) |
| 🇺🇸 **Perceptron** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Flagship model Perceptron Mk1 can be tested for free via their demo app or integrations like Puter.js. Developers can sign up for API keys on platform.perceptron.inc. Direct API usage is billed on a pay-as-you-go token basis: $0.15 per million input tokens ($0.15/MT) and $1.50 per million output tokens ($1.50/MT). | `Perceptron Mk1` | [官网链接](https://perceptron.ai/) |
| 🌐 **Phala** | 第三方推理平台 | 🌐 | ✅ 兼容 | Decentralized confidential computing network. Agent Contracts can be deployed and hosted for free with no gas fees (dstack SDK is free). For Phala Cloud (Confidential VMs/GPU TEEs), new verified users may receive $20 in free credits, after which computing resources are billed on a pay-as-you-go basis (per-minute billing for instance types and $0.000139/GB/hour for storage). | `Llama 3.1`, `Qwen`, `DeepSeek` (+3 更多) | [官网链接](https://phala.network/) |
| 🇺🇸 **Relace** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Provides developer infrastructure for autonomous coding agents. Offers a free tier with rate limits (e.g., 3 calls per minute) for testing and small projects. Paid plans are usage-based or tiered (token-based pricing for individual models) designed to scale with team size. | `Relace Apply 3`, `Instant Apply`, `Relace Search` | [官网链接](https://relace.co/) |
| 🇺🇸 **Switchpoint** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Intelligent LLM routing service. Offers a free trial with small signup credits for new developer accounts. Paid options include a Pay-As-You-Go Developer Plan (using top-up credits based on routed models) and a flat-rate Stable Tier ($1.05/M input and $4.25/M output tokens). | `GPT-4o (Routed)`, `Claude 3.5 Sonnet (Routed)`, `Llama 3.1 (Routed)` | [官网链接](https://switchpoint.ai/) |
| 🇺🇸 **Wafer** | 第三方推理平台 | 🇺🇸 | ✅ 兼容 | Optimized AI performance engineering and inference platform. Does not offer a traditional free tier. Provides flat-rate subscription passes: Starter (~$10/week for 1,000 requests every 5 hours) and Privacy (~$25/week for 2,000 requests every 5 hours with zero data retention). Also offers pay-as-you-go serverless billing for enterprise accounts. | `Qwen 3.5 397B-A17B`, `GLM-5.1`, `Kimi-K2.6` | [官网链接](https://wafer.ai/) |
| 🇺🇸 **Weights & Biases** | 云服务商 | 🇺🇸 | ❌ 不兼容 (需使用 SDK) | W&B is an MLOps platform (not a model hosting provider). Free tier for personal or academic use offers unlimited experiments and tracked hours, and 5 GB of artifact storage. Paid options: Pro and Enterprise plans for team collaboration and commercial use. | `Integrates with Llama`, `Integrates with GPT`, `Integrates with Claude` (+1 更多) | [官网链接](https://wandb.ai/) |
| 🌐 **io.net** | 第三方推理平台 | 🌐 | ✅ 兼容 | No traditional free tier. Offers subscription plans that include monthly usage credits: Professional Plan ($15/mo in credits for light workloads, refreshes daily) and Developer Plan ($150/mo in credits with ~10% discount, refreshes every 8 hours). Beyond credits, usage is pay-as-you-go billed via $IO tokens or credit cards. | `Llama-3.3-70B-Instruct`, `Custom Docker Container Deployments` | [官网链接](https://io.net/) |

## 🌐 OpenRouter 动态免费模型

*OpenRouter 动态更新其免费模型目录。当前免费文本模型（于 2026-06-19 10:00:13 检测到 27 个模型）：*

| 模型 ID | 上下文窗口 | 描述 |
| :--- | :--- | :--- |
| `cognitivecomputations/dolphin-mistral-24b-venice-edition:free` | 32K | Venice Uncensored Dolphin Mistral 24B Venice Edition is a fine-tuned variant of Mistral-Small-24B-In... |
| `cohere/north-mini-code:free` | 256K | North Mini Code is Cohere's first agentic coding model and the debut of its North family. A sparse m... |
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
| `poolside/laguna-m.1:free` | 262K | Laguna M.1 is the flagship coding agent model from [Poolside](https://poolside.ai/), optimized for c... |
| `poolside/laguna-xs.2:free` | 262K | Laguna XS.2 is the second-generation model in the XS size class from [Poolside](https://poolside.ai/... |
| `qwen/qwen3-coder:free` | 1048K | Qwen3-Coder-480B-A35B-Instruct is a Mixture-of-Experts (MoE) code generation model developed by the ... |
| `qwen/qwen3-next-80b-a3b-instruct:free` | 262K | Qwen3-Next-80B-A3B-Instruct is an instruction-tuned chat model in the Qwen3-Next series optimized fo... |

## 详细服务商介绍与限制规则

### 🇮🇱 AI21
- **官网链接**: [点击访问](https://www.ai21.com/)
- **OpenAI 兼容 Base URL**: `https://api.ai21.com/studio/v1`
- **规则与免费条件**: Offers a free trial of $10 in credits valid for three months upon account creation. No permanent free tier. Once credits are exhausted or expired, users must transition to a paid plan. Commercial API access is usage-based (pay-as-you-go). Model usage via third-party cloud providers (AWS Bedrock, Azure) is governed by their respective rates.
- **支持的模型 / 功能特征**:
  - `Jamba 1.5 Large`
  - `Jamba 1.5 Mini`
  - `Jamba 1.6`

### 🇮🇱 AionLabs
- **官网链接**: [点击访问](https://www.aionlabs.ai/)
- **OpenAI 兼容 Base URL**: `https://api.aionlabs.ai/v1`
- **规则与免费条件**: Offers a free tier with a recurring daily credit allowance (approx. 20,000 tokens per day) for testing agent jobs, APIs, and browser chat with no credit card required. Paid options include Prepaid (pay-as-you-go) and monthly Business plans. API is OpenAI-compatible and can also be accessed via Puter.js.
- **支持的模型 / 功能特征**:
  - `Aion-2.0`
  - `Aion-1.0`
  - `Aion-1.0-Mini`

### 🇺🇸 Akamai Cloud
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://www.linode.com/)
- **规则与免费条件**: Infrastructure provider. Does not offer a permanent free tier. Provides $100 in free credits to new customers, valid for 60 days (requires payment verification). Standard flat-rate billing applies afterwards: shared instances start at $5/month, dedicated instances start at $36-$50/month.
- **支持的模型 / 功能特征**:
  - `NVIDIA RTX PRO 6000 Blackwell Server Edition (GPU)`
  - `NVIDIA RTX 4000 Ada Generation (GPU)`
  - `NVIDIA Quadro RTX 6000 (GPU)`

### 🌐 AkashML
- **官网链接**: [点击访问](https://akash.network/)
- **规则与免费条件**: New users of the AkashML managed inference service receive $100 in free AI token credits for both playground and API usage. Additionally, the Akash Console for self-hosted container deployments offers a $100 free trial (requires credit card for verification, 24h limit per instance). Paid options are pay-per-use, operating as a decentralized marketplace with reverse auctions resulting in 60-85% savings compared to standard cloud providers.
- **支持的模型 / 功能特征**:
  - `Llama 3.3 70B`
  - `DeepSeek V4 Flash`
  - `DeepSeek V3.2`
  - `Qwen 3.6 35B A3B`

### 🇨🇳 Alibaba Cloud Int.
- **官网链接**: [点击访问](https://www.alibabacloud.com/)
- **规则与免费条件**: Provides DashScope / Model Studio developer APIs and AI Coding Plans. New users receive a free token quota valid for 90 days (Singapore region only, sk- keys). Standard DashScope API is pay-as-you-go based on token usage. The AI Coding Plan is a fixed-price monthly subscription (Lite/Pro, sk-sp- keys) providing flat-rate prompt limits instead of token billing.
- **支持的模型 / 功能特征**:
  - `Qwen3.7-Max`
  - `Qwen3.7-Plus`
  - `Qwen3.6-Plus`
  - `Qwen-Max`
  - `Qwen-Turbo`
  - `Wan 2.7`

### 🇺🇸 Amazon Bedrock
- **官网链接**: [点击访问](https://aws.amazon.com/bedrock/)
- **规则与免费条件**: No permanent free tier. New AWS accounts receive up to $200 in promotional credits ($100 at signup, $100 via guided tasks) valid for 6 months. Startup programs offer $1,000 to $300,000+ in credits. Paid options: On-Demand pay-as-you-go per 1M tokens, Batch Inference (approx. 50% discount), and Provisioned Throughput (dedicated capacity billing).
- **支持的模型 / 功能特征**:
  - `Anthropic Claude 3.5 Sonnet`
  - `Meta Llama 3.3`
  - `Amazon Titan`

### 🇺🇸 Anthropic
- **官网链接**: [点击访问](https://console.anthropic.com/)
- **规则与免费条件**: Claude.ai interactive chat offers a permanent free tier with usage limits capped on a rolling 5-hour window. The developer API has no permanent free tier but provides a small one-time starter credit upon account creation. Paid options include Claude.ai Pro ($20/month) and consumption-based developer API billing. The CLAUDE_CODE_OAUTH_TOKEN environment variable can be used to authenticate coding tasks via Anthropic's OAuth device flow.
- **支持的模型 / 功能特征**:
  - `Claude 4.6 Sonnet`
  - `Claude 4.7 Opus`
  - `Claude 4.5 Haiku`

### 🇺🇸 Arcee AI
- **官网链接**: [点击访问](https://www.arcee.ai/)
- **规则与免费条件**: Does not offer a traditional permanent free tier for its commercial API. However, the Trinity Builders Program offers free inference access for approved developer, research, and open-source projects. Otherwise, commercial API is pay-as-you-go (e.g., Trinity-Mini at ~$0.045/1M input tokens and ~$0.15/1M output tokens). Models are open-weight and can be downloaded for free local deployment.
- **支持的模型 / 功能特征**:
  - `Trinity-Large-Thinking`
  - `Trinity-Large-Preview`
  - `Trinity-Mini`
  - `Trinity-Nano`

### 🇺🇸 AssemblyAI API
- **官网链接**: [点击访问](https://www.assemblyai.com/)
- **规则与免费条件**: Free tier includes up to 185 hours of batch transcription and 333 hours of streaming transcription (no credit card required). Startup program offers up to 200,000 hours of free credits. Billed under a pay-as-you-go model for additional usage, with core transcription rates and extra add-ons (Diarization, sentiment, LeMUR LLM analysis).
- **支持的模型 / 功能特征**:
  - `Universal-3 Pro`
  - `Universal-1`
  - `Universal-3 Pro Streaming`
  - `LeMUR (Framework)`

### 🇺🇸 AtlasCloud
- **官网链接**: [点击访问](https://atlascloud.io/)
- **规则与免费条件**: Provides a unified API to access over 300 models on a pay-as-you-go consumption model (e.g., DeepSeek V3 at $0.07/1M tokens). GPU Cloud instances start around $2.95/hr with per-second billing. Standard developer subscriptions are currently noted as unavailable, and evaluation credits/promotions vary dynamically within the console.
- **支持的模型 / 功能特征**:
  - `DeepSeek V3`
  - `Kling`
  - `Seedance`
  - `Flux`

### 🇺🇸 Azure
- **官网链接**: [点击访问](https://azure.microsoft.com/)
- **规则与免费条件**: Offers $200 free credits for the first 30 days, 12 months of popular free services, and 65+ always-free services (subject to monthly limits) for new accounts. Unused credits expire and require manual upgrade to Pay-As-You-Go. Azure for Students offers $100 credits without credit card verification.
- **支持的模型 / 功能特征**:
  - `GPT-5.5 (Azure OpenAI)`
  - `GPT-5.4 (Azure OpenAI)`
  - `Llama (Foundry)`
  - `Claude (Foundry)`
  - `DeepSeek (Foundry)`

### 🇺🇸 Azure Cloud
- **官网链接**: [点击访问](https://azure.microsoft.com/)
- **规则与免费条件**: Not configured yet. General Azure cloud $200 trial credits.

### 🇨🇳 Baidu Qianfan
- **官网链接**: [点击访问](https://cloud.baidu.com/product/wenxin.html)
- **规则与免费条件**: Offers permanently free access to select lightweight models like ERNIE-3.5-8K and ERNIE-Speed-8K. Premium models like ERNIE-4.0-8K include introductory trial quotas (e.g., 1M free tokens in the first month). Paid options include pay-per-token consumption for proprietary ERNIE models and third-party models, as well as a paid 'Coding Plan' subscription for developer tools.
- **支持的模型 / 功能特征**:
  - `ERNIE 5.1`
  - `ERNIE-4.0-8K`
  - `ERNIE-3.5-8K`
  - `ERNIE-Speed-8K`

### 🇺🇸 Baseten
- **官网链接**: [点击访问](https://www.baseten.co/)
- **OpenAI 兼容 Base URL**: `https://bridge.baseten.co/v1`
- **规则与免费条件**: No permanent free tier. New workspaces receive $30 in free trial credits. Startup programs offer up to $25,000 for dedicated deployments and $2,500 for model APIs. Paid options are usage-based on a per-replica-hour or per-token basis with scale-to-zero capabilities to eliminate idle costs.
- **支持的模型 / 功能特征**:
  - `Meta Llama 3`
  - `Mistral`
  - `Whisper`
  - `Stable Diffusion`

### 📰 BlogWatcher CLI
- **官网链接**: [点击访问](https://github.com/)
- **规则与免费条件**: Command-line tool to register, track, scan, and notify new blog and RSS feed updates on the fly.

### 🇺🇸 Brave Search API
- **官网链接**: [点击访问](https://brave.com/search/api/)
- **规则与免费条件**: Metered pricing model. Automatically provides $5 in free credits every month, covering approximately 1,000 free requests/month. The standard Search Plan is priced at $5 per 1,000 requests (includes Web, News, Images, LLM context). Answers Plan is priced at $4 per 1,000 queries plus token costs.
- **支持的模型 / 功能特征**:
  - `Search API (No custom LLM models hosted)`

### 🤖 Browser-use
- **官网链接**: [点击访问](https://browser-use.com/)
- **规则与免费条件**: Agent browser automation library and cloud platform. Core Python library is open-source (MIT License) and completely free to run locally (user pays for LLM tokens). Managed Browser Use Cloud offers browser hosting infrastructure; includes a free tier for individual testing and prototyping. Paid Developer/Business plans scale concurrency, proxy bandwidth, and runtime.
- **支持的模型 / 功能特征**:
  - `Agentic Browser Navigation`
  - `Managed Chromium Nodes`

### 🌐 Browserbase
- **官网链接**: [点击访问](https://www.browserbase.com/)
- **规则与免费条件**: Managed cloud browser platform for web scraping and AI agents. Free plan offers 1 hour (60 minutes) of concurrent browser session usage per month (max 15 mins/session, 1 concurrent browser, 7-day data retention). Developer plan is $20/month for 100 browser hours and 1 GB proxy bandwidth, with pay-as-you-go overage billing at $0.12/hour.
- **支持的模型 / 功能特征**:
  - `Cloud Browser Session`
  - `Session Recording`
  - `Captcha Solver`

### 🦊 Camofox
- **官网链接**: [点击访问](https://github.com/camoufox/camoufox)
- **规则与免费条件**: Open-source, headless anti-detection browser automation server designed for AI agents. Free to run and self-host locally or on own infrastructure (Docker/VPS) using the open-source Camoufox Firefox fork. Integrates with agents via local base URL overrides. Supports access security via custom CAMOFOX_API_KEY authentication tokens.
- **支持的模型 / 功能特征**:
  - `Stealth Headless Firefox`
  - `Accessibility Snapshot API`

### 🇺🇸 Cerebras
- **官网链接**: [点击访问](https://cloud.cerebras.ai/)
- **OpenAI 兼容 Base URL**: `https://api.cerebras.ai/v1`
- **规则与免费条件**: Generous free tier offering 1,000,000 free tokens per day (no credit card required). Paid options: Developer Tier (pre-paid starting at $10) with 10x higher rate limits and priority processing; Enterprise Tier with custom pricing for dedicated hosting and support.
- **支持的模型 / 功能特征**:
  - `Llama 3.3`
  - `Llama 3.1 70B`
  - `Llama 4 Scout`
  - `Qwen 2.5 72B`

### 🔍 ChangeDetection.io
- **官网链接**: [点击访问](https://changedetection.io/)
- **规则与免费条件**: Website monitoring and change detection service. Self-hosted version is free and open-source (MIT license). Managed Cloud SaaS subscription starts at $8.99/month for up to 5,000 URLs, including managed proxies and browser-based checks.
- **支持的模型 / 功能特征**:
  - `Website Change Detection Engine (No LLM models hosted)`

### 🇺🇸 Chutes
- **官网链接**: [点击访问](https://chutes.ai/)
- **规则与免费条件**: No longer offers a free tier as of March 15, 2026. Operates under a pay-as-you-go (PAYGO) model for token inference and hourly private GPU deployments. Optional paid monthly subscription plans, Plus ($10/month) and Pro ($20/month), provide daily request quotas and a 6-10% discount on excess PAYGO usage. Startup credits (up to $10,000) are available for qualifying companies.
- **支持的模型 / 功能特征**:
  - `DeepSeek-R1`
  - `DeepSeek-V3.2-TEE`
  - `Mistral-Nemo-Instruct-2407`
  - `FLUX.1 [dev]`
  - `FLUX.1-schnell`

### 🇺🇸 Clarifai
- **官网链接**: [点击访问](https://www.clarifai.com/)
- **规则与免费条件**: Has transitioned from tier-based subscriptions to a credits-based Pay-As-You-Go model. New users can receive a one-time $5 welcome bonus (valid for 30 days) upon phone verification to test serverless API calls and custom deployments. Paid access requires purchasing additional credits to top up the account balance.
- **支持的模型 / 功能特征**:
  - `general-image-recognition`
  - `DeepSeek-V3_2`
  - `Llama-3_2-3B-Instruct`
  - `gpt-oss-20b`

### 🇺🇸 Cloudflare
- **官网链接**: [点击访问](https://dash.cloudflare.com/)
- **OpenAI 兼容 Base URL**: `https://api.cloudflare.com/client/v4/accounts/{account_id}/ai/run`
- **规则与免费条件**: Free tier provides a daily allocation of 10,000 Neurons across all accounts. Paid options: Workers Paid plan starts at $5/month, and usage beyond the daily free allocation is billed at $0.011 per 1,000 Neurons.
- **支持的模型 / 功能特征**:
  - `@cf/meta/llama-3.1-8b-instruct`
  - `@cf/mistral/mistral-7b-instruct-v0.2`
  - `@cf/stabilityai/stable-diffusion-xl-base-1.0`

### 🇨🇦 Cohere
- **官网链接**: [点击访问](https://dashboard.cohere.com/api-keys)
- **OpenAI 兼容 Base URL**: `https://api.cohere.com/v2`
- **规则与免费条件**: Offers a free Evaluation (Trial) tier for developers with a rate-limited trial API key (1,000 API calls/month, 20 requests/minute). Paid options include the Production Tier with pay-as-you-go billing based on token usage (e.g., 500 RPM limit) and Enterprise agreements for dedicated hosting or custom SLA needs.
- **支持的模型 / 功能特征**:
  - `Command A+`
  - `Command R`
  - `Command R7B`
  - `Embed v4`
  - `Rerank v3.5`
  - `North Mini Code`

### 🇮🇱 Decart
- **官网链接**: [点击访问](https://www.decart.ai/)
- **规则与免费条件**: Operates on a pay-as-you-go model with no monthly subscription fees. New accounts receive free trial credits to test the API and models. Paid options are charged based on execution metrics: realtime models are billed per second of active generation (e.g., Lucy 2.1 at ~$0.02/sec), video models per second generated, and image models per generation.
- **支持的模型 / 功能特征**:
  - `Lucy 2.1`
  - `Lucy Image 2`
  - `Oasis 3`

### 🇺🇸 DeepInfra
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://deepinfra.com/)
- **OpenAI 兼容 Base URL**: `https://api.deepinfra.com/v1/openai`
- **规则与免费条件**: Does not offer a formal subscription-based free tier. However, users can perform unauthenticated testing of models with an empty api_key (rate-limited by IP address). Signing up can sometimes grant temporary token allotments. Paid options are strictly pay-as-you-go based on token usage (e.g., starting at ~$0.02/1M tokens) or execution time for non-LLMs. Cached tokens are discounted (e.g., ~$0.145/1M tokens).
- **支持的模型 / 功能特征**:
  - `Llama 3.3`
  - `DeepSeek-V4-Pro`
  - `gemini-3.5-flash`
  - `FLUX`
  - `Cosmos 3`

### 🇨🇳 DeepSeek
- **官网链接**: [点击访问](https://platform.deepseek.com/)
- **OpenAI 兼容 Base URL**: `https://api.deepseek.com`
- **规则与免费条件**: The web chat interface (chat.deepseek.com) is permanently free. The API does not have an ongoing free tier but offers 5 million free trial tokens for new developer accounts. Paid options follow a pay-as-you-go model: DeepSeek V4-Flash is priced at $0.14/1M input and $0.28/1M output tokens, and DeepSeek V4-Pro is priced at $0.435/1M input and $0.87/1M output tokens. Significant discounts are offered for cache hits.
- **支持的模型 / 功能特征**:
  - `DeepSeek V4-Flash`
  - `DeepSeek V4-Pro`

### 🇺🇸 Deepgram API
- **官网链接**: [点击访问](https://deepgram.com/)
- **规则与免费条件**: Billed by usage (per-second billing). New users receive $200 in one-time free credits (approx. 12,000 minutes of transcription). Startup program provides up to $100,000 in credits over 12 months. Paid plans: Pay-As-You-Go, Growth (discounted rates with annual commitment), and Enterprise (custom rates/self-hosting). STT rates start at ~$0.0077/min, TTS starts at ~$0.015/1k characters, Voice Agent is ~$4.50/hour.
- **支持的模型 / 功能特征**:
  - `Nova-3 (STT)`
  - `Flux (Conversational STT)`
  - `Aura-2 (TTS)`

### 🇺🇸 DigitalOcean
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://www.digitalocean.com/)
- **规则与免费条件**: Offers a Free tier with basic GPU access, 5GB storage, 12-hour auto-shutdown, and public projects. Paid options include Pro subscription ($8/month, 15GB storage, mid-range GPUs) and Growth subscription ($39/month, 50GB storage, high-end GPUs like A100/H100). Hourly compute costs apply additionally while instances are active, billed per second and stopped when powered down.
- **支持的模型 / 功能特征**:
  - `NVIDIA H100`
  - `NVIDIA A100`
  - `RTX A6000`
  - `RTX A5000`
  - `RTX A4000`
  - `Tesla V100`

### 🗣️ ElevenLabs
- **官网链接**: [点击访问](https://elevenlabs.io/)
- **规则与免费条件**: Premium AI speech synthesis and voice cloning. Free tier provides 10,000 characters/month (refreshes monthly) for personal use, limited to standard voices. Starter plan is $5/month ($1 first month, 30,000 characters, instant voice cloning). Paid plans range up to $330/month (Scale). Scribe STT offers a usage-based tier.
- **支持的模型 / 功能特征**:
  - `Multilingual v2 (TTS)`
  - `Turbo v2.5 (TTS)`
  - `Scribe (STT)`
  - `Instant Voice Cloning`

### 🔍 Exa
- **官网链接**: [点击访问](https://exa.ai/)
- **规则与免费条件**: AI-native web search and content extraction engine. Free tier provides 1,000 free search queries/month for developer accounts (resets monthly, no credit card required). Paid plan starts at $20/month (includes 10,000 queries, overages at $0.002/query). Enterprise plans offer custom limits and dedicated endpoints. Includes search, contents/scraping, and similarity endpoints.
- **支持的模型 / 功能特征**:
  - `Search API`
  - `Extract API`
  - `Similarity API`

### 🎨 Fal.ai
- **官网链接**: [点击访问](https://fal.ai/)
- **规则与免费条件**: High-performance generative media (image/video/audio) API. No permanent free tier. New developer signups receive up to $20 in one-time free credits (especially for business domains) to test models in the Playground. Paid usage is pay-per-use (prepaid credit model, charged per generated image/video/second). Research grants program is available for open-source AI.
- **支持的模型 / 功能特征**:
  - `FLUX.1 series`
  - `Stable Diffusion 3.5`
  - `Cosmos Video`

### 🔥 Firecrawl
- **官网链接**: [点击访问](https://www.firecrawl.dev/)
- **规则与免费条件**: Web scraping, crawling, and AI-powered extraction API. Free tier provides 500 to 1,000 credits/month (no credit card required) for evaluation. Paid plans start at $19/month (Hobby, 3,000 credits) to $599/month (Scale). Operations consume credits based on complexity (e.g. AI extract/stealth proxies cost more). Also available as a free self-hosted open-source version (Docker Compose) with custom FIRECRAWL_API_URL environment overrides.
- **支持的模型 / 功能特征**:
  - `Scraping API`
  - `Crawling API`
  - `AI Extraction API`

### 🇺🇸 Fireworks
- **官网链接**: [点击访问](https://fireworks.ai/)
- **OpenAI 兼容 Base URL**: `https://api.fireworks.ai/inference/v1`
- **规则与免费条件**: No permanent free tier. Offers $1 in free starter credits for new signups. Paid options: Serverless pay-per-token pricing based on model size (sub-4B: $0.10/1M tokens, 4B-16B: $0.20/1M tokens, 16B+: $0.90/1M tokens). Offers 50% discount for cached input tokens and batch inference.
- **支持的模型 / 功能特征**:
  - `Llama 3.3`
  - `Qwen 2.5`
  - `DeepSeek-V3`
  - `Stable Diffusion`

### 🇰🇷 Friendli
- **官网链接**: [点击访问](https://friendli.ai/)
- **规则与免费条件**: No permanent free plan. Offers substantial startup/promotional GPU inference credits ranging from $10,000 up to $50,000 to help teams scale. Otherwise uses usage-based pay-as-you-go pricing optimized for high-throughput production workloads.
- **支持的模型 / 功能特征**:
  - `Llama 3.1`
  - `Gemma 2`
  - `Mistral`
  - `Qwen 2`

### 🇺🇸 GMI Cloud
- **官网链接**: [点击访问](https://gmicloud.com/)
- **OpenAI 兼容 Base URL**: `https://api.gmicloud.ai/v1`
- **规则与免费条件**: High-performance GPU cloud. No public permanent free tier. Offers free access to specific model endpoints (e.g. Llama 3.3, DeepSeek R1) for inference on the Model Hub dashboard. Paid options use a pay-as-you-go model with transparent pricing based on GPU hardware (e.g. NVIDIA H100, B200) and service type.
- **支持的模型 / 功能特征**:
  - `DeepSeek`
  - `Llama`
  - `Qwen`
  - `Flux`

### 🐙 GitHub API
- **官网链接**: [点击访问](https://github.com/settings/tokens)
- **规则与免费条件**: GitHub API authentication token. Free accounts have standard API rate limits (60 requests/hour unauthenticated). Authenticating using a Personal Access Token (GITHUB_TOKEN) increases the rate limit to 5,000 requests/hour (up to 15,000 requests/hour for GitHub Enterprise/marketplace accounts). Used for Skills Hub publishing and repository syncing.
- **支持的模型 / 功能特征**:
  - `GitHub REST API`
  - `GitHub GraphQL API`

### 🇺🇸 Google AI Studio
- **官网链接**: [点击访问](https://aistudio.google.com/app/apikey)
- **规则与免费条件**: Free tier available for the Gemini Developer API on non-billing-enabled projects, subject to RPM, TPM, and RPD rate limits (data may be used for model training). Access to Pro models on the free tier was restricted starting April 1, 2026. Enabling billing removes the free tier and transitions the project to pay-as-you-go pricing (prepaid billing for new users, with mandatory spend caps and context caching discounts).
- **支持的模型 / 功能特征**:
  - `Gemini 1.5 Flash`
  - `Gemini 1.5 Pro`
  - `Gemini 2.5`
  - `Gemini 3.1`

### 🇺🇸 Google Custom Search JSON API
- **官网链接**: [点击访问](https://developers.google.com/custom-search/v1/overview)
- **规则与免费条件**: Closed to new signups. The API is in a sunset phase and will be fully discontinued on January 1, 2027. For existing customers, the free tier provides 100 queries/day. Additional queries cost $5 per 1,000 requests, up to a daily limit of 10,000 queries.
- **支持的模型 / 功能特征**:
  - `Custom Search API (No LLM models hosted)`

### 🇺🇸 Google Vertex
- **官网链接**: [点击访问](https://cloud.google.com/vertex-ai)
- **规则与免费条件**: No permanent free tier. New Google Cloud accounts receive $300 in free credits valid for 90 days. Vertex AI Express Mode offers limited free access hours or agent engines in a 90-day window. Paid options are pay-as-you-go. (Google AI Studio provides a separate, rate-limited free tier for developer prototyping).
- **支持的模型 / 功能特征**:
  - `Gemini 1.5 Pro`
  - `Gemini 1.5 Flash`
  - `Imagen 3`
  - `Claude 3.5 Sonnet`

### 🇺🇸 Groq
- **官网链接**: [点击访问](https://console.groq.com/keys)
- **OpenAI 兼容 Base URL**: `https://api.groq.com/openai/v1`
- **规则与免费条件**: Offers an always-free API tier (no credit card required) subject to organization-level rate limits (e.g., 30 RPM, 30,000 TPM, 14,400 RPD). Paid Developer Tier (pay-as-you-go) provides up to 10x higher rate limits, with input costs starting at $0.05/1M tokens (Llama 3.1 8B) up to $0.59 input / $0.79 output per 1M tokens (Llama 3.3 70B), plus a 50% discount for Batch API and prompt caching.
- **支持的模型 / 功能特征**:
  - `Llama 3.1 8B`
  - `Llama 3.3 70B`
  - `Mixtral`
  - `Qwen`
  - `DeepSeek`

### ⚡ Hermes Agent CLI
- **官网链接**: [点击访问](https://github.com/)
- **规则与免费条件**: Local command-line wrapper enabling background agent task runs, persistent environments, and pairing triggers.

### 🧠 Honcho
- **官网链接**: [点击访问](https://honcho.dev/)
- **规则与免费条件**: AI-native persistent memory library for stateful agents (developed by Plastic Labs). Licensed under AGPL-3.0 and completely free to self-host locally or via Docker, with standard configuration overrides (HONCHO_BASE_URL). The managed cloud service (api.honcho.dev) offers a free trial of $100 in start credits to new organizations.
- **支持的模型 / 功能特征**:
  - `Agent Memory Storage`

### 🇦🇪 Inception
- **官网链接**: [点击访问](https://www.g42.ai/)
- **规则与免费条件**: Provides 10 million free tokens upon account creation to test and prototype. OpenAI-compatible API operates on usage-based pricing with customizable user-defined billing limits and email alerts to block overages.
- **支持的模型 / 功能特征**:
  - `Mercury 2`
  - `Mercury Edit 2`
  - `JAIS`

### 🇺🇸 Inceptron
- **官网链接**: [点击访问](https://inceptron.com/)
- **规则与免费条件**: No direct free tier. Operates strictly on consumption-based pricing designed for EU data sovereignty. Access is typically provided through third-party gateways (e.g., Kilo.ai or Requesty) using per-million-token pay-as-you-go billing (e.g., $0.15/1M input tokens for MiniMax M2.5). Custom pricing is available for startups and enterprises.
- **支持的模型 / 功能特征**:
  - `MiniMax M2.5`
  - `Kimi K2.6`
  - `GLM 5.1`

### 🇺🇸 Infermatic
- **官网链接**: [点击访问](https://infermatic.ai/)
- **规则与免费条件**: Structured around flat-rate subscription tiers rather than token-based billing. Includes a Free Plan ($0/mo for select models like Rocinante-12B), Essential Tier ($9/mo), Standard Tier ($16/mo), and Plus Tier ($20/mo for unrestricted prompts/results, zero-logs policy, and advanced models).
- **支持的模型 / 功能特征**:
  - `Rocinante-12B-v1.1`
  - `Fallen Llama 3.3`
  - `Strawberrylemonade L3`
  - `Magnum v4`
  - `Qwen series`

### 🇺🇸 Inflection
- **官网链接**: [点击访问](https://inflection.ai/)
- **规则与免费条件**: The Pi consumer personal assistant app is completely free with no usage limits or premium tiers. The developer API operates on usage-based pricing (e.g., Inflection-3 billed at approx. $2.50 per million input tokens and $10.00 per million output tokens) with custom enterprise options.
- **支持的模型 / 功能特征**:
  - `Inflection-3`
  - `Inflection-2.5`
  - `Pi`

### 💻 Kilocode
- **官网链接**: [点击访问](https://kilo.ai/)
- **规则与免费条件**: AI-native gateway and assistant platform. Auto Free Tier routes to free models (e.g., Llama 3.1 8B, Qwen 2.5 7B) through Kilo Gateway. Supports Bring Your Own Key (BYOK) to route to user's OpenAI, Anthropic, or Gemini keys for free or paid usage. Paid Kilo Pass subscriptions start at $19/month (Starter) to $199/month (Expert) for hosted model credits.
- **支持的模型 / 功能特征**:
  - `kilo-free`
  - `Llama series`
  - `Qwen series`

### 🖌️ Krea
- **官网链接**: [点击访问](https://www.krea.ai/)
- **规则与免费条件**: AI image and video generation platform. Web app offers a free plan with daily free credits (~50 generations/day). Developer API (via KREA_API_KEY) has no free tier and is billed independently via prepaid USD workspace balances on a per-generation cost model.
- **支持的模型 / 功能特征**:
  - `Krea 2 Image Gen`
  - `Krea Video Gen`

### 📊 Langfuse
- **官网链接**: [点击访问](https://langfuse.com/)
- **规则与免费条件**: Open-source LLM engineering, tracing, and observability platform. Cloud Hobby plan is permanently free, including up to 50,000 tracing units/month, 30 days data retention, and 2 users. Langfuse Cloud Pro is $199/month. Standard self-hosted version is fully open-source (MIT License) with no usage limits, though enterprise SSO/RBAC require commercial licensing.
- **支持的模型 / 功能特征**:
  - `LLM Observability Traces`
  - `Prompt Management`
  - `Datasets & Evaluations`

### 🇺🇸 Liquid
- **官网链接**: [点击访问](https://www.liquid.ai/)
- **规则与免费条件**: Free self-service open access to download, customize, and deploy models (via Hugging Face or LEAP platform) under the LFM Open License v1.0, which has a commercial use threshold: free for companies under $10 million in annual revenue; companies above this must purchase a commercial license. Liquid Apollo is also free for mobile devices. Enterprise tiers offer custom agreements.
- **支持的模型 / 功能特征**:
  - `LFM-1B`
  - `LFM-3B`
  - `LFM-40B`
  - `LFM2/LFM2.5 series`

### 🌐 Mancer
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://mancer.tech/)
- **规则与免费条件**: No monthly subscription free tier. Provides access to select 'free models' for initial testing. Otherwise uses a pay-as-you-go system with credit packs ranging from $4.99 (~1.25M credits) to $249.99 (~100M credits). No subscription lock-in. A 25% token discount is available if users opt into Anonymous Logging (data sharing for training).
- **支持的模型 / 功能特征**:
  - `Weaver (alpha)`
  - `Magnum v4 72B`
  - `ReMM SLERP 13B`
  - `MythoMax 13B`

### 🇨🇳 MiniMax
- **官网链接**: [点击访问](https://platform.minimaxi.com/)
- **OpenAI 兼容 Base URL**: `https://api.minimax.chat/v1`
- **规则与免费条件**: No permanent free tier. Provides limited trial credits to new developer accounts for testing. Paid options: Token Plan (monthly subscription starting at $10/month) or Pay-as-you-go (token packages starting at $5 for 5,000 credits). Standard rates for flagship models are typically around $0.30-$0.50/1M input tokens and $1.00-$1.20/1M output tokens.
- **支持的模型 / 功能特征**:
  - `MiniMax-M3`
  - `MiniMax-M2.7`
  - `MiniMax-M2.5`
  - `Hailuo Video`

### 🇫🇷 Mistral
- **官网链接**: [点击访问](https://console.mistral.ai/api-keys)
- **OpenAI 兼容 Base URL**: `https://api.mistral.ai/v1`
- **规则与免费条件**: API (La Plateforme) offers a permanent Free Tier for evaluation and prototyping, subject to strict rate limits (e.g., 1 request/second global limit). Paid options: Scale plan (pay-as-you-go). Startup programs provide up to $30,000 in credits. Le Chat consumer chat service offers a free plan capped at ~25 messages/day and a Pro plan at $14.99/month.
- **支持的模型 / 功能特征**:
  - `Mistral Medium 3.5`
  - `Mistral Small 4`
  - `Mistral Large 3`
  - `Codestral`

### 🤖 Mistral API (Voxtral)
- **官网链接**: [点击访问](https://console.mistral.ai/)
- **规则与免费条件**: Hermes audio integration using Mistral's Voxtral speech-to-text and text-to-speech engine. Billed under the standard Mistral API billing structure (La Plateforme). STT and TTS are billed based on usage (characters synthesized or minutes transcribed).
- **支持的模型 / 功能特征**:
  - `mistral-embed`
  - `voxtral-stt`
  - `voxtral-tts`

### 🇨🇳 Moonshot AI
- **官网链接**: [点击访问](https://platform.moonshot.cn/)
- **规则与免费条件**: Kimi chat interface is free for casual users with query volume and context limits. Pro features (Agent Swarm, Deep Research) are available via monthly subscriptions: Moderato (~$19/mo), Allegretto, and Vivace (up to $199/mo). Developer API is pay-as-you-go ($0.55-$0.95 per million input, $2.50-$4.00 per million output tokens) with automatic context caching. Open-weight versions of Kimi K2 models are free to self-host.
- **支持的模型 / 功能特征**:
  - `Kimi K2.6`
  - `Kimi K2.7`
  - `Moonshot-v1`

### 🇺🇸 Morph
- **官网链接**: [点击访问](https://www.morph.so/)
- **规则与免费条件**: Includes Morph LLM (developer assistant) which offers a free tier of 200 requests/month, and Morph Studio (video/image generation) which offers a free plan of 75 credits/month. Paid options: Morph LLM features Starter, Pro, and Scale plans with per-token billing (e.g., $0.80-$0.90/1M input tokens). Morph Studio plans start at ~$10/month (or $7/month billed annually) for 3,000 credits.
- **支持的模型 / 功能特征**:
  - `Morph V3 Fast`
  - `Morph V3 Large`
  - `Morph-Video-1`
  - `Seedance 2.0`

### 🟢 NVIDIA NIM
- **官网链接**: [点击访问](https://build.nvidia.com)
- **OpenAI 兼容 Base URL**: `https://integrate.api.nvidia.com/v1`
- **规则与免费条件**: Provides free developer access to hosted NIM APIs for development, prototyping, and testing (no credit card required, never expires). Subject to model-specific rate limits (approx. 40 RPM). Strictly for development and testing. Paid options require self-hosting NIM containers under an NVIDIA AI Enterprise license.
- **支持的模型 / 功能特征**:
  - `meta/llama-3.3-70b-instruct`
  - `nvidia/nemotron-4-340b-instruct`
  - `deepseek-ai/deepseek-r1`

### 🇳🇱 Nebius Token Factory
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://nebius.ai/)
- **规则与免费条件**: No permanent free tier. Provides free promotional credits upon account sign-up ('Start Free' model) to test over 60 open-source models in the Playground or via API. Paid usage is pay-per-token for serverless access, or billed by compute hours for dedicated endpoints.
- **支持的模型 / 功能特征**:
  - `DeepSeek-V3`
  - `Qwen 2.5`
  - `Qwen 3`
  - `Llama`
  - `Mistral`

### 🇺🇸 NextBit
- **官网链接**: [点击访问](https://nextbit.ai/)
- **规则与免费条件**: No public free tier. Operates on a pay-per-token serverless API platform or fixed-price dedicated instances for enterprise needs.
- **支持的模型 / 功能特征**:
  - `Llama 3.3 70B`
  - `Qwen 2.5 72B`
  - `Llama 3.3 8B`

### 🌐 Novita AI Sandbox Browser
- **官网链接**: [点击访问](https://novita.ai/products/sandbox)
- **规则与免费条件**: Secure runtime sandbox for multi-agent workloads. Offers $100 in free Sandbox credits to new users. Free tier limits session lengths to 1 hour, concurrency to 5, and resources to 2 vCPU + 4GB RAM. Paid tier (automatic upgrade when balance > $0) allows up to 24-hour sessions, 100 concurrent sandboxes, and up to 8 vCPU + 8GB RAM.
- **支持的模型 / 功能特征**:
  - `DeepSeek-V4-Pro`
  - `Llama 3.3-70B`
  - `Qwen3-Max`
  - `FLUX.1 [dev]`
  - `Stable Diffusion 3`

### 🇺🇸 NovitaAI
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://novita.ai/)
- **OpenAI 兼容 Base URL**: `https://api.novita.ai/v1`
- **规则与免费条件**: No permanent free tier. New accounts receive $1 in free credits upon signup, with promotions offering up to $100 in Sandbox credits (valid for 90 days) or $10 for specific models. Startups can receive up to $10,000 in credits. Paid options: Pay-as-you-go based on token usage or hourly dedicated GPU instance hosting.
- **支持的模型 / 功能特征**:
  - `Qwen3.7-Max`
  - `MiniMax-M3`
  - `Kimi K2.7 Code`
  - `DeepSeek V4 Pro`

### 🦙 Ollama
- **官网链接**: [点击访问](https://ollama.com/)
- **OpenAI 兼容 Base URL**: `http://localhost:11434/v1`
- **规则与免费条件**: Fully local and permanently free. Run model architectures like Llama, Qwen, Mistral, and Gemma on local CPU/GPU.

### ☁️ Ollama Cloud
- **官网链接**: [点击访问](https://ollama.com/)
- **OpenAI 兼容 Base URL**: `https://api.ollama.com`
- **规则与免费条件**: Hosted cloud service for Ollama models. Free tier ($0/month) provides access to a selection of cloud-enabled models, subject to base limits based on actual GPU compute/execution time rather than tokens. Paid plans: Pro ($20/month, 50x usage, 3 concurrent cloud models) and Max ($100/month, 5x Pro usage, 10 concurrent cloud models).
- **支持的模型 / 功能特征**:
  - `Llama 3.3`
  - `Qwen 2.5`
  - `Mistral Small`

### 🇺🇸 OpenAI
- **官网链接**: [点击访问](https://platform.openai.com/)
- **OpenAI 兼容 Base URL**: `https://api.openai.com/v1`
- **规则与免费条件**: No permanent free API tier. New accounts receive a one-time trial credit (e.g., $5 to $18) expiring in 3 months. Users can opt into the Data Sharing Program to get a daily quota of free tokens on specific models (e.g., gpt-4o-mini, gpt-4.1-mini) in exchange for training data. General usage is pay-as-you-go per-token billing (e.g., GPT-5.5 at $5/1M input, $30/1M output; GPT-5.4-nano at $0.10-$0.20/1M input), with input caching and Batch API (50% off) discounts.
- **支持的模型 / 功能特征**:
  - `GPT-5.5`
  - `GPT-5.4`
  - `GPT-5.4-mini`
  - `GPT-5.4-nano`
  - `GPT-4o`
  - `GPT-4o-mini`

### 🇺🇸 OpenInference
- **官网链接**: [点击访问](https://openinference.io/)
- **规则与免费条件**: Offers hosted model inference. Historically provides free rate-limited access for certain models (such as Qwen, Kimi, and DeepSeek, e.g., 500 prompts per day) for academic and research purposes. Paid API access is based on token consumption (e.g., Gemma 4 31B at $0.06/M input and $0.35/M output tokens; GPT-OSS 120B at $0.03/M input and $0.15/M output tokens).
- **支持的模型 / 功能特征**:
  - `Gemma 4 (31B)`
  - `gpt-oss-120b`
  - `gpt-oss-20b`

### 🌐 OpenRouter
- **官网链接**: [点击访问](https://openrouter.ai/keys)
- **OpenAI 兼容 Base URL**: `https://openrouter.ai/api/v1`
- **规则与免费条件**: 20 RPM, 50 RPD free models (up to 1,000 RPD with $10 lifetime top-up)
- **支持的模型 / 功能特征**:
  - `cohere/north-mini-code:free`
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

### ⚡ Parallel
- **官网链接**: [点击访问](https://parallel.ai/)
- **规则与免费条件**: AI-native search and extraction engine. Operates primarily on a pay-as-you-go consumption model with no standard monthly free tier for its hosted web APIs. Search requests are billed at ~$0.005/request and extraction at ~$0.001/request. The Parallel Search Model Context Protocol (MCP) server is free to run locally and does not require an API key.
- **支持的模型 / 功能特征**:
  - `Search API`
  - `Extract API`
  - `Monitor API`

### 🇺🇸 Parasail
- **官网链接**: [点击访问](https://parasail.io/)
- **规则与免费条件**: Offers a 'Serverless - Free' tier for prototyping and testing, limited to 5 Requests Per Minute (RPM). Paid options: Pay-per-token serverless billing or hourly GPU instance billing, which typically requires a linked payment method and a $25 charging threshold.
- **支持的模型 / 功能特征**:
  - `Qwen series`
  - `DeepSeek series`
  - `Llama series`

### 🇺🇸 Perceptron
- **官网链接**: [点击访问](https://perceptron.ai/)
- **规则与免费条件**: Flagship model Perceptron Mk1 can be tested for free via their demo app or integrations like Puter.js. Developers can sign up for API keys on platform.perceptron.inc. Direct API usage is billed on a pay-as-you-go token basis: $0.15 per million input tokens ($0.15/MT) and $1.50 per million output tokens ($1.50/MT).
- **支持的模型 / 功能特征**:
  - `Perceptron Mk1`

### 🇺🇸 Perplexity
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://www.perplexity.ai/pro)
- **OpenAI 兼容 Base URL**: `https://api.perplexity.ai`
- **规则与免费条件**: No permanent free tier. New accounts receive $25-$50 in trial credits. Perplexity Pro subscribers ($20/month) receive $5 in monthly API credits. Startup programs offer grants from $500 to $5,000+. Paid options: Pay-as-you-go token pricing.
- **支持的模型 / 功能特征**:
  - `Sonar Small Online`
  - `Sonar Large Online`
  - `Sonar Huge Online`
  - `Sonar Pro`

### 🌐 Phala
- **官网链接**: [点击访问](https://phala.network/)
- **规则与免费条件**: Decentralized confidential computing network. Agent Contracts can be deployed and hosted for free with no gas fees (dstack SDK is free). For Phala Cloud (Confidential VMs/GPU TEEs), new verified users may receive $20 in free credits, after which computing resources are billed on a pay-as-you-go basis (per-minute billing for instance types and $0.000139/GB/hour for storage).
- **支持的模型 / 功能特征**:
  - `Llama 3.1`
  - `Qwen`
  - `DeepSeek`
  - `Gemma`
  - `Phi`
  - `LLaVA`

### 🇫🇷 Poolside
- **官网链接**: [点击访问](https://poolside.ai/)
- **规则与免费条件**: Enterprise-focused coding assistant and foundation models. Models are available with open weights (e.g., Laguna XS.2 is Apache-2.0 licensed). Free access to models is available via third-party integrations like OpenRouter, Puter.js, Requesty, and Krater.ai. Direct business model is custom enterprise deployment (on-premises or private VPCs), with no standard public self-serve pay-as-you-go pricing listed.
- **支持的模型 / 功能特征**:
  - `Laguna M.1`
  - `Laguna XS.2`

### 🤖 Qoder
- **官网链接**: [点击访问](https://qoder.io/)
- **规则与免费条件**: Local developer utility for AI assistance, code generation, and terminal integration.

### 🇺🇸 Reka AI
- **官网链接**: [点击访问](https://www.reka.ai/)
- **规则与免费条件**: Developer API offers $10 in free credits monthly. Reka Vision API offers a free evaluation tier of 3 free hours (180 minutes) of indexed video. Paid usage is consumption-based (pay-as-you-go) per token (for text) or per-minute/request (for video/image/research tasks).
- **支持的模型 / 功能特征**:
  - `Reka Core`
  - `Reka Flash`
  - `Reka Edge`
  - `Reka Spark`

### 🇺🇸 Relace
- **官网链接**: [点击访问](https://relace.co/)
- **规则与免费条件**: Provides developer infrastructure for autonomous coding agents. Offers a free tier with rate limits (e.g., 3 calls per minute) for testing and small projects. Paid plans are usage-based or tiered (token-based pricing for individual models) designed to scale with team size.
- **支持的模型 / 功能特征**:
  - `Relace Apply 3`
  - `Instant Apply`
  - `Relace Search`

### 🇺🇸 SambaNova
- **官网链接**: [点击访问](https://cloud.sambanova.ai/)
- **OpenAI 兼容 Base URL**: `https://api.sambanova.ai/v1`
- **规则与免费条件**: No perpetual free tier. Offers $5 in free API credits to new users (valid for 30 to 90 days, no credit card required) subject to Free Tier rate limits. Paid options: Developer Tier (pay-as-you-go) with higher rate limits (e.g., 20M tokens/day) once a billing method is linked.
- **支持的模型 / 功能特征**:
  - `Meta-Llama-3.3-70B-Instruct`
  - `DeepSeek-V3.1`
  - `gemma-4-31B-it`
  - `gpt-oss-120b`

### 🔍 SearXNG
- **官网链接**: [点击访问](https://github.com/searxng/searxng)
- **规则与免费条件**: Free, open-source metasearch engine that aggregates results from more than 70 search services. Completely free to self-host (using Docker or local installation) with zero API keys required. Integrates with agents via setting the SEARXNG_URL environment variable to point to the self-hosted instance endpoint.
- **支持的模型 / 功能特征**:
  - `Self-Hosted Metasearch API`

### 🇨🇳 SiliconFlow
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://siliconflow.cn/zh-cn/)
- **OpenAI 兼容 Base URL**: `https://api.siliconflow.cn/v1`
- **规则与免费条件**: Offers a 'Get Started for Free' tier featuring select free models (e.g., Qwen2.5-7B-Instruct) subject daily rate limits (e.g., 50 requests/day). New accounts receive $1 in free trial credits. Paid options: Pay-as-you-go token pricing for Pro models.
- **支持的模型 / 功能特征**:
  - `MiniMax-M3`
  - `Nex-N2-Pro`
  - `DeepSeek-V4-Pro`
  - `Qwen2.5-7B-Instruct`

### 🇨🇳 StepFun
- **官网链接**: [点击访问](https://platform.stepfun.com/)
- **规则与免费条件**: Offers the Step series of multimodal models. Free tier is available under the V0 tier ($0 account balance) with rate limits of 10 RPM and 5,000,000 TPM. Certain models (like Step 3.5 Flash) are also free to use via OpenRouter. Paid tiers require topping up your account balance (starting from $15 up to $1,500+), which increases RPM, TPM, and concurrency limits.
- **支持的模型 / 功能特征**:
  - `Step 3.5 Flash`
  - `Step 3.7 Flash`
  - `Step-1-128k`
  - `Step-2`

### 🇺🇸 Switchpoint
- **官网链接**: [点击访问](https://switchpoint.ai/)
- **规则与免费条件**: Intelligent LLM routing service. Offers a free trial with small signup credits for new developer accounts. Paid options include a Pay-As-You-Go Developer Plan (using top-up credits based on routed models) and a flat-rate Stable Tier ($1.05/M input and $4.25/M output tokens).
- **支持的模型 / 功能特征**:
  - `GPT-4o (Routed)`
  - `Claude 3.5 Sonnet (Routed)`
  - `Llama 3.1 (Routed)`

### 🕵️ Tavily
- **官网链接**: [点击访问](https://tavily.com/)
- **规则与免费条件**: AI-native search engine designed for LLMs. Free tier provides 1,000 search API queries/month (no credit card required, resets monthly). Billed by usage: Basic Search consumes 1 credit, Advanced Search consumes 2 credits, Extract consumes 1 credit/5 URLs. Paid plans: Pay-as-you-go at $0.008/credit, or monthly subscriptions starting at $15/month.
- **支持的模型 / 功能特征**:
  - `Search API`
  - `Extract API`
  - `Crawl API`

### 🇺🇸 Together
- **官网链接**: [点击访问](https://together.ai/)
- **OpenAI 兼容 Base URL**: `https://api.together.xyz/v1`
- **规则与免费条件**: Requires a minimum credit purchase of $5 to activate and maintain API access. New accounts generally receive $5 in free credits to test the API. Billed under a pay-as-you-go serverless model ranging from $0.05 to $9.00 per million tokens (e.g., Llama 3.3 70B is ~$0.88/M tokens; DeepSeek R1 is ~$3.00/$7.00 per M tokens). Offers input context caching discounts.
- **支持的模型 / 功能特征**:
  - `DeepSeek R1`
  - `DeepSeek V3.1`
  - `Llama 3.3 (70B)`
  - `Qwen 3.6 Plus`
  - `Kimi K2.6`

### 🌐 Venice
- **推荐注册链接**: [点击访问]()
- **普通官网链接**: [点击访问](https://venice.ai/)
- **OpenAI 兼容 Base URL**: `https://api.venice.ai/api/v1`
- **规则与免费条件**: Freemium model. Free tier allows 10 text prompts and 15 image prompts per day without login. Paid plans: Pro ($18/mo for unlimited text, 1000 images/day, and 100 credits/mo), Pro Plus ($68/mo with 7,500 credits/mo), and Max ($200/mo with 22,500 credits/mo). API access is included in the Pro tier.
- **支持的模型 / 功能特征**:
  - `Claude 3.5 Sonnet`
  - `Gemini 3 Flash Preview`
  - `Llama 3.1`
  - `DeepSeek R1`
  - `Venice Uncensored`

### 🎙️ Voice Tools (OpenAI)
- **官网链接**: [点击访问](https://platform.openai.com/)
- **规则与免费条件**: Hermes audio transcription and speech integration using OpenAI Whisper (STT) and OpenAI TTS. Billed directly via the configured OpenAI API key (pay-as-you-go). Whisper is priced at $0.006/minute of audio. OpenAI TTS is priced at $15/M characters (Standard) and $30/M characters (HD).
- **支持的模型 / 功能特征**:
  - `whisper-1`
  - `tts-1`
  - `tts-1-hd`

### 💬 WaCLI
- **官网链接**: [点击访问](https://github.com/topics/whatsapp-cli)
- **规则与免费条件**: WhatsApp CLI tool for sending, syncing, and alerting messages directly from the server command-line.

### 🇺🇸 Wafer
- **官网链接**: [点击访问](https://wafer.ai/)
- **规则与免费条件**: Optimized AI performance engineering and inference platform. Does not offer a traditional free tier. Provides flat-rate subscription passes: Starter (~$10/week for 1,000 requests every 5 hours) and Privacy (~$25/week for 2,000 requests every 5 hours with zero data retention). Also offers pay-as-you-go serverless billing for enterprise accounts.
- **支持的模型 / 功能特征**:
  - `Qwen 3.5 397B-A17B`
  - `GLM-5.1`
  - `Kimi-K2.6`

### 🇺🇸 Weights & Biases
- **官网链接**: [点击访问](https://wandb.ai/)
- **规则与免费条件**: W&B is an MLOps platform (not a model hosting provider). Free tier for personal or academic use offers unlimited experiments and tracked hours, and 5 GB of artifact storage. Paid options: Pro and Enterprise plans for team collaboration and commercial use.
- **支持的模型 / 功能特征**:
  - `Integrates with Llama`
  - `Integrates with GPT`
  - `Integrates with Claude`
  - `Integrates with Stable Diffusion`

### 🇨🇳 Xiaomi
- **官网链接**: [点击访问](https://xiaoai.mi.com/)
- **规则与免费条件**: No permanent free tier. Offers limited-time promotions (e.g., free access to flagship MiMo-V2.5 models or TTS model) and partner integrations (e.g., Cline, OpenCode) with models labeled 'FREE'. Paid options: Pay-as-you-go token billing (e.g., MiMo-V2.5 at ¥1.00/M tokens Cache Miss) and Token Plan subscription packages starting around ¥39/month.
- **支持的模型 / 功能特征**:
  - `MiMo-V2.5 Pro`
  - `MiMo-V2-Flash`
  - `MiMo-V2-Omni`
  - `MiMo-V2-TTS`

### 🇨🇳 Z.ai
- **官网链接**: [点击访问](https://open.bigmodel.cn/)
- **规则与免费条件**: Offers free-tier access for specific models like GLM-4-Flash and GLM-4.5-Flash. New users receive registration bonuses of free tokens (millions of tokens) valid for a limited period. Paid API usage is billed per token on a pay-as-you-go model. Offers GLM Coding subscription plans for premium/agentic models.
- **支持的模型 / 功能特征**:
  - `GLM-5`
  - `GLM-5-Turbo`
  - `GLM-4.7`
  - `GLM-4.5-Flash`
  - `CogVideoX`
  - `CodeGeeX`

### 🌐 io.net
- **官网链接**: [点击访问](https://io.net/)
- **规则与免费条件**: No traditional free tier. Offers subscription plans that include monthly usage credits: Professional Plan ($15/mo in credits for light workloads, refreshes daily) and Developer Plan ($150/mo in credits with ~10% discount, refreshes every 8 hours). Beyond credits, usage is pay-as-you-go billed via $IO tokens or credit cards.
- **支持的模型 / 功能特征**:
  - `Llama-3.3-70B-Instruct`
  - `Custom Docker Container Deployments`

### 🇺🇸 xAI
- **官网链接**: [点击访问](https://console.x.ai/)
- **OpenAI 兼容 Base URL**: `https://api.x.ai/v1`
- **规则与免费条件**: Grok chatbot has a limited free tier (~10 messages every 2 hours) on grok.com/X app. The developer API (console.x.ai) offers $25 in promotional credits for new accounts. A data-sharing opt-in program offers up to $150/month in credits (requires minimum $5 spend to enroll). Paid API usage is consumption-based (e.g., Grok 4.3 at $1.25/M input and $2.50/M output tokens).
- **支持的模型 / 功能特征**:
  - `Grok 4.3`
  - `Grok Build 0.1`
  - `Grok Imagine API`
  - `Grok Voice API`

## 🤝 贡献指南与自动化工作流

本仓库由 Hermes 智能体自动维护。每日作业会自动扫描上游来源并处理 GitHub 议题（Issues）。

- **汇报规则变更**: 如果某个免费额度已更改，或者某个提供商已停止提供服务，请**提交一个 Issue**，说明具体的服务商名称及变化细节。机器人将自动通过网页搜索进行核实，并在 24 小时内更新该文件。

- **提交更新**: 欢迎提交更新 `free-llm-providers.json` 数据库或脚本的 PR。请不要直接编辑 `README.md`，因为它是由脚本动态生成的。

---
*上次更新时间: 2026-06-19 10:00:13 (北京时间) | 编译 ID: 20260619100013*