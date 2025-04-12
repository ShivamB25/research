# Databricks Mosaic AI Model Training Analysis

## What It Is
Databricks provides LLM fine-tuning and pretraining through its **Mosaic AI Model Training** service. It's built right into the main Databricks Data Intelligence Platform, letting companies customize open-source models or even build new ones using their own data, all securely within their Databricks environment.

## Key Features
*   **All-in-One Platform**: Because it's native to Databricks, you can fine-tune models securely without having to move your data around.
*   **Built to Scale**: Gives access to high-performance gear like NVIDIA InfiniBand networking and H100 GPUs, making it feasible to train large models (over 70 billion parameters).
*   **Cost Savings Claims**: Databricks suggests that fine-tuning smaller open-source models can be up to 5 times cheaper to serve compared to using large proprietary ones. They also claim their optimized setup lowers training costs significantly.
*   **Security & Ownership**: Your data stays put in your environment. You keep full control and ownership of both your data and the resulting model. Everything's encrypted by default.
*   **Governance Included**: Leverages the standard Databricks governance features for tracking, auditing, and monitoring model usage.
*   **Model Support**: Works with models like Llama 3.1 (70B, 8B) and Llama 3.2 (3B, 1B). Some older models like DBRX and Mixtral are being phased out.

## How Customers Use It (Examples)
*   Replit uses it for code completion models.
*   Refuel uses it for data labeling and enrichment tasks.
*   AI2 used it to build their open-source OLMo model.
*   Stardog uses it for conversational query models.

## Pricing (Mosaic AI Fine-tuning)
*   **How it works**: Pay-as-you-go, billed using Databricks Units (DBUs).
*   **Cost per DBU**: Around $0.65 per DBU (using US East as an example; rate varies by region). This price includes the cost of the underlying cloud compute instance.
*   **What drives cost**: The number of DBUs used depends mainly on the model you're training and how much data (e.g., word count) you're using.
*   **Rough Cost Examples (US East @ $0.65/DBU)**:
    *   Llama 3.1 70B (10M words): ~$146 (approx. 225 DBUs)
    *   Llama 3.1 70B (500M words): ~$7,150 (approx. 11,000 DBUs)
    *   Llama 3.1 8B (10M words): ~$65 (approx. 100 DBUs)
    *   Llama 3.1 8B (500M words): ~$2,860 (approx. 4,400 DBUs)
*   **Discounts**: Available if you commit to a certain level of usage.
*   **Other Costs**: Remember to factor in standard Databricks costs for things like data storage, networking, and data transfer.

## Who It's For
*   Companies already using Databricks or planning to adopt it.
*   Businesses that need to fine-tune or pretrain LLMs securely on their own data within a governed platform.
*   Teams needing scalable infrastructure to train large models.

## Where to Find More
*   Product Page: [https://www.databricks.com/product/machine-learning/mosaic-ai-training](https://www.databricks.com/product/machine-learning/mosaic-ai-training)
*   Fine-tuning Pricing: [https://www.databricks.com/product/pricing/mosaic-foundation-model-training](https://www.databricks.com/product/pricing/mosaic-foundation-model-training)
*   Overall Pricing: [https://www.databricks.com/product/pricing](https://www.databricks.com/product/pricing)