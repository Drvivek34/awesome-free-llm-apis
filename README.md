# API-Pulse: The Ultimate Free LLM, Search, & AI Tool API Directory ⚡

*A curated, auto-updated registry of Large Language Model (LLM) APIs, search APIs, voice transcriptions, and developer CLI tools with permanent free tiers or trial credits. Updated daily by Hermes bots.*

🌐 **[English](README.md)** · **[简体中文](README.zh-CN.md)**

## 📌 LLM Inference & API Providers

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit / Conditions | Key Models / Features | API Key / Referral Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇮🇱 **AI21** | First-Party | 🇮🇱 | ✅ Yes | Offers a free trial of $10 in credits valid for three months upon account creation. No permanent free tier. Once credits are exhausted or expired, users must transition to a paid plan. Commercial API access is usage-based (pay-as-you-go). Model usage via third-party cloud providers (AWS Bedrock, Azure) is governed by their respective rates. | `Jamba 1.5 Large`, `Jamba 1.5 Mini`, `Jamba 1.6` | [Normal Link](https://www.ai21.com/) |
| 🇮🇱 **AionLabs** | First-Party | 🇮🇱 | ✅ Yes | Offers a free tier with a recurring daily credit allowance (approx. 20,000 tokens per day) for testing agent jobs, APIs, and browser chat with no credit card required. Paid options include Prepaid (pay-as-you-go) and monthly Business plans. API is OpenAI-compatible and can also be accessed via Puter.js. | `Aion-2.0`, `Aion-1.0`, `Aion-1.0-Mini` | [Normal Link](https://www.aionlabs.ai/) |
| 🌐 **AkashML** | Inference Provider | 🌐 | ✅ Yes | New users of the AkashML managed inference service receive $100 in free AI token credits for both playground and API usage. Additionally, the Akash Console for self-hosted container deployments offers a $100 free trial (requires credit card for verification, 24h limit per instance). Paid options are pay-per-use, operating as a decentralized marketplace with reverse auctions resulting in 60-85% savings compared to standard cloud providers. | `Llama 3.3 70B`, `DeepSeek V4 Flash`, `DeepSeek V3.2` (+1 more) | [Normal Link](https://akash.network/) |
| 🇨🇳 **Alibaba Cloud Int.** | Cloud Provider | 🇨🇳 | ✅ Yes | Provides DashScope / Model Studio developer APIs and AI Coding Plans. New users receive a free token quota valid for 90 days (Singapore region only, sk- keys). Standard DashScope API is pay-as-you-go based on token usage. The AI Coding Plan is a fixed-price monthly subscription (Lite/Pro, sk-sp- keys) providing flat-rate prompt limits instead of token billing. | `Qwen3.7-Max`, `Qwen3.7-Plus`, `Qwen3.6-Plus` (+3 more) | [Normal Link](https://www.alibabacloud.com/) |
| 🇺🇸 **Amazon Bedrock** | Cloud Provider | 🇺🇸 | ❌ No (SDK needed) | No permanent free tier. New AWS accounts receive up to $200 in promotional credits ($100 at signup, $100 via guided tasks) valid for 6 months. Startup programs offer $1,000 to $300,000+ in credits. Paid options: On-Demand pay-as-you-go per 1M tokens, Batch Inference (approx. 50% discount), and Provisioned Throughput (dedicated capacity billing). | `Anthropic Claude 3.5 Sonnet`, `Meta Llama 3.3`, `Amazon Titan` | [Normal Link](https://aws.amazon.com/bedrock/) |
| 🇺🇸 **Anthropic** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Claude.ai interactive chat offers a permanent free tier with usage limits capped on a rolling 5-hour window. The developer API has no permanent free tier but provides a small one-time starter credit upon account creation. Paid options include Claude.ai Pro ($20/month) and consumption-based developer API billing. The CLAUDE_CODE_OAUTH_TOKEN environment variable can be used to authenticate coding tasks via Anthropic's OAuth device flow. | `Claude 4.6 Sonnet`, `Claude 4.7 Opus`, `Claude 4.5 Haiku` | [Normal Link](https://console.anthropic.com/) |
| 🇺🇸 **Arcee AI** | First-Party | 🇺🇸 | ✅ Yes | Does not offer a traditional permanent free tier for its commercial API. However, the Trinity Builders Program offers free inference access for approved developer, research, and open-source projects. Otherwise, commercial API is pay-as-you-go (e.g., Trinity-Mini at ~$0.045/1M input tokens and ~$0.15/1M output tokens). Models are open-weight and can be downloaded for free local deployment. | `Trinity-Large-Thinking`, `Trinity-Large-Preview`, `Trinity-Mini` (+1 more) | [Normal Link](https://www.arcee.ai/) |
| 🇺🇸 **AtlasCloud** | Inference Provider | 🇺🇸 | ✅ Yes | Provides a unified API to access over 300 models on a pay-as-you-go consumption model (e.g., DeepSeek V3 at $0.07/1M tokens). GPU Cloud instances start around $2.95/hr with per-second billing. Standard developer subscriptions are currently noted as unavailable, and evaluation credits/promotions vary dynamically within the console. | `DeepSeek V3`, `Kling`, `Seedance` (+1 more) | [Normal Link](https://atlascloud.io/) |
| 🇺🇸 **Azure** | Cloud Provider | 🇺🇸 | ✅ Yes | Offers $200 free credits for the first 30 days, 12 months of popular free services, and 65+ always-free services (subject to monthly limits) for new accounts. Unused credits expire and require manual upgrade to Pay-As-You-Go. Azure for Students offers $100 credits without credit card verification. | `GPT-5.5 (Azure OpenAI)`, `GPT-5.4 (Azure OpenAI)`, `Llama (Foundry)` (+2 more) | [Normal Link](https://azure.microsoft.com/) |
| 🇨🇳 **Baidu Qianfan** | First-Party | 🇨🇳 | ✅ Yes | Offers permanently free access to select lightweight models like ERNIE-3.5-8K and ERNIE-Speed-8K. Premium models like ERNIE-4.0-8K include introductory trial quotas (e.g., 1M free tokens in the first month). Paid options include pay-per-token consumption for proprietary ERNIE models and third-party models, as well as a paid 'Coding Plan' subscription for developer tools. | `ERNIE 5.1`, `ERNIE-4.0-8K`, `ERNIE-3.5-8K` (+1 more) | [Normal Link](https://cloud.baidu.com/product/wenxin.html) |
| 🇺🇸 **Baseten** | Inference Provider | 🇺🇸 | ✅ Yes | No permanent free tier. New workspaces receive $30 in free trial credits. Startup programs offer up to $25,000 for dedicated deployments and $2,500 for model APIs. Paid options are usage-based on a per-replica-hour or per-token basis with scale-to-zero capabilities to eliminate idle costs. | `Meta Llama 3`, `Mistral`, `Whisper` (+1 more) | [Normal Link](https://www.baseten.co/) |
| 🇺🇸 **Cerebras** | Inference Provider | 🇺🇸 | ✅ Yes | Generous free tier offering 1,000,000 free tokens per day (no credit card required). Paid options: Developer Tier (pre-paid starting at $10) with 10x higher rate limits and priority processing; Enterprise Tier with custom pricing for dedicated hosting and support. | `Llama 3.3`, `Llama 3.1 70B`, `Llama 4 Scout` (+1 more) | [Normal Link](https://cloud.cerebras.ai/) |
| 🇺🇸 **Chutes** | Inference Provider | 🇺🇸 | ✅ Yes | No longer offers a free tier as of March 15, 2026. Operates under a pay-as-you-go (PAYGO) model for token inference and hourly private GPU deployments. Optional paid monthly subscription plans, Plus ($10/month) and Pro ($20/month), provide daily request quotas and a 6-10% discount on excess PAYGO usage. Startup credits (up to $10,000) are available for qualifying companies. | `DeepSeek-R1`, `DeepSeek-V3.2-TEE`, `Mistral-Nemo-Instruct-2407` (+2 more) | [Normal Link](https://chutes.ai/) |
| 🇺🇸 **Clarifai** | Inference Provider | 🇺🇸 | ✅ Yes | Has transitioned from tier-based subscriptions to a credits-based Pay-As-You-Go model. New users can receive a one-time $5 welcome bonus (valid for 30 days) upon phone verification to test serverless API calls and custom deployments. Paid access requires purchasing additional credits to top up the account balance. | `general-image-recognition`, `DeepSeek-V3_2`, `Llama-3_2-3B-Instruct` (+1 more) | [Normal Link](https://www.clarifai.com/) |
| 🇺🇸 **Cloudflare** | Cloud Provider | 🇺🇸 | ✅ Yes | Free tier provides a daily allocation of 10,000 Neurons across all accounts. Paid options: Workers Paid plan starts at $5/month, and usage beyond the daily free allocation is billed at $0.011 per 1,000 Neurons. | `llama-3.1-8b-instruct`, `mistral-7b-instruct-v0.2`, `stable-diffusion-xl-base-1.0` | [Normal Link](https://dash.cloudflare.com/) |
| 🇨🇦 **Cohere** | First-Party | 🇨🇦 | ✅ Yes | Offers a free Evaluation (Trial) tier for developers with a rate-limited trial API key (1,000 API calls/month, 20 requests/minute). Paid options include the Production Tier with pay-as-you-go billing based on token usage (e.g., 500 RPM limit) and Enterprise agreements for dedicated hosting or custom SLA needs. | `Command A+`, `Command R`, `Command R7B` (+3 more) | [Normal Link](https://dashboard.cohere.com/api-keys) |
| 🇮🇱 **Decart** | First-Party | 🇮🇱 | ✅ Yes | Operates on a pay-as-you-go model with no monthly subscription fees. New accounts receive free trial credits to test the API and models. Paid options are charged based on execution metrics: realtime models are billed per second of active generation (e.g., Lucy 2.1 at ~$0.02/sec), video models per second generated, and image models per generation. | `Lucy 2.1`, `Lucy Image 2`, `Oasis 3` | [Normal Link](https://www.decart.ai/) |
| 🇺🇸 **DeepInfra** | Inference Provider | 🇺🇸 | ✅ Yes | Does not offer a formal subscription-based free tier. However, users can perform unauthenticated testing of models with an empty api_key (rate-limited by IP address). Signing up can sometimes grant temporary token allotments. Paid options are strictly pay-as-you-go based on token usage (e.g., starting at ~$0.02/1M tokens) or execution time for non-LLMs. Cached tokens are discounted (e.g., ~$0.145/1M tokens). | `Llama 3.3`, `DeepSeek-V4-Pro`, `gemini-3.5-flash` (+2 more) | [Referral Link]() / [Normal Link](https://deepinfra.com/) |
| 🇨🇳 **DeepSeek** | First-Party | 🇨🇳 | ✅ Yes | The web chat interface (chat.deepseek.com) is permanently free. The API does not have an ongoing free tier but offers 5 million free trial tokens for new developer accounts. Paid options follow a pay-as-you-go model: DeepSeek V4-Flash is priced at $0.14/1M input and $0.28/1M output tokens, and DeepSeek V4-Pro is priced at $0.435/1M input and $0.87/1M output tokens. Significant discounts are offered for cache hits. | `DeepSeek V4-Flash`, `DeepSeek V4-Pro` | [Normal Link](https://platform.deepseek.com/) |
| 🇺🇸 **Fireworks** | Inference Provider | 🇺🇸 | ✅ Yes | No permanent free tier. Offers $1 in free starter credits for new signups. Paid options: Serverless pay-per-token pricing based on model size (sub-4B: $0.10/1M tokens, 4B-16B: $0.20/1M tokens, 16B+: $0.90/1M tokens). Offers 50% discount for cached input tokens and batch inference. | `Llama 3.3`, `Qwen 2.5`, `DeepSeek-V3` (+1 more) | [Normal Link](https://fireworks.ai/) |
| 🇰🇷 **Friendli** | Inference Provider | 🇰🇷 | ✅ Yes | No permanent free plan. Offers substantial startup/promotional GPU inference credits ranging from $10,000 up to $50,000 to help teams scale. Otherwise uses usage-based pay-as-you-go pricing optimized for high-throughput production workloads. | `Llama 3.1`, `Gemma 2`, `Mistral` (+1 more) | [Normal Link](https://friendli.ai/) |
| 🇺🇸 **GMI Cloud** | Cloud Provider | 🇺🇸 | ✅ Yes | High-performance GPU cloud. No public permanent free tier. Offers free access to specific model endpoints (e.g. Llama 3.3, DeepSeek R1) for inference on the Model Hub dashboard. Paid options use a pay-as-you-go model with transparent pricing based on GPU hardware (e.g. NVIDIA H100, B200) and service type. | `DeepSeek`, `Llama`, `Qwen` (+1 more) | [Normal Link](https://gmicloud.com/) |
| 🇺🇸 **Google AI Studio** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Free tier available for the Gemini Developer API on non-billing-enabled projects, subject to RPM, TPM, and RPD rate limits (data may be used for model training). Access to Pro models on the free tier was restricted starting April 1, 2026. Enabling billing removes the free tier and transitions the project to pay-as-you-go pricing (prepaid billing for new users, with mandatory spend caps and context caching discounts). | `Gemini 1.5 Flash`, `Gemini 1.5 Pro`, `Gemini 2.5` (+1 more) | [Normal Link](https://aistudio.google.com/app/apikey) |
| 🇺🇸 **Google Vertex** | Cloud Provider | 🇺🇸 | ❌ No (SDK needed) | No permanent free tier. New Google Cloud accounts receive $300 in free credits valid for 90 days. Vertex AI Express Mode offers limited free access hours or agent engines in a 90-day window. Paid options are pay-as-you-go. (Google AI Studio provides a separate, rate-limited free tier for developer prototyping). | `Gemini 1.5 Pro`, `Gemini 1.5 Flash`, `Imagen 3` (+1 more) | [Normal Link](https://cloud.google.com/vertex-ai) |
| 🇺🇸 **Groq** | Inference Provider | 🇺🇸 | ✅ Yes | Offers an always-free API tier (no credit card required) subject to organization-level rate limits (e.g., 30 RPM, 30,000 TPM, 14,400 RPD). Paid Developer Tier (pay-as-you-go) provides up to 10x higher rate limits, with input costs starting at $0.05/1M tokens (Llama 3.1 8B) up to $0.59 input / $0.79 output per 1M tokens (Llama 3.3 70B), plus a 50% discount for Batch API and prompt caching. | `Llama 3.1 8B`, `Llama 3.3 70B`, `Mixtral` (+2 more) | [Normal Link](https://console.groq.com/keys) |
| 🇦🇪 **Inception** | First-Party | 🇦🇪 | ✅ Yes | Provides 10 million free tokens upon account creation to test and prototype. OpenAI-compatible API operates on usage-based pricing with customizable user-defined billing limits and email alerts to block overages. | `Mercury 2`, `Mercury Edit 2`, `JAIS` | [Normal Link](https://www.g42.ai/) |
| 🇺🇸 **Inceptron** | Inference Provider | 🇺🇸 | ✅ Yes | No direct free tier. Operates strictly on consumption-based pricing designed for EU data sovereignty. Access is typically provided through third-party gateways (e.g., Kilo.ai or Requesty) using per-million-token pay-as-you-go billing (e.g., $0.15/1M input tokens for MiniMax M2.5). Custom pricing is available for startups and enterprises. | `MiniMax M2.5`, `Kimi K2.6`, `GLM 5.1` | [Normal Link](https://inceptron.com/) |
| 🇺🇸 **Infermatic** | Inference Provider | 🇺🇸 | ✅ Yes | Structured around flat-rate subscription tiers rather than token-based billing. Includes a Free Plan ($0/mo for select models like Rocinante-12B), Essential Tier ($9/mo), Standard Tier ($16/mo), and Plus Tier ($20/mo for unrestricted prompts/results, zero-logs policy, and advanced models). | `Rocinante-12B-v1.1`, `Fallen Llama 3.3`, `Strawberrylemonade L3` (+2 more) | [Normal Link](https://infermatic.ai/) |
| 🇺🇸 **Inflection** | First-Party | 🇺🇸 | ✅ Yes | The Pi consumer personal assistant app is completely free with no usage limits or premium tiers. The developer API operates on usage-based pricing (e.g., Inflection-3 billed at approx. $2.50 per million input tokens and $10.00 per million output tokens) with custom enterprise options. | `Inflection-3`, `Inflection-2.5`, `Pi` | [Normal Link](https://inflection.ai/) |
| 💻 **Kilocode** | Inference Provider | 💻 | ✅ Yes | AI-native gateway and assistant platform. Auto Free Tier routes to free models (e.g., Llama 3.1 8B, Qwen 2.5 7B) through Kilo Gateway. Supports Bring Your Own Key (BYOK) to route to user's OpenAI, Anthropic, or Gemini keys for free or paid usage. Paid Kilo Pass subscriptions start at $19/month (Starter) to $199/month (Expert) for hosted model credits. | `kilo-free`, `Llama series`, `Qwen series` | [Normal Link](https://kilo.ai/) |
| 🇺🇸 **Liquid** | First-Party | 🇺🇸 | ✅ Yes | Free self-service open access to download, customize, and deploy models (via Hugging Face or LEAP platform) under the LFM Open License v1.0, which has a commercial use threshold: free for companies under $10 million in annual revenue; companies above this must purchase a commercial license. Liquid Apollo is also free for mobile devices. Enterprise tiers offer custom agreements. | `LFM-1B`, `LFM-3B`, `LFM-40B` (+1 more) | [Normal Link](https://www.liquid.ai/) |
| 🌐 **Mancer** | Inference Provider | 🌐 | ✅ Yes | No monthly subscription free tier. Provides access to select 'free models' for initial testing. Otherwise uses a pay-as-you-go system with credit packs ranging from $4.99 (~1.25M credits) to $249.99 (~100M credits). No subscription lock-in. A 25% token discount is available if users opt into Anonymous Logging (data sharing for training). | `Weaver (alpha)`, `Magnum v4 72B`, `ReMM SLERP 13B` (+1 more) | [Referral Link]() / [Normal Link](https://mancer.tech/) |
| 🇨🇳 **MiniMax** | First-Party | 🇨🇳 | ✅ Yes | No permanent free tier. Provides limited trial credits to new developer accounts for testing. Paid options: Token Plan (monthly subscription starting at $10/month) or Pay-as-you-go (token packages starting at $5 for 5,000 credits). Standard rates for flagship models are typically around $0.30-$0.50/1M input tokens and $1.00-$1.20/1M output tokens. | `MiniMax-M3`, `MiniMax-M2.7`, `MiniMax-M2.5` (+1 more) | [Normal Link](https://platform.minimaxi.com/) |
| 🇫🇷 **Mistral** | First-Party | 🇫🇷 | ✅ Yes | API (La Plateforme) offers a permanent Free Tier for evaluation and prototyping, subject to strict rate limits (e.g., 1 request/second global limit). Paid options: Scale plan (pay-as-you-go). Startup programs provide up to $30,000 in credits. Le Chat consumer chat service offers a free plan capped at ~25 messages/day and a Pro plan at $14.99/month. | `Mistral Medium 3.5`, `Mistral Small 4`, `Mistral Large 3` (+1 more) | [Normal Link](https://console.mistral.ai/api-keys) |
| 🇨🇳 **Moonshot AI** | First-Party | 🇨🇳 | ✅ Yes | Kimi chat interface is free for casual users with query volume and context limits. Pro features (Agent Swarm, Deep Research) are available via monthly subscriptions: Moderato (~$19/mo), Allegretto, and Vivace (up to $199/mo). Developer API is pay-as-you-go ($0.55-$0.95 per million input, $2.50-$4.00 per million output tokens) with automatic context caching. Open-weight versions of Kimi K2 models are free to self-host. | `Kimi K2.6`, `Kimi K2.7`, `Moonshot-v1` | [Normal Link](https://platform.moonshot.cn/) |
| 🇺🇸 **Morph** | Inference Provider | 🇺🇸 | ✅ Yes | Includes Morph LLM (developer assistant) which offers a free tier of 200 requests/month, and Morph Studio (video/image generation) which offers a free plan of 75 credits/month. Paid options: Morph LLM features Starter, Pro, and Scale plans with per-token billing (e.g., $0.80-$0.90/1M input tokens). Morph Studio plans start at ~$10/month (or $7/month billed annually) for 3,000 credits. | `Morph V3 Fast`, `Morph V3 Large`, `Morph-Video-1` (+1 more) | [Normal Link](https://www.morph.so/) |
| 🟢 **NVIDIA NIM** | Inference Provider | 🟢 | ✅ Yes | Provides free developer access to hosted NIM APIs for development, prototyping, and testing (no credit card required, never expires). Subject to model-specific rate limits (approx. 40 RPM). Strictly for development and testing. Paid options require self-hosting NIM containers under an NVIDIA AI Enterprise license. | `llama-3.3-70b-instruct`, `nemotron-4-340b-instruct`, `deepseek-r1` | [Normal Link](https://build.nvidia.com) |
| 🇳🇱 **Nebius Token Factory** | Inference Provider | 🇳🇱 | ✅ Yes | No permanent free tier. Provides free promotional credits upon account sign-up ('Start Free' model) to test over 60 open-source models in the Playground or via API. Paid usage is pay-per-token for serverless access, or billed by compute hours for dedicated endpoints. | `DeepSeek-V3`, `Qwen 2.5`, `Qwen 3` (+2 more) | [Referral Link]() / [Normal Link](https://nebius.ai/) |
| 🇺🇸 **NextBit** | Inference Provider | 🇺🇸 | ✅ Yes | No public free tier. Operates on a pay-per-token serverless API platform or fixed-price dedicated instances for enterprise needs. | `Llama 3.3 70B`, `Qwen 2.5 72B`, `Llama 3.3 8B` | [Normal Link](https://nextbit.ai/) |
| 🇺🇸 **NovitaAI** | Inference Provider | 🇺🇸 | ✅ Yes | No permanent free tier. New accounts receive $1 in free credits upon signup, with promotions offering up to $100 in Sandbox credits (valid for 90 days) or $10 for specific models. Startups can receive up to $10,000 in credits. Paid options: Pay-as-you-go based on token usage or hourly dedicated GPU instance hosting. | `Qwen3.7-Max`, `MiniMax-M3`, `Kimi K2.7 Code` (+1 more) | [Referral Link]() / [Normal Link](https://novita.ai/) |
| ☁️ **Ollama Cloud** | Inference Provider | ☁️ | ✅ Yes | Hosted cloud service for Ollama models. Free tier ($0/month) provides access to a selection of cloud-enabled models, subject to base limits based on actual GPU compute/execution time rather than tokens. Paid plans: Pro ($20/month, 50x usage, 3 concurrent cloud models) and Max ($100/month, 5x Pro usage, 10 concurrent cloud models). | `Llama 3.3`, `Qwen 2.5`, `Mistral Small` | [Normal Link](https://ollama.com/) |
| 🇺🇸 **OpenAI** | First-Party | 🇺🇸 | ✅ Yes | No permanent free API tier. New accounts receive a one-time trial credit (e.g., $5 to $18) expiring in 3 months. Users can opt into the Data Sharing Program to get a daily quota of free tokens on specific models (e.g., gpt-4o-mini, gpt-4.1-mini) in exchange for training data. General usage is pay-as-you-go per-token billing (e.g., GPT-5.5 at $5/1M input, $30/1M output; GPT-5.4-nano at $0.10-$0.20/1M input), with input caching and Batch API (50% off) discounts. | `GPT-5.5`, `GPT-5.4`, `GPT-5.4-mini` (+3 more) | [Normal Link](https://platform.openai.com/) |
| 🌐 **OpenRouter** | Inference Provider | 🌐 | ✅ Yes | 20 RPM, 50 RPD free models (up to 1,000 RPD with $10 lifetime top-up) | `laguna-xs-2.1:free`, `north-mini-code:free`, `nemotron-3.5-content-safety:free` (+12 more) | [Normal Link](https://openrouter.ai/keys) |
| 🇺🇸 **Parasail** | Inference Provider | 🇺🇸 | ✅ Yes | Offers a 'Serverless - Free' tier for prototyping and testing, limited to 5 Requests Per Minute (RPM). Paid options: Pay-per-token serverless billing or hourly GPU instance billing, which typically requires a linked payment method and a $25 charging threshold. | `Qwen series`, `DeepSeek series`, `Llama series` | [Normal Link](https://parasail.io/) |
| 🇺🇸 **Perplexity** | Inference Provider | 🇺🇸 | ✅ Yes | No permanent free tier. New accounts receive $25-$50 in trial credits. Perplexity Pro subscribers ($20/month) receive $5 in monthly API credits. Startup programs offer grants from $500 to $5,000+. Paid options: Pay-as-you-go token pricing. | `Sonar Small Online`, `Sonar Large Online`, `Sonar Huge Online` (+1 more) | [Referral Link]() / [Normal Link](https://www.perplexity.ai/pro) |
| 🇫🇷 **Poolside** | First-Party | 🇫🇷 | ✅ Yes | Enterprise-focused coding assistant and foundation models. Models are available with open weights (e.g., Laguna XS.2 is Apache-2.0 licensed). Free access to models is available via third-party integrations like OpenRouter, Puter.js, Requesty, and Krater.ai. Direct business model is custom enterprise deployment (on-premises or private VPCs), with no standard public self-serve pay-as-you-go pricing listed. | `Laguna M.1`, `Laguna XS.2` | [Normal Link](https://poolside.ai/) |
| 🇺🇸 **Reka AI** | First-Party | 🇺🇸 | ✅ Yes | Developer API offers $10 in free credits monthly. Reka Vision API offers a free evaluation tier of 3 free hours (180 minutes) of indexed video. Paid usage is consumption-based (pay-as-you-go) per token (for text) or per-minute/request (for video/image/research tasks). | `Reka Core`, `Reka Flash`, `Reka Edge` (+1 more) | [Normal Link](https://www.reka.ai/) |
| 🇺🇸 **SambaNova** | Inference Provider | 🇺🇸 | ✅ Yes | No perpetual free tier. Offers $5 in free API credits to new users (valid for 30 to 90 days, no credit card required) subject to Free Tier rate limits. Paid options: Developer Tier (pay-as-you-go) with higher rate limits (e.g., 20M tokens/day) once a billing method is linked. | `Meta-Llama-3.3-70B-Instruct`, `DeepSeek-V3.1`, `gemma-4-31B-it` (+1 more) | [Normal Link](https://cloud.sambanova.ai/) |
| 🇨🇳 **SiliconFlow** | Inference Provider | 🇨🇳 | ✅ Yes | Offers a 'Get Started for Free' tier featuring select free models (e.g., Qwen2.5-7B-Instruct) subject daily rate limits (e.g., 50 requests/day). New accounts receive $1 in free trial credits. Paid options: Pay-as-you-go token pricing for Pro models. | `MiniMax-M3`, `Nex-N2-Pro`, `DeepSeek-V4-Pro` (+1 more) | [Referral Link]() / [Normal Link](https://siliconflow.cn/zh-cn/) |
| 🇨🇳 **StepFun** | First-Party | 🇨🇳 | ✅ Yes | Offers the Step series of multimodal models. Free tier is available under the V0 tier ($0 account balance) with rate limits of 10 RPM and 5,000,000 TPM. Certain models (like Step 3.5 Flash) are also free to use via OpenRouter. Paid tiers require topping up your account balance (starting from $15 up to $1,500+), which increases RPM, TPM, and concurrency limits. | `Step 3.5 Flash`, `Step 3.7 Flash`, `Step-1-128k` (+1 more) | [Normal Link](https://platform.stepfun.com/) |
| 🇺🇸 **Together** | Inference Provider | 🇺🇸 | ✅ Yes | Requires a minimum credit purchase of $5 to activate and maintain API access. New accounts generally receive $5 in free credits to test the API. Billed under a pay-as-you-go serverless model ranging from $0.05 to $9.00 per million tokens (e.g., Llama 3.3 70B is ~$0.88/M tokens; DeepSeek R1 is ~$3.00/$7.00 per M tokens). Offers input context caching discounts. | `DeepSeek R1`, `DeepSeek V3.1`, `Llama 3.3 (70B)` (+2 more) | [Normal Link](https://together.ai/) |
| 🌐 **Venice** | Inference Provider | 🌐 | ✅ Yes | Freemium model. Free tier allows 10 text prompts and 15 image prompts per day without login. Paid plans: Pro ($18/mo for unlimited text, 1000 images/day, and 100 credits/mo), Pro Plus ($68/mo with 7,500 credits/mo), and Max ($200/mo with 22,500 credits/mo). API access is included in the Pro tier. | `Claude 3.5 Sonnet`, `Gemini 3 Flash Preview`, `Llama 3.1` (+2 more) | [Referral Link]() / [Normal Link](https://venice.ai/) |
| 🇨🇳 **Xiaomi** | First-Party | 🇨🇳 | ❌ No (SDK needed) | No permanent free tier. Offers limited-time promotions (e.g., free access to flagship MiMo-V2.5 models or TTS model) and partner integrations (e.g., Cline, OpenCode) with models labeled 'FREE'. Paid options: Pay-as-you-go token billing (e.g., MiMo-V2.5 at ¥1.00/M tokens Cache Miss) and Token Plan subscription packages starting around ¥39/month. | `MiMo-V2.5 Pro`, `MiMo-V2-Flash`, `MiMo-V2-Omni` (+1 more) | [Normal Link](https://xiaoai.mi.com/) |
| 🇨🇳 **Z.ai** | First-Party | 🇨🇳 | ✅ Yes | Offers free-tier access for specific models like GLM-4-Flash and GLM-4.5-Flash. New users receive registration bonuses of free tokens (millions of tokens) valid for a limited period. Paid API usage is billed per token on a pay-as-you-go model. Offers GLM Coding subscription plans for premium/agentic models. | `GLM-5`, `GLM-5-Turbo`, `GLM-4.7` (+3 more) | [Normal Link](https://open.bigmodel.cn/) |
| 🇺🇸 **xAI** | First-Party | 🇺🇸 | ✅ Yes | Grok chatbot has a limited free tier (~10 messages every 2 hours) on grok.com/X app. The developer API (console.x.ai) offers $25 in promotional credits for new accounts. A data-sharing opt-in program offers up to $150/month in credits (requires minimum $5 spend to enroll). Paid API usage is consumption-based (e.g., Grok 4.3 at $1.25/M input and $2.50/M output tokens). | `Grok 4.3`, `Grok Build 0.1`, `Grok Imagine API` (+1 more) | [Normal Link](https://console.x.ai/) |

## 📌 Free Search Engine APIs

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit / Conditions | Key Models / Features | API Key / Referral Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇺🇸 **Brave Search API** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Metered pricing model. Automatically provides $5 in free credits every month, covering approximately 1,000 free requests/month. The standard Search Plan is priced at $5 per 1,000 requests (includes Web, News, Images, LLM context). Answers Plan is priced at $4 per 1,000 queries plus token costs. | `Search API (No custom LLM models hosted)` | [Normal Link](https://brave.com/search/api/) |
| 🔍 **Exa** | First-Party | 🔍 | ❌ No (SDK needed) | AI-native web search and content extraction engine. Free tier provides 1,000 free search queries/month for developer accounts (resets monthly, no credit card required). Paid plan starts at $20/month (includes 10,000 queries, overages at $0.002/query). Enterprise plans offer custom limits and dedicated endpoints. Includes search, contents/scraping, and similarity endpoints. | `Search API`, `Extract API`, `Similarity API` | [Normal Link](https://exa.ai/) |
| 🔥 **Firecrawl** | First-Party | 🔥 | ❌ No (SDK needed) | Web scraping, crawling, and AI-powered extraction API. Free tier provides 500 to 1,000 credits/month (no credit card required) for evaluation. Paid plans start at $19/month (Hobby, 3,000 credits) to $599/month (Scale). Operations consume credits based on complexity (e.g. AI extract/stealth proxies cost more). Also available as a free self-hosted open-source version (Docker Compose) with custom FIRECRAWL_API_URL environment overrides. | `Scraping API`, `Crawling API`, `AI Extraction API` | [Normal Link](https://www.firecrawl.dev/) |
| 🇺🇸 **Google Custom Search JSON API** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Closed to new signups. The API is in a sunset phase and will be fully discontinued on January 1, 2027. For existing customers, the free tier provides 100 queries/day. Additional queries cost $5 per 1,000 requests, up to a daily limit of 10,000 queries. | `Custom Search API (No LLM models hosted)` | [Normal Link](https://developers.google.com/custom-search/v1/overview) |
| ⚡ **Parallel** | First-Party | ⚡ | ❌ No (SDK needed) | AI-native search and extraction engine. Operates primarily on a pay-as-you-go consumption model with no standard monthly free tier for its hosted web APIs. Search requests are billed at ~$0.005/request and extraction at ~$0.001/request. The Parallel Search Model Context Protocol (MCP) server is free to run locally and does not require an API key. | `Search API`, `Extract API`, `Monitor API` | [Normal Link](https://parallel.ai/) |
| 🔍 **SearXNG** | First-Party | 🔍 | ❌ No (SDK needed) | Free, open-source metasearch engine that aggregates results from more than 70 search services. Completely free to self-host (using Docker or local installation) with zero API keys required. Integrates with agents via setting the SEARXNG_URL environment variable to point to the self-hosted instance endpoint. | `Self-Hosted Metasearch API` | [Normal Link](https://github.com/searxng/searxng) |
| 🕵️ **Tavily** | First-Party | 🕵️ | ❌ No (SDK needed) | AI-native search engine designed for LLMs. Free tier provides 1,000 search API queries/month (no credit card required, resets monthly). Billed by usage: Basic Search consumes 1 credit, Advanced Search consumes 2 credits, Extract consumes 1 credit/5 URLs. Paid plans: Pay-as-you-go at $0.008/credit, or monthly subscriptions starting at $15/month. | `Search API`, `Extract API`, `Crawl API` | [Normal Link](https://tavily.com/) |

## 📌 Speech-to-Text & Transcription APIs

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit / Conditions | Key Models / Features | API Key / Referral Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇺🇸 **AssemblyAI API** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Free tier includes up to 185 hours of batch transcription and 333 hours of streaming transcription (no credit card required). Startup program offers up to 200,000 hours of free credits. Billed under a pay-as-you-go model for additional usage, with core transcription rates and extra add-ons (Diarization, sentiment, LeMUR LLM analysis). | `Universal-3 Pro`, `Universal-1`, `Universal-3 Pro Streaming` (+1 more) | [Normal Link](https://www.assemblyai.com/) |
| 🇺🇸 **Deepgram API** | First-Party | 🇺🇸 | ❌ No (SDK needed) | Billed by usage (per-second billing). New users receive $200 in one-time free credits (approx. 12,000 minutes of transcription). Startup program provides up to $100,000 in credits over 12 months. Paid plans: Pay-As-You-Go, Growth (discounted rates with annual commitment), and Enterprise (custom rates/self-hosting). STT rates start at ~$0.0077/min, TTS starts at ~$0.015/1k characters, Voice Agent is ~$4.50/hour. | `Nova-3 (STT)`, `Flux (Conversational STT)`, `Aura-2 (TTS)` | [Normal Link](https://deepgram.com/) |
| 🗣️ **ElevenLabs** | First-Party | 🗣️ | ❌ No (SDK needed) | Premium AI speech synthesis and voice cloning. Free tier provides 10,000 characters/month (refreshes monthly) for personal use, limited to standard voices. Starter plan is $5/month ($1 first month, 30,000 characters, instant voice cloning). Paid plans range up to $330/month (Scale). Scribe STT offers a usage-based tier. | `Multilingual v2 (TTS)`, `Turbo v2.5 (TTS)`, `Scribe (STT)` (+1 more) | [Normal Link](https://elevenlabs.io/) |
| 🤖 **Mistral API (Voxtral)** | First-Party | 🤖 | ❌ No (SDK needed) | Hermes audio integration using Mistral's Voxtral speech-to-text and text-to-speech engine. Billed under the standard Mistral API billing structure (La Plateforme). STT and TTS are billed based on usage (characters synthesized or minutes transcribed). | `mistral-embed`, `voxtral-stt`, `voxtral-tts` | [Normal Link](https://console.mistral.ai/) |
| 🎙️ **Voice Tools (OpenAI)** | First-Party | 🎙️ | ❌ No (SDK needed) | Hermes audio transcription and speech integration using OpenAI Whisper (STT) and OpenAI TTS. Billed directly via the configured OpenAI API key (pay-as-you-go). Whisper is priced at $0.006/minute of audio. OpenAI TTS is priced at $15/M characters (Standard) and $30/M characters (HD). | `whisper-1`, `tts-1`, `tts-1-hd` | [Normal Link](https://platform.openai.com/) |

## 📌 CLI & AI Developer Tools

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit / Conditions | Key Models / Features | API Key / Referral Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 📰 **BlogWatcher CLI** | First-Party | 📰 | ❌ No (SDK needed) | Command-line tool to register, track, scan, and notify new blog and RSS feed updates on the fly. | *Not configured / Features listed below* | [Normal Link](https://github.com/) |
| 🐙 **GitHub API** | First-Party | 🐙 | ❌ No (SDK needed) | GitHub API authentication token. Free accounts have standard API rate limits (60 requests/hour unauthenticated). Authenticating using a Personal Access Token (GITHUB_TOKEN) increases the rate limit to 5,000 requests/hour (up to 15,000 requests/hour for GitHub Enterprise/marketplace accounts). Used for Skills Hub publishing and repository syncing. | `GitHub REST API`, `GitHub GraphQL API` | [Normal Link](https://github.com/settings/tokens) |
| ⚡ **Hermes Agent CLI** | First-Party | ⚡ | ❌ No (SDK needed) | Local command-line wrapper enabling background agent task runs, persistent environments, and pairing triggers. | *Not configured / Features listed below* | [Normal Link](https://github.com/) |
| 🧠 **Honcho** | First-Party | 🧠 | ❌ No (SDK needed) | AI-native persistent memory library for stateful agents (developed by Plastic Labs). Licensed under AGPL-3.0 and completely free to self-host locally or via Docker, with standard configuration overrides (HONCHO_BASE_URL). The managed cloud service (api.honcho.dev) offers a free trial of $100 in start credits to new organizations. | `Agent Memory Storage` | [Normal Link](https://honcho.dev/) |
| 🦙 **Ollama** | First-Party | 🦙 | ✅ Yes | Fully local and permanently free. Run model architectures like Llama, Qwen, Mistral, and Gemma on local CPU/GPU. | *Not configured / Features listed below* | [Normal Link](https://ollama.com/) |
| 🤖 **Qoder** | First-Party | 🤖 | ❌ No (SDK needed) | Local developer utility for AI assistance, code generation, and terminal integration. | *Not configured / Features listed below* | [Normal Link](https://qoder.io/) |
| 💬 **WaCLI** | First-Party | 💬 | ❌ No (SDK needed) | WhatsApp CLI tool for sending, syncing, and alerting messages directly from the server command-line. | *Not configured / Features listed below* | [Normal Link](https://github.com/topics/whatsapp-cli) |

## 📌 Browser-Based & Sandbox Tools

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit / Conditions | Key Models / Features | API Key / Referral Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🤖 **Browser-use** | First-Party | 🤖 | ❌ No (SDK needed) | Agent browser automation library and cloud platform. Core Python library is open-source (MIT License) and completely free to run locally (user pays for LLM tokens). Managed Browser Use Cloud offers browser hosting infrastructure; includes a free tier for individual testing and prototyping. Paid Developer/Business plans scale concurrency, proxy bandwidth, and runtime. | `Agentic Browser Navigation`, `Managed Chromium Nodes` | [Normal Link](https://browser-use.com/) |
| 🌐 **Browserbase** | First-Party | 🌐 | ❌ No (SDK needed) | Managed cloud browser platform for web scraping and AI agents. Free plan offers 1 hour (60 minutes) of concurrent browser session usage per month (max 15 mins/session, 1 concurrent browser, 7-day data retention). Developer plan is $20/month for 100 browser hours and 1 GB proxy bandwidth, with pay-as-you-go overage billing at $0.12/hour. | `Cloud Browser Session`, `Session Recording`, `Captcha Solver` | [Normal Link](https://www.browserbase.com/) |
| 🦊 **Camofox** | First-Party | 🦊 | ❌ No (SDK needed) | Open-source, headless anti-detection browser automation server designed for AI agents. Free to run and self-host locally or on own infrastructure (Docker/VPS) using the open-source Camoufox Firefox fork. Integrates with agents via local base URL overrides. Supports access security via custom CAMOFOX_API_KEY authentication tokens. | `Stealth Headless Firefox`, `Accessibility Snapshot API` | [Normal Link](https://github.com/camoufox/camoufox) |
| 🔍 **ChangeDetection.io** | First-Party | 🔍 | ❌ No (SDK needed) | Website monitoring and change detection service. Self-hosted version is free and open-source (MIT license). Managed Cloud SaaS subscription starts at $8.99/month for up to 5,000 URLs, including managed proxies and browser-based checks. | `Website Change Detection Engine (No LLM models hosted)` | [Normal Link](https://changedetection.io/) |
| 🌐 **Novita AI Sandbox Browser** | First-Party | 🌐 | ❌ No (SDK needed) | Secure runtime sandbox for multi-agent workloads. Offers $100 in free Sandbox credits to new users. Free tier limits session lengths to 1 hour, concurrency to 5, and resources to 2 vCPU + 4GB RAM. Paid tier (automatic upgrade when balance > $0) allows up to 24-hour sessions, 100 concurrent sandboxes, and up to 8 vCPU + 8GB RAM. | `DeepSeek-V4-Pro`, `Llama 3.3-70B`, `Qwen3-Max` (+2 more) | [Normal Link](https://novita.ai/products/sandbox) |

## 📌 Other Free API Resources

| Provider | Type | Region | OpenAI Compatible? | Quota / Rate Limit / Conditions | Key Models / Features | API Key / Referral Link |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🇺🇸 **Akamai Cloud** | Cloud Provider | 🇺🇸 | ❌ No (SDK needed) | Infrastructure provider. Does not offer a permanent free tier. Provides $100 in free credits to new customers, valid for 60 days (requires payment verification). Standard flat-rate billing applies afterwards: shared instances start at $5/month, dedicated instances start at $36-$50/month. | `NVIDIA RTX PRO 6000 Blackwell Server Edition (GPU)`, `NVIDIA RTX 4000 Ada Generation (GPU)`, `NVIDIA Quadro RTX 6000 (GPU)` | [Referral Link]() / [Normal Link](https://www.linode.com/) |
| 🇺🇸 **Azure Cloud** | Cloud Provider | 🇺🇸 | ❌ No (SDK needed) | Not configured yet. General Azure cloud $200 trial credits. | *Not configured / Features listed below* | [Normal Link](https://azure.microsoft.com/) |
| 🇺🇸 **DigitalOcean** | Cloud Provider | 🇺🇸 | ❌ No (SDK needed) | Offers a Free tier with basic GPU access, 5GB storage, 12-hour auto-shutdown, and public projects. Paid options include Pro subscription ($8/month, 15GB storage, mid-range GPUs) and Growth subscription ($39/month, 50GB storage, high-end GPUs like A100/H100). Hourly compute costs apply additionally while instances are active, billed per second and stopped when powered down. | `NVIDIA H100`, `NVIDIA A100`, `RTX A6000` (+3 more) | [Referral Link]() / [Normal Link](https://www.digitalocean.com/) |
| 🎨 **Fal.ai** | First-Party | 🎨 | ❌ No (SDK needed) | High-performance generative media (image/video/audio) API. No permanent free tier. New developer signups receive up to $20 in one-time free credits (especially for business domains) to test models in the Playground. Paid usage is pay-per-use (prepaid credit model, charged per generated image/video/second). Research grants program is available for open-source AI. | `FLUX.1 series`, `Stable Diffusion 3.5`, `Cosmos Video` | [Normal Link](https://fal.ai/) |
| 🖌️ **Krea** | First-Party | 🖌️ | ❌ No (SDK needed) | AI image and video generation platform. Web app offers a free plan with daily free credits (~50 generations/day). Developer API (via KREA_API_KEY) has no free tier and is billed independently via prepaid USD workspace balances on a per-generation cost model. | `Krea 2 Image Gen`, `Krea Video Gen` | [Normal Link](https://www.krea.ai/) |
| 📊 **Langfuse** | First-Party | 📊 | ❌ No (SDK needed) | Open-source LLM engineering, tracing, and observability platform. Cloud Hobby plan is permanently free, including up to 50,000 tracing units/month, 30 days data retention, and 2 users. Langfuse Cloud Pro is $199/month. Standard self-hosted version is fully open-source (MIT License) with no usage limits, though enterprise SSO/RBAC require commercial licensing. | `LLM Observability Traces`, `Prompt Management`, `Datasets & Evaluations` | [Normal Link](https://langfuse.com/) |
| 🇺🇸 **OpenInference** | Inference Provider | 🇺🇸 | ✅ Yes | Offers hosted model inference. Historically provides free rate-limited access for certain models (such as Qwen, Kimi, and DeepSeek, e.g., 500 prompts per day) for academic and research purposes. Paid API access is based on token consumption (e.g., Gemma 4 31B at $0.06/M input and $0.35/M output tokens; GPT-OSS 120B at $0.03/M input and $0.15/M output tokens). | `Gemma 4 (31B)`, `gpt-oss-120b`, `gpt-oss-20b` | [Normal Link](https://openinference.io/) |
| 🇺🇸 **Perceptron** | Inference Provider | 🇺🇸 | ✅ Yes | Flagship model Perceptron Mk1 can be tested for free via their demo app or integrations like Puter.js. Developers can sign up for API keys on platform.perceptron.inc. Direct API usage is billed on a pay-as-you-go token basis: $0.15 per million input tokens ($0.15/MT) and $1.50 per million output tokens ($1.50/MT). | `Perceptron Mk1` | [Normal Link](https://perceptron.ai/) |
| 🌐 **Phala** | Inference Provider | 🌐 | ✅ Yes | Decentralized confidential computing network. Agent Contracts can be deployed and hosted for free with no gas fees (dstack SDK is free). For Phala Cloud (Confidential VMs/GPU TEEs), new verified users may receive $20 in free credits, after which computing resources are billed on a pay-as-you-go basis (per-minute billing for instance types and $0.000139/GB/hour for storage). | `Llama 3.1`, `Qwen`, `DeepSeek` (+3 more) | [Normal Link](https://phala.network/) |
| 🇺🇸 **Relace** | Inference Provider | 🇺🇸 | ✅ Yes | Provides developer infrastructure for autonomous coding agents. Offers a free tier with rate limits (e.g., 3 calls per minute) for testing and small projects. Paid plans are usage-based or tiered (token-based pricing for individual models) designed to scale with team size. | `Relace Apply 3`, `Instant Apply`, `Relace Search` | [Normal Link](https://relace.co/) |
| 🇺🇸 **Switchpoint** | Inference Provider | 🇺🇸 | ✅ Yes | Intelligent LLM routing service. Offers a free trial with small signup credits for new developer accounts. Paid options include a Pay-As-You-Go Developer Plan (using top-up credits based on routed models) and a flat-rate Stable Tier ($1.05/M input and $4.25/M output tokens). | `GPT-4o (Routed)`, `Claude 3.5 Sonnet (Routed)`, `Llama 3.1 (Routed)` | [Normal Link](https://switchpoint.ai/) |
| 🇺🇸 **Wafer** | Inference Provider | 🇺🇸 | ✅ Yes | Optimized AI performance engineering and inference platform. Does not offer a traditional free tier. Provides flat-rate subscription passes: Starter (~$10/week for 1,000 requests every 5 hours) and Privacy (~$25/week for 2,000 requests every 5 hours with zero data retention). Also offers pay-as-you-go serverless billing for enterprise accounts. | `Qwen 3.5 397B-A17B`, `GLM-5.1`, `Kimi-K2.6` | [Normal Link](https://wafer.ai/) |
| 🇺🇸 **Weights & Biases** | Cloud Provider | 🇺🇸 | ❌ No (SDK needed) | W&B is an MLOps platform (not a model hosting provider). Free tier for personal or academic use offers unlimited experiments and tracked hours, and 5 GB of artifact storage. Paid options: Pro and Enterprise plans for team collaboration and commercial use. | `Integrates with Llama`, `Integrates with GPT`, `Integrates with Claude` (+1 more) | [Normal Link](https://wandb.ai/) |
| 🌐 **io.net** | Inference Provider | 🌐 | ✅ Yes | No traditional free tier. Offers subscription plans that include monthly usage credits: Professional Plan ($15/mo in credits for light workloads, refreshes daily) and Developer Plan ($150/mo in credits with ~10% discount, refreshes every 8 hours). Beyond credits, usage is pay-as-you-go billed via $IO tokens or credit cards. | `Llama-3.3-70B-Instruct`, `Custom Docker Container Deployments` | [Normal Link](https://io.net/) |

## 🌐 OpenRouter Dynamic Free Models

*OpenRouter dynamically updates its free model catalogue. Current free text-models (26 models detected on 2026-07-03 10:00:59):*

| Model ID | Context Window | Description |
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
| `poolside/laguna-m.1:free` | 262K | Laguna M.1 is the flagship coding agent model from [Poolside](https://poolside.ai/), optimized for c... |
| `poolside/laguna-xs-2.1:free` | 262K | Laguna XS 2.1 is the latest coding agent model in the 33B-A3B category from [Poolside](https://pools... |
| `poolside/laguna-xs.2:free` | 262K | Laguna XS.2 is the second-generation model in the XS size class from [Poolside](https://poolside.ai/... |
| `qwen/qwen3-coder:free` | 1048K | Qwen3-Coder-480B-A35B-Instruct is a Mixture-of-Experts (MoE) code generation model developed by the ... |
| `qwen/qwen3-next-80b-a3b-instruct:free` | 262K | Qwen3-Next-80B-A3B-Instruct is an instruction-tuned chat model in the Qwen3-Next series optimized fo... |

## Detailed Provider Profiles & Conditions

### 🇮🇱 AI21
- **Normal Link**: [Link](https://www.ai21.com/)
- **OpenAI Base URL**: `https://api.ai21.com/studio/v1`
- **Rules & Conditions**: Offers a free trial of $10 in credits valid for three months upon account creation. No permanent free tier. Once credits are exhausted or expired, users must transition to a paid plan. Commercial API access is usage-based (pay-as-you-go). Model usage via third-party cloud providers (AWS Bedrock, Azure) is governed by their respective rates.
- **Supported Models / Features**:
  - `Jamba 1.5 Large`
  - `Jamba 1.5 Mini`
  - `Jamba 1.6`

### 🇮🇱 AionLabs
- **Normal Link**: [Link](https://www.aionlabs.ai/)
- **OpenAI Base URL**: `https://api.aionlabs.ai/v1`
- **Rules & Conditions**: Offers a free tier with a recurring daily credit allowance (approx. 20,000 tokens per day) for testing agent jobs, APIs, and browser chat with no credit card required. Paid options include Prepaid (pay-as-you-go) and monthly Business plans. API is OpenAI-compatible and can also be accessed via Puter.js.
- **Supported Models / Features**:
  - `Aion-2.0`
  - `Aion-1.0`
  - `Aion-1.0-Mini`

### 🇺🇸 Akamai Cloud
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://www.linode.com/)
- **Rules & Conditions**: Infrastructure provider. Does not offer a permanent free tier. Provides $100 in free credits to new customers, valid for 60 days (requires payment verification). Standard flat-rate billing applies afterwards: shared instances start at $5/month, dedicated instances start at $36-$50/month.
- **Supported Models / Features**:
  - `NVIDIA RTX PRO 6000 Blackwell Server Edition (GPU)`
  - `NVIDIA RTX 4000 Ada Generation (GPU)`
  - `NVIDIA Quadro RTX 6000 (GPU)`

### 🌐 AkashML
- **Normal Link**: [Link](https://akash.network/)
- **Rules & Conditions**: New users of the AkashML managed inference service receive $100 in free AI token credits for both playground and API usage. Additionally, the Akash Console for self-hosted container deployments offers a $100 free trial (requires credit card for verification, 24h limit per instance). Paid options are pay-per-use, operating as a decentralized marketplace with reverse auctions resulting in 60-85% savings compared to standard cloud providers.
- **Supported Models / Features**:
  - `Llama 3.3 70B`
  - `DeepSeek V4 Flash`
  - `DeepSeek V3.2`
  - `Qwen 3.6 35B A3B`

### 🇨🇳 Alibaba Cloud Int.
- **Normal Link**: [Link](https://www.alibabacloud.com/)
- **Rules & Conditions**: Provides DashScope / Model Studio developer APIs and AI Coding Plans. New users receive a free token quota valid for 90 days (Singapore region only, sk- keys). Standard DashScope API is pay-as-you-go based on token usage. The AI Coding Plan is a fixed-price monthly subscription (Lite/Pro, sk-sp- keys) providing flat-rate prompt limits instead of token billing.
- **Supported Models / Features**:
  - `Qwen3.7-Max`
  - `Qwen3.7-Plus`
  - `Qwen3.6-Plus`
  - `Qwen-Max`
  - `Qwen-Turbo`
  - `Wan 2.7`

### 🇺🇸 Amazon Bedrock
- **Normal Link**: [Link](https://aws.amazon.com/bedrock/)
- **Rules & Conditions**: No permanent free tier. New AWS accounts receive up to $200 in promotional credits ($100 at signup, $100 via guided tasks) valid for 6 months. Startup programs offer $1,000 to $300,000+ in credits. Paid options: On-Demand pay-as-you-go per 1M tokens, Batch Inference (approx. 50% discount), and Provisioned Throughput (dedicated capacity billing).
- **Supported Models / Features**:
  - `Anthropic Claude 3.5 Sonnet`
  - `Meta Llama 3.3`
  - `Amazon Titan`

### 🇺🇸 Anthropic
- **Normal Link**: [Link](https://console.anthropic.com/)
- **Rules & Conditions**: Claude.ai interactive chat offers a permanent free tier with usage limits capped on a rolling 5-hour window. The developer API has no permanent free tier but provides a small one-time starter credit upon account creation. Paid options include Claude.ai Pro ($20/month) and consumption-based developer API billing. The CLAUDE_CODE_OAUTH_TOKEN environment variable can be used to authenticate coding tasks via Anthropic's OAuth device flow.
- **Supported Models / Features**:
  - `Claude 4.6 Sonnet`
  - `Claude 4.7 Opus`
  - `Claude 4.5 Haiku`

### 🇺🇸 Arcee AI
- **Normal Link**: [Link](https://www.arcee.ai/)
- **Rules & Conditions**: Does not offer a traditional permanent free tier for its commercial API. However, the Trinity Builders Program offers free inference access for approved developer, research, and open-source projects. Otherwise, commercial API is pay-as-you-go (e.g., Trinity-Mini at ~$0.045/1M input tokens and ~$0.15/1M output tokens). Models are open-weight and can be downloaded for free local deployment.
- **Supported Models / Features**:
  - `Trinity-Large-Thinking`
  - `Trinity-Large-Preview`
  - `Trinity-Mini`
  - `Trinity-Nano`

### 🇺🇸 AssemblyAI API
- **Normal Link**: [Link](https://www.assemblyai.com/)
- **Rules & Conditions**: Free tier includes up to 185 hours of batch transcription and 333 hours of streaming transcription (no credit card required). Startup program offers up to 200,000 hours of free credits. Billed under a pay-as-you-go model for additional usage, with core transcription rates and extra add-ons (Diarization, sentiment, LeMUR LLM analysis).
- **Supported Models / Features**:
  - `Universal-3 Pro`
  - `Universal-1`
  - `Universal-3 Pro Streaming`
  - `LeMUR (Framework)`

### 🇺🇸 AtlasCloud
- **Normal Link**: [Link](https://atlascloud.io/)
- **Rules & Conditions**: Provides a unified API to access over 300 models on a pay-as-you-go consumption model (e.g., DeepSeek V3 at $0.07/1M tokens). GPU Cloud instances start around $2.95/hr with per-second billing. Standard developer subscriptions are currently noted as unavailable, and evaluation credits/promotions vary dynamically within the console.
- **Supported Models / Features**:
  - `DeepSeek V3`
  - `Kling`
  - `Seedance`
  - `Flux`

### 🇺🇸 Azure
- **Normal Link**: [Link](https://azure.microsoft.com/)
- **Rules & Conditions**: Offers $200 free credits for the first 30 days, 12 months of popular free services, and 65+ always-free services (subject to monthly limits) for new accounts. Unused credits expire and require manual upgrade to Pay-As-You-Go. Azure for Students offers $100 credits without credit card verification.
- **Supported Models / Features**:
  - `GPT-5.5 (Azure OpenAI)`
  - `GPT-5.4 (Azure OpenAI)`
  - `Llama (Foundry)`
  - `Claude (Foundry)`
  - `DeepSeek (Foundry)`

### 🇺🇸 Azure Cloud
- **Normal Link**: [Link](https://azure.microsoft.com/)
- **Rules & Conditions**: Not configured yet. General Azure cloud $200 trial credits.

### 🇨🇳 Baidu Qianfan
- **Normal Link**: [Link](https://cloud.baidu.com/product/wenxin.html)
- **Rules & Conditions**: Offers permanently free access to select lightweight models like ERNIE-3.5-8K and ERNIE-Speed-8K. Premium models like ERNIE-4.0-8K include introductory trial quotas (e.g., 1M free tokens in the first month). Paid options include pay-per-token consumption for proprietary ERNIE models and third-party models, as well as a paid 'Coding Plan' subscription for developer tools.
- **Supported Models / Features**:
  - `ERNIE 5.1`
  - `ERNIE-4.0-8K`
  - `ERNIE-3.5-8K`
  - `ERNIE-Speed-8K`

### 🇺🇸 Baseten
- **Normal Link**: [Link](https://www.baseten.co/)
- **OpenAI Base URL**: `https://bridge.baseten.co/v1`
- **Rules & Conditions**: No permanent free tier. New workspaces receive $30 in free trial credits. Startup programs offer up to $25,000 for dedicated deployments and $2,500 for model APIs. Paid options are usage-based on a per-replica-hour or per-token basis with scale-to-zero capabilities to eliminate idle costs.
- **Supported Models / Features**:
  - `Meta Llama 3`
  - `Mistral`
  - `Whisper`
  - `Stable Diffusion`

### 📰 BlogWatcher CLI
- **Normal Link**: [Link](https://github.com/)
- **Rules & Conditions**: Command-line tool to register, track, scan, and notify new blog and RSS feed updates on the fly.

### 🇺🇸 Brave Search API
- **Normal Link**: [Link](https://brave.com/search/api/)
- **Rules & Conditions**: Metered pricing model. Automatically provides $5 in free credits every month, covering approximately 1,000 free requests/month. The standard Search Plan is priced at $5 per 1,000 requests (includes Web, News, Images, LLM context). Answers Plan is priced at $4 per 1,000 queries plus token costs.
- **Supported Models / Features**:
  - `Search API (No custom LLM models hosted)`

### 🤖 Browser-use
- **Normal Link**: [Link](https://browser-use.com/)
- **Rules & Conditions**: Agent browser automation library and cloud platform. Core Python library is open-source (MIT License) and completely free to run locally (user pays for LLM tokens). Managed Browser Use Cloud offers browser hosting infrastructure; includes a free tier for individual testing and prototyping. Paid Developer/Business plans scale concurrency, proxy bandwidth, and runtime.
- **Supported Models / Features**:
  - `Agentic Browser Navigation`
  - `Managed Chromium Nodes`

### 🌐 Browserbase
- **Normal Link**: [Link](https://www.browserbase.com/)
- **Rules & Conditions**: Managed cloud browser platform for web scraping and AI agents. Free plan offers 1 hour (60 minutes) of concurrent browser session usage per month (max 15 mins/session, 1 concurrent browser, 7-day data retention). Developer plan is $20/month for 100 browser hours and 1 GB proxy bandwidth, with pay-as-you-go overage billing at $0.12/hour.
- **Supported Models / Features**:
  - `Cloud Browser Session`
  - `Session Recording`
  - `Captcha Solver`

### 🦊 Camofox
- **Normal Link**: [Link](https://github.com/camoufox/camoufox)
- **Rules & Conditions**: Open-source, headless anti-detection browser automation server designed for AI agents. Free to run and self-host locally or on own infrastructure (Docker/VPS) using the open-source Camoufox Firefox fork. Integrates with agents via local base URL overrides. Supports access security via custom CAMOFOX_API_KEY authentication tokens.
- **Supported Models / Features**:
  - `Stealth Headless Firefox`
  - `Accessibility Snapshot API`

### 🇺🇸 Cerebras
- **Normal Link**: [Link](https://cloud.cerebras.ai/)
- **OpenAI Base URL**: `https://api.cerebras.ai/v1`
- **Rules & Conditions**: Generous free tier offering 1,000,000 free tokens per day (no credit card required). Paid options: Developer Tier (pre-paid starting at $10) with 10x higher rate limits and priority processing; Enterprise Tier with custom pricing for dedicated hosting and support.
- **Supported Models / Features**:
  - `Llama 3.3`
  - `Llama 3.1 70B`
  - `Llama 4 Scout`
  - `Qwen 2.5 72B`

### 🔍 ChangeDetection.io
- **Normal Link**: [Link](https://changedetection.io/)
- **Rules & Conditions**: Website monitoring and change detection service. Self-hosted version is free and open-source (MIT license). Managed Cloud SaaS subscription starts at $8.99/month for up to 5,000 URLs, including managed proxies and browser-based checks.
- **Supported Models / Features**:
  - `Website Change Detection Engine (No LLM models hosted)`

### 🇺🇸 Chutes
- **Normal Link**: [Link](https://chutes.ai/)
- **Rules & Conditions**: No longer offers a free tier as of March 15, 2026. Operates under a pay-as-you-go (PAYGO) model for token inference and hourly private GPU deployments. Optional paid monthly subscription plans, Plus ($10/month) and Pro ($20/month), provide daily request quotas and a 6-10% discount on excess PAYGO usage. Startup credits (up to $10,000) are available for qualifying companies.
- **Supported Models / Features**:
  - `DeepSeek-R1`
  - `DeepSeek-V3.2-TEE`
  - `Mistral-Nemo-Instruct-2407`
  - `FLUX.1 [dev]`
  - `FLUX.1-schnell`

### 🇺🇸 Clarifai
- **Normal Link**: [Link](https://www.clarifai.com/)
- **Rules & Conditions**: Has transitioned from tier-based subscriptions to a credits-based Pay-As-You-Go model. New users can receive a one-time $5 welcome bonus (valid for 30 days) upon phone verification to test serverless API calls and custom deployments. Paid access requires purchasing additional credits to top up the account balance.
- **Supported Models / Features**:
  - `general-image-recognition`
  - `DeepSeek-V3_2`
  - `Llama-3_2-3B-Instruct`
  - `gpt-oss-20b`

### 🇺🇸 Cloudflare
- **Normal Link**: [Link](https://dash.cloudflare.com/)
- **OpenAI Base URL**: `https://api.cloudflare.com/client/v4/accounts/{account_id}/ai/run`
- **Rules & Conditions**: Free tier provides a daily allocation of 10,000 Neurons across all accounts. Paid options: Workers Paid plan starts at $5/month, and usage beyond the daily free allocation is billed at $0.011 per 1,000 Neurons.
- **Supported Models / Features**:
  - `@cf/meta/llama-3.1-8b-instruct`
  - `@cf/mistral/mistral-7b-instruct-v0.2`
  - `@cf/stabilityai/stable-diffusion-xl-base-1.0`

### 🇨🇦 Cohere
- **Normal Link**: [Link](https://dashboard.cohere.com/api-keys)
- **OpenAI Base URL**: `https://api.cohere.com/v2`
- **Rules & Conditions**: Offers a free Evaluation (Trial) tier for developers with a rate-limited trial API key (1,000 API calls/month, 20 requests/minute). Paid options include the Production Tier with pay-as-you-go billing based on token usage (e.g., 500 RPM limit) and Enterprise agreements for dedicated hosting or custom SLA needs.
- **Supported Models / Features**:
  - `Command A+`
  - `Command R`
  - `Command R7B`
  - `Embed v4`
  - `Rerank v3.5`
  - `North Mini Code`

### 🇮🇱 Decart
- **Normal Link**: [Link](https://www.decart.ai/)
- **Rules & Conditions**: Operates on a pay-as-you-go model with no monthly subscription fees. New accounts receive free trial credits to test the API and models. Paid options are charged based on execution metrics: realtime models are billed per second of active generation (e.g., Lucy 2.1 at ~$0.02/sec), video models per second generated, and image models per generation.
- **Supported Models / Features**:
  - `Lucy 2.1`
  - `Lucy Image 2`
  - `Oasis 3`

### 🇺🇸 DeepInfra
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://deepinfra.com/)
- **OpenAI Base URL**: `https://api.deepinfra.com/v1/openai`
- **Rules & Conditions**: Does not offer a formal subscription-based free tier. However, users can perform unauthenticated testing of models with an empty api_key (rate-limited by IP address). Signing up can sometimes grant temporary token allotments. Paid options are strictly pay-as-you-go based on token usage (e.g., starting at ~$0.02/1M tokens) or execution time for non-LLMs. Cached tokens are discounted (e.g., ~$0.145/1M tokens).
- **Supported Models / Features**:
  - `Llama 3.3`
  - `DeepSeek-V4-Pro`
  - `gemini-3.5-flash`
  - `FLUX`
  - `Cosmos 3`

### 🇨🇳 DeepSeek
- **Normal Link**: [Link](https://platform.deepseek.com/)
- **OpenAI Base URL**: `https://api.deepseek.com`
- **Rules & Conditions**: The web chat interface (chat.deepseek.com) is permanently free. The API does not have an ongoing free tier but offers 5 million free trial tokens for new developer accounts. Paid options follow a pay-as-you-go model: DeepSeek V4-Flash is priced at $0.14/1M input and $0.28/1M output tokens, and DeepSeek V4-Pro is priced at $0.435/1M input and $0.87/1M output tokens. Significant discounts are offered for cache hits.
- **Supported Models / Features**:
  - `DeepSeek V4-Flash`
  - `DeepSeek V4-Pro`

### 🇺🇸 Deepgram API
- **Normal Link**: [Link](https://deepgram.com/)
- **Rules & Conditions**: Billed by usage (per-second billing). New users receive $200 in one-time free credits (approx. 12,000 minutes of transcription). Startup program provides up to $100,000 in credits over 12 months. Paid plans: Pay-As-You-Go, Growth (discounted rates with annual commitment), and Enterprise (custom rates/self-hosting). STT rates start at ~$0.0077/min, TTS starts at ~$0.015/1k characters, Voice Agent is ~$4.50/hour.
- **Supported Models / Features**:
  - `Nova-3 (STT)`
  - `Flux (Conversational STT)`
  - `Aura-2 (TTS)`

### 🇺🇸 DigitalOcean
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://www.digitalocean.com/)
- **Rules & Conditions**: Offers a Free tier with basic GPU access, 5GB storage, 12-hour auto-shutdown, and public projects. Paid options include Pro subscription ($8/month, 15GB storage, mid-range GPUs) and Growth subscription ($39/month, 50GB storage, high-end GPUs like A100/H100). Hourly compute costs apply additionally while instances are active, billed per second and stopped when powered down.
- **Supported Models / Features**:
  - `NVIDIA H100`
  - `NVIDIA A100`
  - `RTX A6000`
  - `RTX A5000`
  - `RTX A4000`
  - `Tesla V100`

### 🗣️ ElevenLabs
- **Normal Link**: [Link](https://elevenlabs.io/)
- **Rules & Conditions**: Premium AI speech synthesis and voice cloning. Free tier provides 10,000 characters/month (refreshes monthly) for personal use, limited to standard voices. Starter plan is $5/month ($1 first month, 30,000 characters, instant voice cloning). Paid plans range up to $330/month (Scale). Scribe STT offers a usage-based tier.
- **Supported Models / Features**:
  - `Multilingual v2 (TTS)`
  - `Turbo v2.5 (TTS)`
  - `Scribe (STT)`
  - `Instant Voice Cloning`

### 🔍 Exa
- **Normal Link**: [Link](https://exa.ai/)
- **Rules & Conditions**: AI-native web search and content extraction engine. Free tier provides 1,000 free search queries/month for developer accounts (resets monthly, no credit card required). Paid plan starts at $20/month (includes 10,000 queries, overages at $0.002/query). Enterprise plans offer custom limits and dedicated endpoints. Includes search, contents/scraping, and similarity endpoints.
- **Supported Models / Features**:
  - `Search API`
  - `Extract API`
  - `Similarity API`

### 🎨 Fal.ai
- **Normal Link**: [Link](https://fal.ai/)
- **Rules & Conditions**: High-performance generative media (image/video/audio) API. No permanent free tier. New developer signups receive up to $20 in one-time free credits (especially for business domains) to test models in the Playground. Paid usage is pay-per-use (prepaid credit model, charged per generated image/video/second). Research grants program is available for open-source AI.
- **Supported Models / Features**:
  - `FLUX.1 series`
  - `Stable Diffusion 3.5`
  - `Cosmos Video`

### 🔥 Firecrawl
- **Normal Link**: [Link](https://www.firecrawl.dev/)
- **Rules & Conditions**: Web scraping, crawling, and AI-powered extraction API. Free tier provides 500 to 1,000 credits/month (no credit card required) for evaluation. Paid plans start at $19/month (Hobby, 3,000 credits) to $599/month (Scale). Operations consume credits based on complexity (e.g. AI extract/stealth proxies cost more). Also available as a free self-hosted open-source version (Docker Compose) with custom FIRECRAWL_API_URL environment overrides.
- **Supported Models / Features**:
  - `Scraping API`
  - `Crawling API`
  - `AI Extraction API`

### 🇺🇸 Fireworks
- **Normal Link**: [Link](https://fireworks.ai/)
- **OpenAI Base URL**: `https://api.fireworks.ai/inference/v1`
- **Rules & Conditions**: No permanent free tier. Offers $1 in free starter credits for new signups. Paid options: Serverless pay-per-token pricing based on model size (sub-4B: $0.10/1M tokens, 4B-16B: $0.20/1M tokens, 16B+: $0.90/1M tokens). Offers 50% discount for cached input tokens and batch inference.
- **Supported Models / Features**:
  - `Llama 3.3`
  - `Qwen 2.5`
  - `DeepSeek-V3`
  - `Stable Diffusion`

### 🇰🇷 Friendli
- **Normal Link**: [Link](https://friendli.ai/)
- **Rules & Conditions**: No permanent free plan. Offers substantial startup/promotional GPU inference credits ranging from $10,000 up to $50,000 to help teams scale. Otherwise uses usage-based pay-as-you-go pricing optimized for high-throughput production workloads.
- **Supported Models / Features**:
  - `Llama 3.1`
  - `Gemma 2`
  - `Mistral`
  - `Qwen 2`

### 🇺🇸 GMI Cloud
- **Normal Link**: [Link](https://gmicloud.com/)
- **OpenAI Base URL**: `https://api.gmicloud.ai/v1`
- **Rules & Conditions**: High-performance GPU cloud. No public permanent free tier. Offers free access to specific model endpoints (e.g. Llama 3.3, DeepSeek R1) for inference on the Model Hub dashboard. Paid options use a pay-as-you-go model with transparent pricing based on GPU hardware (e.g. NVIDIA H100, B200) and service type.
- **Supported Models / Features**:
  - `DeepSeek`
  - `Llama`
  - `Qwen`
  - `Flux`

### 🐙 GitHub API
- **Normal Link**: [Link](https://github.com/settings/tokens)
- **Rules & Conditions**: GitHub API authentication token. Free accounts have standard API rate limits (60 requests/hour unauthenticated). Authenticating using a Personal Access Token (GITHUB_TOKEN) increases the rate limit to 5,000 requests/hour (up to 15,000 requests/hour for GitHub Enterprise/marketplace accounts). Used for Skills Hub publishing and repository syncing.
- **Supported Models / Features**:
  - `GitHub REST API`
  - `GitHub GraphQL API`

### 🇺🇸 Google AI Studio
- **Normal Link**: [Link](https://aistudio.google.com/app/apikey)
- **Rules & Conditions**: Free tier available for the Gemini Developer API on non-billing-enabled projects, subject to RPM, TPM, and RPD rate limits (data may be used for model training). Access to Pro models on the free tier was restricted starting April 1, 2026. Enabling billing removes the free tier and transitions the project to pay-as-you-go pricing (prepaid billing for new users, with mandatory spend caps and context caching discounts).
- **Supported Models / Features**:
  - `Gemini 1.5 Flash`
  - `Gemini 1.5 Pro`
  - `Gemini 2.5`
  - `Gemini 3.1`

### 🇺🇸 Google Custom Search JSON API
- **Normal Link**: [Link](https://developers.google.com/custom-search/v1/overview)
- **Rules & Conditions**: Closed to new signups. The API is in a sunset phase and will be fully discontinued on January 1, 2027. For existing customers, the free tier provides 100 queries/day. Additional queries cost $5 per 1,000 requests, up to a daily limit of 10,000 queries.
- **Supported Models / Features**:
  - `Custom Search API (No LLM models hosted)`

### 🇺🇸 Google Vertex
- **Normal Link**: [Link](https://cloud.google.com/vertex-ai)
- **Rules & Conditions**: No permanent free tier. New Google Cloud accounts receive $300 in free credits valid for 90 days. Vertex AI Express Mode offers limited free access hours or agent engines in a 90-day window. Paid options are pay-as-you-go. (Google AI Studio provides a separate, rate-limited free tier for developer prototyping).
- **Supported Models / Features**:
  - `Gemini 1.5 Pro`
  - `Gemini 1.5 Flash`
  - `Imagen 3`
  - `Claude 3.5 Sonnet`

### 🇺🇸 Groq
- **Normal Link**: [Link](https://console.groq.com/keys)
- **OpenAI Base URL**: `https://api.groq.com/openai/v1`
- **Rules & Conditions**: Offers an always-free API tier (no credit card required) subject to organization-level rate limits (e.g., 30 RPM, 30,000 TPM, 14,400 RPD). Paid Developer Tier (pay-as-you-go) provides up to 10x higher rate limits, with input costs starting at $0.05/1M tokens (Llama 3.1 8B) up to $0.59 input / $0.79 output per 1M tokens (Llama 3.3 70B), plus a 50% discount for Batch API and prompt caching.
- **Supported Models / Features**:
  - `Llama 3.1 8B`
  - `Llama 3.3 70B`
  - `Mixtral`
  - `Qwen`
  - `DeepSeek`

### ⚡ Hermes Agent CLI
- **Normal Link**: [Link](https://github.com/)
- **Rules & Conditions**: Local command-line wrapper enabling background agent task runs, persistent environments, and pairing triggers.

### 🧠 Honcho
- **Normal Link**: [Link](https://honcho.dev/)
- **Rules & Conditions**: AI-native persistent memory library for stateful agents (developed by Plastic Labs). Licensed under AGPL-3.0 and completely free to self-host locally or via Docker, with standard configuration overrides (HONCHO_BASE_URL). The managed cloud service (api.honcho.dev) offers a free trial of $100 in start credits to new organizations.
- **Supported Models / Features**:
  - `Agent Memory Storage`

### 🇦🇪 Inception
- **Normal Link**: [Link](https://www.g42.ai/)
- **Rules & Conditions**: Provides 10 million free tokens upon account creation to test and prototype. OpenAI-compatible API operates on usage-based pricing with customizable user-defined billing limits and email alerts to block overages.
- **Supported Models / Features**:
  - `Mercury 2`
  - `Mercury Edit 2`
  - `JAIS`

### 🇺🇸 Inceptron
- **Normal Link**: [Link](https://inceptron.com/)
- **Rules & Conditions**: No direct free tier. Operates strictly on consumption-based pricing designed for EU data sovereignty. Access is typically provided through third-party gateways (e.g., Kilo.ai or Requesty) using per-million-token pay-as-you-go billing (e.g., $0.15/1M input tokens for MiniMax M2.5). Custom pricing is available for startups and enterprises.
- **Supported Models / Features**:
  - `MiniMax M2.5`
  - `Kimi K2.6`
  - `GLM 5.1`

### 🇺🇸 Infermatic
- **Normal Link**: [Link](https://infermatic.ai/)
- **Rules & Conditions**: Structured around flat-rate subscription tiers rather than token-based billing. Includes a Free Plan ($0/mo for select models like Rocinante-12B), Essential Tier ($9/mo), Standard Tier ($16/mo), and Plus Tier ($20/mo for unrestricted prompts/results, zero-logs policy, and advanced models).
- **Supported Models / Features**:
  - `Rocinante-12B-v1.1`
  - `Fallen Llama 3.3`
  - `Strawberrylemonade L3`
  - `Magnum v4`
  - `Qwen series`

### 🇺🇸 Inflection
- **Normal Link**: [Link](https://inflection.ai/)
- **Rules & Conditions**: The Pi consumer personal assistant app is completely free with no usage limits or premium tiers. The developer API operates on usage-based pricing (e.g., Inflection-3 billed at approx. $2.50 per million input tokens and $10.00 per million output tokens) with custom enterprise options.
- **Supported Models / Features**:
  - `Inflection-3`
  - `Inflection-2.5`
  - `Pi`

### 💻 Kilocode
- **Normal Link**: [Link](https://kilo.ai/)
- **Rules & Conditions**: AI-native gateway and assistant platform. Auto Free Tier routes to free models (e.g., Llama 3.1 8B, Qwen 2.5 7B) through Kilo Gateway. Supports Bring Your Own Key (BYOK) to route to user's OpenAI, Anthropic, or Gemini keys for free or paid usage. Paid Kilo Pass subscriptions start at $19/month (Starter) to $199/month (Expert) for hosted model credits.
- **Supported Models / Features**:
  - `kilo-free`
  - `Llama series`
  - `Qwen series`

### 🖌️ Krea
- **Normal Link**: [Link](https://www.krea.ai/)
- **Rules & Conditions**: AI image and video generation platform. Web app offers a free plan with daily free credits (~50 generations/day). Developer API (via KREA_API_KEY) has no free tier and is billed independently via prepaid USD workspace balances on a per-generation cost model.
- **Supported Models / Features**:
  - `Krea 2 Image Gen`
  - `Krea Video Gen`

### 📊 Langfuse
- **Normal Link**: [Link](https://langfuse.com/)
- **Rules & Conditions**: Open-source LLM engineering, tracing, and observability platform. Cloud Hobby plan is permanently free, including up to 50,000 tracing units/month, 30 days data retention, and 2 users. Langfuse Cloud Pro is $199/month. Standard self-hosted version is fully open-source (MIT License) with no usage limits, though enterprise SSO/RBAC require commercial licensing.
- **Supported Models / Features**:
  - `LLM Observability Traces`
  - `Prompt Management`
  - `Datasets & Evaluations`

### 🇺🇸 Liquid
- **Normal Link**: [Link](https://www.liquid.ai/)
- **Rules & Conditions**: Free self-service open access to download, customize, and deploy models (via Hugging Face or LEAP platform) under the LFM Open License v1.0, which has a commercial use threshold: free for companies under $10 million in annual revenue; companies above this must purchase a commercial license. Liquid Apollo is also free for mobile devices. Enterprise tiers offer custom agreements.
- **Supported Models / Features**:
  - `LFM-1B`
  - `LFM-3B`
  - `LFM-40B`
  - `LFM2/LFM2.5 series`

### 🌐 Mancer
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://mancer.tech/)
- **Rules & Conditions**: No monthly subscription free tier. Provides access to select 'free models' for initial testing. Otherwise uses a pay-as-you-go system with credit packs ranging from $4.99 (~1.25M credits) to $249.99 (~100M credits). No subscription lock-in. A 25% token discount is available if users opt into Anonymous Logging (data sharing for training).
- **Supported Models / Features**:
  - `Weaver (alpha)`
  - `Magnum v4 72B`
  - `ReMM SLERP 13B`
  - `MythoMax 13B`

### 🇨🇳 MiniMax
- **Normal Link**: [Link](https://platform.minimaxi.com/)
- **OpenAI Base URL**: `https://api.minimax.chat/v1`
- **Rules & Conditions**: No permanent free tier. Provides limited trial credits to new developer accounts for testing. Paid options: Token Plan (monthly subscription starting at $10/month) or Pay-as-you-go (token packages starting at $5 for 5,000 credits). Standard rates for flagship models are typically around $0.30-$0.50/1M input tokens and $1.00-$1.20/1M output tokens.
- **Supported Models / Features**:
  - `MiniMax-M3`
  - `MiniMax-M2.7`
  - `MiniMax-M2.5`
  - `Hailuo Video`

### 🇫🇷 Mistral
- **Normal Link**: [Link](https://console.mistral.ai/api-keys)
- **OpenAI Base URL**: `https://api.mistral.ai/v1`
- **Rules & Conditions**: API (La Plateforme) offers a permanent Free Tier for evaluation and prototyping, subject to strict rate limits (e.g., 1 request/second global limit). Paid options: Scale plan (pay-as-you-go). Startup programs provide up to $30,000 in credits. Le Chat consumer chat service offers a free plan capped at ~25 messages/day and a Pro plan at $14.99/month.
- **Supported Models / Features**:
  - `Mistral Medium 3.5`
  - `Mistral Small 4`
  - `Mistral Large 3`
  - `Codestral`

### 🤖 Mistral API (Voxtral)
- **Normal Link**: [Link](https://console.mistral.ai/)
- **Rules & Conditions**: Hermes audio integration using Mistral's Voxtral speech-to-text and text-to-speech engine. Billed under the standard Mistral API billing structure (La Plateforme). STT and TTS are billed based on usage (characters synthesized or minutes transcribed).
- **Supported Models / Features**:
  - `mistral-embed`
  - `voxtral-stt`
  - `voxtral-tts`

### 🇨🇳 Moonshot AI
- **Normal Link**: [Link](https://platform.moonshot.cn/)
- **Rules & Conditions**: Kimi chat interface is free for casual users with query volume and context limits. Pro features (Agent Swarm, Deep Research) are available via monthly subscriptions: Moderato (~$19/mo), Allegretto, and Vivace (up to $199/mo). Developer API is pay-as-you-go ($0.55-$0.95 per million input, $2.50-$4.00 per million output tokens) with automatic context caching. Open-weight versions of Kimi K2 models are free to self-host.
- **Supported Models / Features**:
  - `Kimi K2.6`
  - `Kimi K2.7`
  - `Moonshot-v1`

### 🇺🇸 Morph
- **Normal Link**: [Link](https://www.morph.so/)
- **Rules & Conditions**: Includes Morph LLM (developer assistant) which offers a free tier of 200 requests/month, and Morph Studio (video/image generation) which offers a free plan of 75 credits/month. Paid options: Morph LLM features Starter, Pro, and Scale plans with per-token billing (e.g., $0.80-$0.90/1M input tokens). Morph Studio plans start at ~$10/month (or $7/month billed annually) for 3,000 credits.
- **Supported Models / Features**:
  - `Morph V3 Fast`
  - `Morph V3 Large`
  - `Morph-Video-1`
  - `Seedance 2.0`

### 🟢 NVIDIA NIM
- **Normal Link**: [Link](https://build.nvidia.com)
- **OpenAI Base URL**: `https://integrate.api.nvidia.com/v1`
- **Rules & Conditions**: Provides free developer access to hosted NIM APIs for development, prototyping, and testing (no credit card required, never expires). Subject to model-specific rate limits (approx. 40 RPM). Strictly for development and testing. Paid options require self-hosting NIM containers under an NVIDIA AI Enterprise license.
- **Supported Models / Features**:
  - `meta/llama-3.3-70b-instruct`
  - `nvidia/nemotron-4-340b-instruct`
  - `deepseek-ai/deepseek-r1`

### 🇳🇱 Nebius Token Factory
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://nebius.ai/)
- **Rules & Conditions**: No permanent free tier. Provides free promotional credits upon account sign-up ('Start Free' model) to test over 60 open-source models in the Playground or via API. Paid usage is pay-per-token for serverless access, or billed by compute hours for dedicated endpoints.
- **Supported Models / Features**:
  - `DeepSeek-V3`
  - `Qwen 2.5`
  - `Qwen 3`
  - `Llama`
  - `Mistral`

### 🇺🇸 NextBit
- **Normal Link**: [Link](https://nextbit.ai/)
- **Rules & Conditions**: No public free tier. Operates on a pay-per-token serverless API platform or fixed-price dedicated instances for enterprise needs.
- **Supported Models / Features**:
  - `Llama 3.3 70B`
  - `Qwen 2.5 72B`
  - `Llama 3.3 8B`

### 🌐 Novita AI Sandbox Browser
- **Normal Link**: [Link](https://novita.ai/products/sandbox)
- **Rules & Conditions**: Secure runtime sandbox for multi-agent workloads. Offers $100 in free Sandbox credits to new users. Free tier limits session lengths to 1 hour, concurrency to 5, and resources to 2 vCPU + 4GB RAM. Paid tier (automatic upgrade when balance > $0) allows up to 24-hour sessions, 100 concurrent sandboxes, and up to 8 vCPU + 8GB RAM.
- **Supported Models / Features**:
  - `DeepSeek-V4-Pro`
  - `Llama 3.3-70B`
  - `Qwen3-Max`
  - `FLUX.1 [dev]`
  - `Stable Diffusion 3`

### 🇺🇸 NovitaAI
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://novita.ai/)
- **OpenAI Base URL**: `https://api.novita.ai/v1`
- **Rules & Conditions**: No permanent free tier. New accounts receive $1 in free credits upon signup, with promotions offering up to $100 in Sandbox credits (valid for 90 days) or $10 for specific models. Startups can receive up to $10,000 in credits. Paid options: Pay-as-you-go based on token usage or hourly dedicated GPU instance hosting.
- **Supported Models / Features**:
  - `Qwen3.7-Max`
  - `MiniMax-M3`
  - `Kimi K2.7 Code`
  - `DeepSeek V4 Pro`

### 🦙 Ollama
- **Normal Link**: [Link](https://ollama.com/)
- **OpenAI Base URL**: `http://localhost:11434/v1`
- **Rules & Conditions**: Fully local and permanently free. Run model architectures like Llama, Qwen, Mistral, and Gemma on local CPU/GPU.

### ☁️ Ollama Cloud
- **Normal Link**: [Link](https://ollama.com/)
- **OpenAI Base URL**: `https://api.ollama.com`
- **Rules & Conditions**: Hosted cloud service for Ollama models. Free tier ($0/month) provides access to a selection of cloud-enabled models, subject to base limits based on actual GPU compute/execution time rather than tokens. Paid plans: Pro ($20/month, 50x usage, 3 concurrent cloud models) and Max ($100/month, 5x Pro usage, 10 concurrent cloud models).
- **Supported Models / Features**:
  - `Llama 3.3`
  - `Qwen 2.5`
  - `Mistral Small`

### 🇺🇸 OpenAI
- **Normal Link**: [Link](https://platform.openai.com/)
- **OpenAI Base URL**: `https://api.openai.com/v1`
- **Rules & Conditions**: No permanent free API tier. New accounts receive a one-time trial credit (e.g., $5 to $18) expiring in 3 months. Users can opt into the Data Sharing Program to get a daily quota of free tokens on specific models (e.g., gpt-4o-mini, gpt-4.1-mini) in exchange for training data. General usage is pay-as-you-go per-token billing (e.g., GPT-5.5 at $5/1M input, $30/1M output; GPT-5.4-nano at $0.10-$0.20/1M input), with input caching and Batch API (50% off) discounts.
- **Supported Models / Features**:
  - `GPT-5.5`
  - `GPT-5.4`
  - `GPT-5.4-mini`
  - `GPT-5.4-nano`
  - `GPT-4o`
  - `GPT-4o-mini`

### 🇺🇸 OpenInference
- **Normal Link**: [Link](https://openinference.io/)
- **Rules & Conditions**: Offers hosted model inference. Historically provides free rate-limited access for certain models (such as Qwen, Kimi, and DeepSeek, e.g., 500 prompts per day) for academic and research purposes. Paid API access is based on token consumption (e.g., Gemma 4 31B at $0.06/M input and $0.35/M output tokens; GPT-OSS 120B at $0.03/M input and $0.15/M output tokens).
- **Supported Models / Features**:
  - `Gemma 4 (31B)`
  - `gpt-oss-120b`
  - `gpt-oss-20b`

### 🌐 OpenRouter
- **Normal Link**: [Link](https://openrouter.ai/keys)
- **OpenAI Base URL**: `https://openrouter.ai/api/v1`
- **Rules & Conditions**: 20 RPM, 50 RPD free models (up to 1,000 RPD with $10 lifetime top-up)
- **Supported Models / Features**:
  - `poolside/laguna-xs-2.1:free`
  - `cohere/north-mini-code:free`
  - `nvidia/nemotron-3.5-content-safety:free`
  - `nvidia/nemotron-3-ultra-550b-a55b:free`
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

### ⚡ Parallel
- **Normal Link**: [Link](https://parallel.ai/)
- **Rules & Conditions**: AI-native search and extraction engine. Operates primarily on a pay-as-you-go consumption model with no standard monthly free tier for its hosted web APIs. Search requests are billed at ~$0.005/request and extraction at ~$0.001/request. The Parallel Search Model Context Protocol (MCP) server is free to run locally and does not require an API key.
- **Supported Models / Features**:
  - `Search API`
  - `Extract API`
  - `Monitor API`

### 🇺🇸 Parasail
- **Normal Link**: [Link](https://parasail.io/)
- **Rules & Conditions**: Offers a 'Serverless - Free' tier for prototyping and testing, limited to 5 Requests Per Minute (RPM). Paid options: Pay-per-token serverless billing or hourly GPU instance billing, which typically requires a linked payment method and a $25 charging threshold.
- **Supported Models / Features**:
  - `Qwen series`
  - `DeepSeek series`
  - `Llama series`

### 🇺🇸 Perceptron
- **Normal Link**: [Link](https://perceptron.ai/)
- **Rules & Conditions**: Flagship model Perceptron Mk1 can be tested for free via their demo app or integrations like Puter.js. Developers can sign up for API keys on platform.perceptron.inc. Direct API usage is billed on a pay-as-you-go token basis: $0.15 per million input tokens ($0.15/MT) and $1.50 per million output tokens ($1.50/MT).
- **Supported Models / Features**:
  - `Perceptron Mk1`

### 🇺🇸 Perplexity
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://www.perplexity.ai/pro)
- **OpenAI Base URL**: `https://api.perplexity.ai`
- **Rules & Conditions**: No permanent free tier. New accounts receive $25-$50 in trial credits. Perplexity Pro subscribers ($20/month) receive $5 in monthly API credits. Startup programs offer grants from $500 to $5,000+. Paid options: Pay-as-you-go token pricing.
- **Supported Models / Features**:
  - `Sonar Small Online`
  - `Sonar Large Online`
  - `Sonar Huge Online`
  - `Sonar Pro`

### 🌐 Phala
- **Normal Link**: [Link](https://phala.network/)
- **Rules & Conditions**: Decentralized confidential computing network. Agent Contracts can be deployed and hosted for free with no gas fees (dstack SDK is free). For Phala Cloud (Confidential VMs/GPU TEEs), new verified users may receive $20 in free credits, after which computing resources are billed on a pay-as-you-go basis (per-minute billing for instance types and $0.000139/GB/hour for storage).
- **Supported Models / Features**:
  - `Llama 3.1`
  - `Qwen`
  - `DeepSeek`
  - `Gemma`
  - `Phi`
  - `LLaVA`

### 🇫🇷 Poolside
- **Normal Link**: [Link](https://poolside.ai/)
- **Rules & Conditions**: Enterprise-focused coding assistant and foundation models. Models are available with open weights (e.g., Laguna XS.2 is Apache-2.0 licensed). Free access to models is available via third-party integrations like OpenRouter, Puter.js, Requesty, and Krater.ai. Direct business model is custom enterprise deployment (on-premises or private VPCs), with no standard public self-serve pay-as-you-go pricing listed.
- **Supported Models / Features**:
  - `Laguna M.1`
  - `Laguna XS.2`

### 🤖 Qoder
- **Normal Link**: [Link](https://qoder.io/)
- **Rules & Conditions**: Local developer utility for AI assistance, code generation, and terminal integration.

### 🇺🇸 Reka AI
- **Normal Link**: [Link](https://www.reka.ai/)
- **Rules & Conditions**: Developer API offers $10 in free credits monthly. Reka Vision API offers a free evaluation tier of 3 free hours (180 minutes) of indexed video. Paid usage is consumption-based (pay-as-you-go) per token (for text) or per-minute/request (for video/image/research tasks).
- **Supported Models / Features**:
  - `Reka Core`
  - `Reka Flash`
  - `Reka Edge`
  - `Reka Spark`

### 🇺🇸 Relace
- **Normal Link**: [Link](https://relace.co/)
- **Rules & Conditions**: Provides developer infrastructure for autonomous coding agents. Offers a free tier with rate limits (e.g., 3 calls per minute) for testing and small projects. Paid plans are usage-based or tiered (token-based pricing for individual models) designed to scale with team size.
- **Supported Models / Features**:
  - `Relace Apply 3`
  - `Instant Apply`
  - `Relace Search`

### 🇺🇸 SambaNova
- **Normal Link**: [Link](https://cloud.sambanova.ai/)
- **OpenAI Base URL**: `https://api.sambanova.ai/v1`
- **Rules & Conditions**: No perpetual free tier. Offers $5 in free API credits to new users (valid for 30 to 90 days, no credit card required) subject to Free Tier rate limits. Paid options: Developer Tier (pay-as-you-go) with higher rate limits (e.g., 20M tokens/day) once a billing method is linked.
- **Supported Models / Features**:
  - `Meta-Llama-3.3-70B-Instruct`
  - `DeepSeek-V3.1`
  - `gemma-4-31B-it`
  - `gpt-oss-120b`

### 🔍 SearXNG
- **Normal Link**: [Link](https://github.com/searxng/searxng)
- **Rules & Conditions**: Free, open-source metasearch engine that aggregates results from more than 70 search services. Completely free to self-host (using Docker or local installation) with zero API keys required. Integrates with agents via setting the SEARXNG_URL environment variable to point to the self-hosted instance endpoint.
- **Supported Models / Features**:
  - `Self-Hosted Metasearch API`

### 🇨🇳 SiliconFlow
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://siliconflow.cn/zh-cn/)
- **OpenAI Base URL**: `https://api.siliconflow.cn/v1`
- **Rules & Conditions**: Offers a 'Get Started for Free' tier featuring select free models (e.g., Qwen2.5-7B-Instruct) subject daily rate limits (e.g., 50 requests/day). New accounts receive $1 in free trial credits. Paid options: Pay-as-you-go token pricing for Pro models.
- **Supported Models / Features**:
  - `MiniMax-M3`
  - `Nex-N2-Pro`
  - `DeepSeek-V4-Pro`
  - `Qwen2.5-7B-Instruct`

### 🇨🇳 StepFun
- **Normal Link**: [Link](https://platform.stepfun.com/)
- **Rules & Conditions**: Offers the Step series of multimodal models. Free tier is available under the V0 tier ($0 account balance) with rate limits of 10 RPM and 5,000,000 TPM. Certain models (like Step 3.5 Flash) are also free to use via OpenRouter. Paid tiers require topping up your account balance (starting from $15 up to $1,500+), which increases RPM, TPM, and concurrency limits.
- **Supported Models / Features**:
  - `Step 3.5 Flash`
  - `Step 3.7 Flash`
  - `Step-1-128k`
  - `Step-2`

### 🇺🇸 Switchpoint
- **Normal Link**: [Link](https://switchpoint.ai/)
- **Rules & Conditions**: Intelligent LLM routing service. Offers a free trial with small signup credits for new developer accounts. Paid options include a Pay-As-You-Go Developer Plan (using top-up credits based on routed models) and a flat-rate Stable Tier ($1.05/M input and $4.25/M output tokens).
- **Supported Models / Features**:
  - `GPT-4o (Routed)`
  - `Claude 3.5 Sonnet (Routed)`
  - `Llama 3.1 (Routed)`

### 🕵️ Tavily
- **Normal Link**: [Link](https://tavily.com/)
- **Rules & Conditions**: AI-native search engine designed for LLMs. Free tier provides 1,000 search API queries/month (no credit card required, resets monthly). Billed by usage: Basic Search consumes 1 credit, Advanced Search consumes 2 credits, Extract consumes 1 credit/5 URLs. Paid plans: Pay-as-you-go at $0.008/credit, or monthly subscriptions starting at $15/month.
- **Supported Models / Features**:
  - `Search API`
  - `Extract API`
  - `Crawl API`

### 🇺🇸 Together
- **Normal Link**: [Link](https://together.ai/)
- **OpenAI Base URL**: `https://api.together.xyz/v1`
- **Rules & Conditions**: Requires a minimum credit purchase of $5 to activate and maintain API access. New accounts generally receive $5 in free credits to test the API. Billed under a pay-as-you-go serverless model ranging from $0.05 to $9.00 per million tokens (e.g., Llama 3.3 70B is ~$0.88/M tokens; DeepSeek R1 is ~$3.00/$7.00 per M tokens). Offers input context caching discounts.
- **Supported Models / Features**:
  - `DeepSeek R1`
  - `DeepSeek V3.1`
  - `Llama 3.3 (70B)`
  - `Qwen 3.6 Plus`
  - `Kimi K2.6`

### 🌐 Venice
- **Referral Link**: [Link]()
- **Normal Link**: [Link](https://venice.ai/)
- **OpenAI Base URL**: `https://api.venice.ai/api/v1`
- **Rules & Conditions**: Freemium model. Free tier allows 10 text prompts and 15 image prompts per day without login. Paid plans: Pro ($18/mo for unlimited text, 1000 images/day, and 100 credits/mo), Pro Plus ($68/mo with 7,500 credits/mo), and Max ($200/mo with 22,500 credits/mo). API access is included in the Pro tier.
- **Supported Models / Features**:
  - `Claude 3.5 Sonnet`
  - `Gemini 3 Flash Preview`
  - `Llama 3.1`
  - `DeepSeek R1`
  - `Venice Uncensored`

### 🎙️ Voice Tools (OpenAI)
- **Normal Link**: [Link](https://platform.openai.com/)
- **Rules & Conditions**: Hermes audio transcription and speech integration using OpenAI Whisper (STT) and OpenAI TTS. Billed directly via the configured OpenAI API key (pay-as-you-go). Whisper is priced at $0.006/minute of audio. OpenAI TTS is priced at $15/M characters (Standard) and $30/M characters (HD).
- **Supported Models / Features**:
  - `whisper-1`
  - `tts-1`
  - `tts-1-hd`

### 💬 WaCLI
- **Normal Link**: [Link](https://github.com/topics/whatsapp-cli)
- **Rules & Conditions**: WhatsApp CLI tool for sending, syncing, and alerting messages directly from the server command-line.

### 🇺🇸 Wafer
- **Normal Link**: [Link](https://wafer.ai/)
- **Rules & Conditions**: Optimized AI performance engineering and inference platform. Does not offer a traditional free tier. Provides flat-rate subscription passes: Starter (~$10/week for 1,000 requests every 5 hours) and Privacy (~$25/week for 2,000 requests every 5 hours with zero data retention). Also offers pay-as-you-go serverless billing for enterprise accounts.
- **Supported Models / Features**:
  - `Qwen 3.5 397B-A17B`
  - `GLM-5.1`
  - `Kimi-K2.6`

### 🇺🇸 Weights & Biases
- **Normal Link**: [Link](https://wandb.ai/)
- **Rules & Conditions**: W&B is an MLOps platform (not a model hosting provider). Free tier for personal or academic use offers unlimited experiments and tracked hours, and 5 GB of artifact storage. Paid options: Pro and Enterprise plans for team collaboration and commercial use.
- **Supported Models / Features**:
  - `Integrates with Llama`
  - `Integrates with GPT`
  - `Integrates with Claude`
  - `Integrates with Stable Diffusion`

### 🇨🇳 Xiaomi
- **Normal Link**: [Link](https://xiaoai.mi.com/)
- **Rules & Conditions**: No permanent free tier. Offers limited-time promotions (e.g., free access to flagship MiMo-V2.5 models or TTS model) and partner integrations (e.g., Cline, OpenCode) with models labeled 'FREE'. Paid options: Pay-as-you-go token billing (e.g., MiMo-V2.5 at ¥1.00/M tokens Cache Miss) and Token Plan subscription packages starting around ¥39/month.
- **Supported Models / Features**:
  - `MiMo-V2.5 Pro`
  - `MiMo-V2-Flash`
  - `MiMo-V2-Omni`
  - `MiMo-V2-TTS`

### 🇨🇳 Z.ai
- **Normal Link**: [Link](https://open.bigmodel.cn/)
- **Rules & Conditions**: Offers free-tier access for specific models like GLM-4-Flash and GLM-4.5-Flash. New users receive registration bonuses of free tokens (millions of tokens) valid for a limited period. Paid API usage is billed per token on a pay-as-you-go model. Offers GLM Coding subscription plans for premium/agentic models.
- **Supported Models / Features**:
  - `GLM-5`
  - `GLM-5-Turbo`
  - `GLM-4.7`
  - `GLM-4.5-Flash`
  - `CogVideoX`
  - `CodeGeeX`

### 🌐 io.net
- **Normal Link**: [Link](https://io.net/)
- **Rules & Conditions**: No traditional free tier. Offers subscription plans that include monthly usage credits: Professional Plan ($15/mo in credits for light workloads, refreshes daily) and Developer Plan ($150/mo in credits with ~10% discount, refreshes every 8 hours). Beyond credits, usage is pay-as-you-go billed via $IO tokens or credit cards.
- **Supported Models / Features**:
  - `Llama-3.3-70B-Instruct`
  - `Custom Docker Container Deployments`

### 🇺🇸 xAI
- **Normal Link**: [Link](https://console.x.ai/)
- **OpenAI Base URL**: `https://api.x.ai/v1`
- **Rules & Conditions**: Grok chatbot has a limited free tier (~10 messages every 2 hours) on grok.com/X app. The developer API (console.x.ai) offers $25 in promotional credits for new accounts. A data-sharing opt-in program offers up to $150/month in credits (requires minimum $5 spend to enroll). Paid API usage is consumption-based (e.g., Grok 4.3 at $1.25/M input and $2.50/M output tokens).
- **Supported Models / Features**:
  - `Grok 4.3`
  - `Grok Build 0.1`
  - `Grok Imagine API`
  - `Grok Voice API`

## 🤝 Contribution Guidelines & Automation

This repository is maintained automatically by Hermes agents. Daily jobs scan upstream sources and GitHub Issues.

- **Reporting changes**: If a free tier has changed or a provider has sunsetted credits, please **open an issue** with the specific provider name and details. The bot will automatically verify the claim via web search and update the catalog within 24 hours.

- **Submitting updates**: PRs updating `free-llm-providers.json` or scripts are welcome. Please don't edit `README.md` directly since it's dynamically generated.

---
*Last updated: 2026-07-03 10:00:59 (IST) | Build ID: 20260703100059*