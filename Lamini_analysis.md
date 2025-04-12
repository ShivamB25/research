# Lamini Platform Analysis

## What It Is
Lamini offers an enterprise LLM platform designed to help build highly accurate "mini-agents." A big focus is reducing hallucinations (they claim by 95%) and ensuring factual accuracy when using LLMs with your own data.

## Key Offerings
*   **Memory Tuning**: Their specific fine-tuning method that aims for high accuracy without sacrificing speed or driving up costs.
*   **Memory RAG**: A simpler take on Retrieval-Augmented Generation (RAG) that uses "embed-time compute" to boost accuracy (claiming 90%+) when building mini-agents.
*   **Classifier Agent Toolkit**: An LLM-powered tool for classifying large amounts of unstructured data automatically.
*   **Optimized Inference**: Lamini claims their platform delivers high throughput for inference (mentioning 52x faster than vLLM in a blog post).
*   **Evaluation Suite**: Includes tools to check how well your LLMs are performing.

## Common Use Cases
*   Building chatbots that give factual answers based on documentation.
*   Automating data classification tasks.
*   Creating Text-to-SQL agents.
*   Developing code assistants.
*   Scaling customer service agents.
*   Enabling function calling for agents to interact with external tools.

## Deployment Options
*   **Lamini Cloud**: Use Lamini's own optimized compute infrastructure (available via On-demand or Reserved plans).
*   **Self-Managed**: Deploy the Lamini platform within your own secure environment (VPC, on-premises, or even air-gapped) using your own GPUs.

## Pricing Breakdown

### On-demand
*   **How it works**: Pay as you go.
*   **Getting Started**: New users get $300 in free credits.
*   **Inference Cost**: $0.50 per million tokens (same rate for input, output, and JSON).
*   **Tuning Cost**: $0.50 per "tuning step" (cost scales with your data).
*   **What's included**: Access to models like Llama 3.1, Mistral v0.3, Phi 3; support for the full process (RAG, tuning, evaluation, inference).

### Reserved
*   **How it works**: Custom pricing for dedicated resources.
*   **What's included**:
    *   Reserved GPUs on Lamini's cluster.
    *   Unlimited tuning and inference usage on those GPUs.
    *   High inference throughput.
    *   Full evaluation tools.
    *   Enterprise-level support.

### Self-managed
*   **How it works**: Custom pricing for running Lamini in your environment.
*   **What's included**:
    *   Runs on your own GPUs (VPC, On-prem, Air-gapped).
    *   Doesn't require internet access.
    *   Billed per software license.
    *   Full evaluation tools.
    *   Access to Lamini's ML experts.
    *   Enterprise-level support.

### Startups
*   Lamini mentions special pricing is available; you'll need to contact them.

## Who It's For
*   Companies (startups and enterprises) needing highly accurate and reliable LLMs.
*   Organizations that require secure deployment options like VPC, on-prem, or air-gapped environments.

## Where to Find More
*   Homepage: [https://www.lamini.ai/](https://www.lamini.ai/)
*   Pricing Page: [https://www.lamini.ai/pricing](https://www.lamini.ai/pricing)