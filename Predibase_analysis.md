# Predibase Fine-Tuning Analysis

## Overview
Predibase is a low-code AI platform designed for developers to efficiently fine-tune and serve open-source large language models (LLMs). It emphasizes cost-effectiveness, speed, and ease of use, built on open-source foundations like Ludwig.

## Key Features for Fine-Tuning
- **Low-Code Interface**: Simplifies the process of fine-tuning.
- **Focus on OSS**: Supports a wide range of popular open-source models (Llama, Mistral, Mixtral, Gemma, Phi, Qwen, CodeLlama, Solar, etc.) and offers best-effort support for any Hugging Face model.
- **Efficient Techniques**: Offers various fine-tuning methods including LoRA, Turbo LoRA (proprietary efficient LoRA), full-parameter Turbo (proprietary efficient full-parameter tuning), and Reinforcement Fine-tuning (RFT GRPO).
- **Cost-Effective Serving**: Utilizes LoRA Exchange (LoRAX) technology to serve potentially hundreds of fine-tuned LoRA adapters on a single GPU deployment, significantly reducing serving costs.
- **Deployment Options**:
    - **Predibase AI Cloud (SaaS)**: Managed service with pay-as-you-go or enterprise tiers.
    - **VPC Deployment**: Enterprise option to deploy within the customer's own cloud (AWS, Azure, GCP).

## Pricing (Fine-Tuning)
- **Model**: Charged per 1 million tokens processed during fine-tuning. Rate depends on base model size and technique.
- **Fine-Tuning Costs (per 1 Million Tokens Processed)**:
    - **SFT / Continued Pretraining (LoRA, Turbo)**:
        - Models up to 16B params: $0.50
        - Models 16.1B to 80B params: $3.00
    - **SFT / Continued Pretraining (Turbo LoRA)**:
        - Models up to 16B params: $1.00
        - Models 16.1B to 80B params: $6.00
    - **RFT GRPO (LoRA)** (Reinforcement Fine-tuning):
        - Models up to 16B params: $10.00
        - Models 16.1B to 32B params: $20.00
- **Interactive Calculator**: Available on the pricing page for cost estimation.
- **Serving Costs (Post-Tuning)**:
    - **Private Serverless Inference**: Billed per second based on hardware choice (e.g., A10G: $2.60/hr, L40S: $3.20/hr, A100 80GB: $4.80/hr). Supports LoRAX. Scales to zero. Higher-end GPUs (H100, H200, MI300X) available for Enterprise.
    - **Shared Serverless Inference**: Free tier for testing (up to 1M tokens/day, 10M tokens/month) with rate limits.
- **Platform Tiers**:
    - **Developer**: Pay-as-you-go, $25 free credits (expire after 30 days).
    - **Enterprise (SaaS & VPC)**: Custom pricing with volume discounts, guaranteed resources, SLAs, enhanced support, and VPC deployment option.

## Target Audience
- Developers and organizations looking for a cost-effective and easy-to-use platform for fine-tuning and serving OSS LLMs.
- Teams wanting to leverage LoRA fine-tuning and efficient serving via LoRAX.
- Companies needing options for both managed SaaS and private VPC deployments.

## Website
- Pricing Page: [https://predibase.com/pricing](https://predibase.com/pricing)
- Homepage: [https://predibase.com/](https://predibase.com/)