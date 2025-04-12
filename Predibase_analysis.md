# Predibase Fine-Tuning Analysis

## What It Is
Predibase bills itself as a low-code AI platform for developers. It's designed to make fine-tuning and serving open-source LLMs efficient and straightforward, focusing on cost-effectiveness, speed, and ease of use. It's built on open-source tools like Ludwig.

## Key Features for Fine-Tuning
*   **Low-Code Approach**: Aims to simplify the fine-tuning process, making it more accessible.
*   **Open-Source Focus**: Supports a wide variety of popular OSS models (Llama, Mistral, Mixtral, Gemma, Phi, Qwen, CodeLlama, Solar, etc.) and tries its best to support any model from Hugging Face.
*   **Efficient Tuning Methods**: Offers several ways to fine-tune, including standard LoRA, their own faster "Turbo LoRA," an efficient full-parameter method called "Turbo," and Reinforcement Fine-tuning (RFT GRPO).
*   **Cost-Saving Serving (LoRAX)**: Uses a technology called LoRA Exchange (LoRAX) that allows potentially hundreds of different fine-tuned LoRA models (adapters) to run on a single GPU deployment. This can drastically cut down serving costs if you have many specialized models.
*   **Deployment Choices**:
    *   **Predibase AI Cloud (SaaS)**: A managed service you can use via pay-as-you-go or enterprise plans.
    *   **VPC Deployment**: An enterprise option lets you run Predibase within your own cloud account (AWS, Azure, or GCP) for maximum data privacy.

## Pricing (Fine-Tuning)
*   **How it works**: You're charged per million tokens processed during the fine-tuning job. The exact rate depends on the size of the base model and the tuning technique you use.
*   **Fine-Tuning Costs (per 1 Million Tokens Processed)**:
    *   **LoRA / Turbo (SFT or Continued Pretraining)**:
        *   Up to 16B params: $0.50
        *   16.1B to 80B params: $3.00
    *   **Turbo LoRA (SFT or Continued Pretraining)**:
        *   Up to 16B params: $1.00
        *   16.1B to 80B params: $6.00
    *   **RFT GRPO (Reinforcement Fine-tuning with LoRA)**:
        *   Up to 16B params: $10.00
        *   16.1B to 32B params: $20.00
*   **Cost Estimator**: Their pricing page includes an interactive calculator.
*   **Serving Costs (After Tuning)**:
    *   **Private Serverless Inference**: Billed per second based on the hardware you choose (e.g., A10G: $2.60/hr, L40S: $3.20/hr, A100 80GB: $4.80/hr). This supports the LoRAX multi-adapter serving and can scale down to zero when not in use. Enterprise plans get access to higher-end GPUs (H100, H200, MI300X).
    *   **Shared Serverless Inference**: A free option mainly for testing, with daily and monthly token limits and rate limiting.
*   **Platform Tiers**:
    *   **Developer**: Pay-as-you-go, comes with $25 in free credits (which expire after 30 days).
    *   **Enterprise (SaaS & VPC)**: Custom pricing. Includes volume discounts, guaranteed compute resources, SLAs, better support, and the VPC deployment option.

## Who It's For
*   Developers and companies wanting an easy-to-use, cost-effective platform for fine-tuning and serving open-source LLMs.
*   Teams interested in using LoRA fine-tuning and benefiting from efficient multi-adapter serving with LoRAX.
*   Businesses needing the flexibility of either a managed SaaS solution or a private deployment in their own VPC.

## Where to Find More
*   Pricing Page: [https://predibase.com/pricing](https://predibase.com/pricing)
*   Homepage: [https://predibase.com/](https://predibase.com/)