# Databricks Mosaic AI Model Training Analysis

## Overview
Databricks offers LLM fine-tuning and pretraining capabilities through its **Mosaic AI Model Training** service, integrated within the Databricks Data Intelligence Platform. It allows organizations to customize open-source models or build new ones using their own enterprise data securely within the Databricks environment.

## Key Features
- **Integrated Platform**: Natively available in Databricks, enabling secure fine-tuning without moving data.
- **Scalability**: Leverages high-performance networking (NVIDIA InfiniBand) and GPUs (NVIDIA H100) for training large models (>70B parameters).
- **Cost-Effectiveness**: Claims fine-tuned smaller models can be up to 5x more cost-effective to serve than larger proprietary LLMs. Optimized stack aims for lower training costs.
- **Security & Compliance**: Data remains within the client's environment; full control and ownership over data and models; encryption by default.
- **Governance**: Benefits from Databricks platform's governance, auditability, traceability, and monitoring features.
- **Supported Models**: Examples include Llama 3.1 (70B, 8B), Llama 3.2 (3B, 1B), and others (though some legacy models like DBRX, Mixtral are being deprecated).

## Use Cases (Examples from Customers)
- Code completion (Replit)
- Data labeling and enrichment (Refuel)
- Building custom open-source LLMs (AI2)
- Conversational queries / Semantic search (Stardog)

## Pricing (Mosaic AI Model Training - fine-tuning)
- **Model**: Pay-as-you-go based on Databricks Units (DBUs).
- **Cost per DBU**: ~$0.65 / DBU (Example: US East region on AWS/Azure/GCP). Price includes underlying cloud instance cost. Price may vary by region.
- **Billing Factors**: DBU consumption depends on the specific model being trained and the size (e.g., word count) of the training dataset.
- **Example Costs (US East @ $0.65/DBU)**:
    - Llama 3.1 70B (10M words): ~$146.25 (~225 DBUs)
    - Llama 3.1 70B (500M words): ~$7,150.00 (~11,000 DBUs)
    - Llama 3.1 8B (10M words): ~$65.00 (~100 DBUs)
    - Llama 3.1 8B (500M words): ~$2,860.00 (~4,400 DBUs)
- **Committed Use**: Discounts available for usage commitments.
- **Other Costs**: Standard Databricks platform costs (storage, networking, data transfer) may apply separately.

## Target Audience
- Organizations already using or considering the Databricks platform.
- Enterprises needing to fine-tune or pretrain LLMs securely on their own data within a governed environment.
- Users requiring scalable training infrastructure for large models.

## Website
- Product Page: [https://www.databricks.com/product/machine-learning/mosaic-ai-training](https://www.databricks.com/product/machine-learning/mosaic-ai-training)
- Fine-tuning Pricing: [https://www.databricks.com/product/pricing/mosaic-foundation-model-training](https://www.databricks.com/product/pricing/mosaic-foundation-model-training)
- Overall Pricing: [https://www.databricks.com/product/pricing](https://www.databricks.com/product/pricing)