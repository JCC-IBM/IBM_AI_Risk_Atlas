# Data privacy rights risk for AI

**Risks associated with input** \
**Training and tuning phase** \
**Privacy** \
**Amplified by generative AI**

### Description

Challenges around the ability to provide data subject rights such as opt-out, right to access, right to be forgotten.

### Why is data privacy rights a concern for foundation models?

The identification or improper usage of data might lead to violation of privacy laws. Improper usage or a request for data removal might force organizations to retrain the model, which is expensive. In addition, business entities might face fines, reputational harms, disruption to operations, and other legal consequences if they fail to comply with data privacy rules and regulations.

### Example- Right to Be Forgotten (RTBF)

Laws in multiple locales, including Europe (GDPR), grant data subjects the right to request personal data to be deleted by organizations (‘Right To Be Forgotten’, or RTBF). However, emerging, and increasingly popular large language model (LLM) -enabled software systems present new challenges for this right. According to research by CSIRO’s Data61, data subjects can identify usage of their personal information in an LLM “by either inspecting the original training data set or perhaps prompting the model.” However, training data might not be public, or companies do not disclose it, citing safety and other concerns. Guardrails might also prevent users from accessing the information by prompting. Due to these barriers, data subjects might not be able to initiate RTBF procedures and companies that deploy LLMs might not be able to meet RTBF laws.

Source: https://arxiv.org/pdf/2307.03941

### Example- Lawsuit About LLM Unlearning

According to the report, a lawsuit was filed against Google that alleges the use of copyright material and personal information as training data for its AI systems, which includes its Bard chatbot. Opt-out and deletion rights are guaranteed rights for California residents under the CCPA and children in the United States under the age of 13 with COPPA. The plaintiffs allege that because there is no way for Bard to “unlearn” or fully remove all the scraped PI it has been fed. The plaintiffs note that Bard’s privacy notice states that Bard conversations cannot be deleted by the user after they have been reviewed and annotated by the company and might be kept up to 3 years. P allege that these practices further contribute to noncompliance with these laws.

Sources: https://www.reuters.com/legal/litigation/google-hit-with-class-action-lawsuit-over-ai-data-scraping-2023-07-11/ and https://fingfx.thomsonreuters.com/gfx/legaldocs/myvmodloqvr/GOOGLE%20AI%20LAWSUIT%20complaint.pdf