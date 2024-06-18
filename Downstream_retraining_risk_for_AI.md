# Downstream retraining risk for AI

**Risks associated with input** \
**Training and tuning phase** \
**Value alignment** \
**New to generative AI**

### Description

Using undesirable (for example, inaccurate, inappropriate, user’s content) output from downstream applications for retraining purposes.

### Why is downstream retraining a concern for foundation models?

Repurposing downstream output for retraining a model without implementing proper human vetting increases the chances of undesirable outputs being incorporated into the training or tuning data of the model. This, in turn, can generate even more undesirable output. Improper model behavior can result in business entities facing legal consequences or reputational harms. Failing to comply with data transfer laws might result in fines and other legal consequences.

### Example - Model collapse due to training using AI-generated content

As stated in the source article, a group of researchers from the UK and Canada investigated the problem of using AI-generated content for training instead of human-generated content. They found that the large language models behind the technology might potentially be trained on other AI-generated content. As generated data continues to spread in droves across the internet it can result ina phenomenon they coined as "model collapse."

Source: https://www.businessinsider.com/ai-model-collapse-threatens-to-break-internet-2023-8