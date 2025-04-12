# Lamini Platform Analysis

## Overview
Lamini provides an enterprise LLM platform focused on building highly accurate "mini-agents" and reducing LLM hallucinations by a claimed 95%. They emphasize factual accuracy and enabling LLMs based on proprietary data.

## Key Offerings
- **Memory Tuning**: A fine-tuning method aiming for high accuracy while keeping inference latency and cost low.
- **Memory RAG**: A simplified RAG approach using "embed-time compute" to achieve high accuracy (claimed 90%+) with mini-agents.
- **Classifier Agent Toolkit**: An LLM-based tool for large-scale classification of unstructured data.
- **Optimized Inference**: Claims high throughput (52x more RPM than vLLM mentioned in a blog post).
- **Evaluation Suite**: Tools for evaluating LLM performance.

## Use Cases
- Factual Reasoning (Documentation Chatbots)
- Classification
- Text-to-SQL
- Code Assistance
- Customer Service Agents
- Function Calling

## Deployment Options
- **Lamini Cloud**: Runs on Lamini's optimized compute platform (On-demand, Reserved plans).
- **Self-Managed**: Deployed in the client's own secure environment (VPC, On-premises, Air-gapped). Runs on client's GPUs.

## Pricing

### On-demand
- **Model**: Pay-as-you-go.
- **Free Credit**: $300 for new users.
- **Inference Cost**: $0.50 / 1 million tokens (input, output, JSON).
- **Tuning Cost**: $0.50 / tuning step (scales with data).
- **Features**: Access to models like Llama 3.1, Mistral v0.3, Phi 3; Full lifecycle support (RAG, prompt tuning, memory tuning, evaluation, inference).

### Reserved
- **Model**: Custom pricing.
- **Features**:
    - Dedicated GPUs from Lamini's cluster.
    - Unlimited tuning and inference.
    - High inference throughput.
    - Full evaluation suite.
    - Enterprise support.

### Self-managed
- **Model**: Custom pricing.
- **Features**:
    - Runs on client's own GPUs in their environment (VPC, On-prem, Air-gapped).
    - No internet access needed.
    - Pay per software license.
    - Full evaluation suite.
    - Access to ML experts.
    - Enterprise support.

### Startups
- Special pricing is available; contact Lamini for details.

## Target Audience
- Enterprises and startups requiring high accuracy and factual reliability from LLMs.
- Organizations needing secure deployment options (VPC, On-prem, Air-gapped).

## Website
- [https://www.lamini.ai/](https://www.lamini.ai/)
- Pricing Page: [https://www.lamini.ai/pricing](https://www.lamini.ai/pricing)