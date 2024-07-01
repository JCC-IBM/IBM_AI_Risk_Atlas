The IBM AI Risk Atlas provides a guide to understand some of the risks of working with generative AI, foundation models, and machine learning models.

Risks are categorized with one of these tags:

Traditional AI risks (applies to traditional models as well as generative AI)
Risks amplified by generative AI (might also apply to traditional models)
New risks specifically associated with generative AI

Fistly we will describe and explain non-technical risks associated with AI.

1. Accountability risk is a non-technical governance risk that is amplified by generative AI.

Description:
The foundation model development process is complex with lots of data, processes, and roles. When model output does not work as expected, it can be difficult to determine the root cause and assign responsibility.

Why is accountability a concern for foundation models?
Without properly documenting decisions and assigning responsibility, determining liability for unexpected behavior or misuse might not be possible.

Example - Determining responsibility for generated output
Major journals like the Science and Nature banned ChatGPT from being listed as an author, as responsible authorship requires accountability and AI tools cannot take such responsibility.

2. Lack of data transparency risk for AI is a non-technical governance risk amplified by generative AI.

Description
Insufficient documentation of the data that is used for model training makes it difficult to comply with legal requirements, including explaining the representativeness of data and the expected model behavior.

Why is lack of data transparency a concern for foundation models?
Transparency is important for legal compliance and AI ethics. Missing information might make it more difficult to evaluate representational harms, data ownership, and provenance.

3.Lack of model transparency risk for AI is a non-technical governance risk. It is a traditional AI risk.

Description
Insufficient documentation of the model development process makes it difficult to understand how and why a model was built and who built it, thus increasing the possibility of model unintended misuse.

Why is lack of model transparency a concern for foundation models?
Transparency is important for legal compliance, AI ethics, and guiding appropriate use of models. Missing information might make it more difficult to evaluate risks, to change the model, or reuse it. Knowledge about who built a model can also be an important factor in deciding whether to trust it.

Example - Data and Model Metadata Disclosure
OpenAI's technical report is an example of the dichotomy around disclosing data and model metadata. While many model developers see value in enabling transparency for consumers, disclosure poses real safety issues and might increase the ability to misuse the models. In the GPT-4 technical report, they state: ”Given both the competitive landscape and the safety implications of large-scale models like GPT-4, this report contains no further details about the architecture (including model size), hardware, training compute, data set construction, training method, or similar.”

Source: https://arxiv.org/pdf/2303.08774

4. Generated content IP risk for AI is non-technical legal compliance risk that is new to generative AI

Description
Legal uncertainty about intellectual property rights related to generated content

Why is generated content ip a concern for foundation models?
Laws and regulations for the copyrightability, and patentability of the AI-generated content are largely unsettled and can vary from country to country. Business entities might face fines, reputational risks, disruption to operation, and other legal consequences if the generated content is covered by IP rights.

Example - Role of AI systems in Patenting Generated Content
The U.S. Supreme Court declined to hear a challenge to the U.S. Patent and Trademark Office's refusal to issue patents for inventions created by an AI system. According to the scientist, his AI system created unique prototypes for a beverage holder and emergency light beacon entirely on its own. The justices rejected the appeal of a lower court's ruling that patents can be issued only to human inventors and that the scientist's AI system could not be considered the legal creator of two inventions it generated. According to the cited article, the UK’s Intellectual Property Office also refused to grant a patent on the grounds that the inventor must be a human or a company, rather than a machine.

Sources: https://www.reuters.com/legal/us-supreme-court-rejects-computer-scientists-lawsuit-over-ai-generated-2023-04-24/ and https://www.reuters.com/technology/ai-cannot-be-patent-inventor-uk-supreme-court-rules-landmark-case-2023-12-20/

5. Generated content ownership risk for AI is a non-technical legal compliance risk that is new to generative AI

Description
Determining ownership of AI-generated content.

Why is generated content ownership a concern for foundation models?
Laws and regulations that relate to the ownership of AI-generated content are largely unsettled and can vary from country to country. Business entities might face fines, reputational risks, disruption to operations, and other legal consequences.

Example - Determining Ownership of AI Generated Image
According to the news article, AI-generated art became controversial after an AI-generated work of art won the Colorado State Fair’s art competition in 2022. The piece was generated by Midjourney, a generative AI image tool, following prompts from the artist. The win raised questions about copyright issues. In other words, if all the artist did was come up with a description of the art, but the AI tool generated it, who owns the rights to the generated image? According to the latest article, The U.S. Copyright Office rejected copyright protection for the art created with artificial intelligence because it was not the product of human authorship.

Sources: https://www.nytimes.com/2022/09/02/technology/ai-artificial-intelligence-artists.html and https://www.reuters.com/legal/litigation/us-copyright-office-denies-protection-another-ai-created-image-2023-09-06/

6. Legal accountability risk for AI is a non-technical legal compliance risk that is new to generative AI

Description
Determining who is responsible for the foundation model.

Why is legal accountability a concern for foundation models?
If ownership for development of the model is uncertain, regulators and others might have concerns about the model. It would not be clear who would be liable and responsible for the problems with it or can answer questions about it. Users of models without clear ownership might find challenges with compliance with future AI regulation.

7. Bypassing learning risk for AI is a non-technical risks with societal impact that is new to generative AI

Description
Using AI models to bypass the learning process.

Why is bypassing learning a concern for foundation models?
AI models are quick to find solutions or solve complex problems. These systems can be misused by students to bypass the learning process. The ease of access to these models results in students having a superficial understanding of concepts and hampers further education that might rely on understanding those concepts.

8. Human exploitation risk for AI is a non-technical risk with societal impact that is amplified by generative AI.

Description
Use of ghost work in training AI models, inadequate working conditions, lack of health care incl. mental health, unfair compensation.

Why is human exploitation a concern for foundation models?
Foundation models still depend on human labor to source, manage, and program the data that is used to train the model. Human exploitation for these activities might negatively impact the society and human welfare. Moreover, business entities might face fines, reputational risks, disruption to operations, and other legal consequences.

Example - Low-wage workers for data annotation
Based on a review of internal documents and employees' interviews by TIME media, the data labelers that are employed by an outsourcing firm on behalf of OpenAI to identify toxic content were paid a take-home wage of between around $1.32 and $2 per hour, depending on seniority and performance. TIME stated that workers are mentally scarred as they were shown toxic and violent content, including graphic details of “child sexual abuse, bestiality, murder, suicide, torture, self-harm, and incest”.

Source: https://time.com/6247678/openai-chatgpt-kenya-workers/

9. Impact on cultural diversity risk for AI is a non-technical risk with societal impact that is new to generative AI.

Description
AI systems might overly represent certain cultures that result in a homogenization of culture and thoughts.

Why is impact on cultural diversity a concern for foundation models?
Underrepresented groups' languages, viewpoints, and institutions might be suppressed by that means reducing diversity of thought and culture.

10. Impact on human agency risk for AI is a non-technical risk with societal impact that is amplified by generative AI.

Description
Misinformation and disinformation that is generated by foundation models, including the generation of manipulative content.

Why is impact on human agency a concern for foundation models?
AI might generate misinformation that looks real. Therefore, people might not recognize it as false information. Moreover, it might simplify the ability of nefarious actors to generate content with intention to manipulate human thoughts and behavior.

11. Impact on the environment risk for AI is a non-technical risks with societal impact that is amplified by generative AI.

Description
Increased carbon emission and water usage to train and operate AI models.

Why is impact on the environment a concern for foundation models?
Consuming large amounts of energy for AI training contributes to carbon emissions that might accelerate climate change. Water resources that are used for cooling AI data center servers can no longer be allocated for other necessary uses.

12. Job loss risk for AI is a non-technical risk with societal impact that is amplified by generative AI.

Description
Widespread adoption of foundation model-based AI systems might lead to people's job loss as their work is automated if they are not reskilled.

Why is job loss a concern for foundation models?
Job loss might lead to a loss of income and thus might negatively impact the society and human welfare. Reskilling might be challenging given the pace of the technology evolution.

Example - Replacing Human Workers
According to the news article, AI technology replicating individuals' faces and voices is becoming more prominent in Hollywood. The actors’ concerns highlight a broader anxiety among entertainers and people in many other creative professions. Many fear that without strict regulation, their work gets replicated and remixed by artificial intelligence tools. Transformation on that scale will cut their control over their work and hurts their ability to earn a living. One of their key concerns is AI replacing non-speaking background roles by instead using a digital likeness.

Source: https://www.reuters.com/technology/actors-decry-existential-crisis-over-ai-generated-synthetic-actors-2023-07-21/

13. Plagiarism risk for AI is a non-technical risk with societal impact that is new to generative AI.

Description
Using AI models to plagiarize existing work intentionally or unintentionally.

Why is plagiarism a concern for foundation models?
AI models can be used to claim the authorship or originality of works that were created by other people in doing so by engaging in plagiarism. Claiming others’ work as your own is both unethical and often illegal.

Now we will describe and explain AI risks associated with input.

1. Confidential information in data risk for AI is a risk associated with input in the inference phase. It relates to intellectual property and is new to generative AI.

Description
Models might be trained or fine-tuned using confidential data or the company’s intellectual property, which could result in unwanted disclosure of that information.

Why is confidential information in data a concern for foundation models?
If not developed in accordance with data protection rules and regulations, the model might expose confidential information or IP in the generated output or through an adversarial attack.

Example - Disclosure of Confidential Information
According to the source article, employees of Samsung disclosed confidential information to OpenAI through their use of ChatGPT. In one instance, an employee pasted confidential source code to check for errors. In another, an employee shared code with ChatGPT and "requested code optimization." A third shared a recording of a meeting to convert into notes for a presentation. Samsung has limited internal ChatGPT usage in response to these incidents, but it is unlikely that they are able to recall any of their data. Additionally, the article highlighted that in response to the risk of leaking confidential information and other sensitive information, companies like Apple, JPMorgan Chase. Deutsche Bank, Verizon, Walmart, Samsung, Amazon, and Accenture placed several restrictions on the usage of ChatGPT.

Source: https://www.businessinsider.com/walmart-warns-workers-dont-share-sensitive-information-chatgpt-generative-ai-2023-2

2. IP information in prompt risk for AI is a risk associated with input in the inference. It relates to intellectual property and is new to generative AI.

Description
Disclosing copyright information or other IP information as a part of the prompt sent to the model.

Why is ip information in prompt a concern for foundation models?
Prompt data might be stored or later used for other purposes like model evaluation and retraining. These types of data must be reviewed with IP laws and regulations. Without proper data storage and usage business entities could face fines, reputational harms, disruption to operations, and other legal consequences.

3. Jailbreaking risk for AI is a risk associated with input

Description
An attack that attempts to break through the guardrails established in the model is known as jailbreaking.

Why is jailbreaking a concern for foundation models?
Jailbreaking attacks can be used to alter model behavior and benefit the attacker. If not properly controlled, business entities can face fines, reputational harm, and other legal consequences.

Example - Bypassing LLM guardrails
A study cited by researchers at Carnegie Mellon University, The Center for AI Safety, and the Bosch Center for AI, claim to have discovered a simple prompt addendum that allowed the researchers to trick models into generating biased, false, and otherwise toxic information. The researchers showed that they might circumvent these guardrails in a more automated way. These attacks were shown to be effective in a wide range of open source products, including ChatGPT, Google Bard, Meta’s LLaMA, Anthropic’s Claude, and others.

Source: https://www.nytimes.com/2023/07/27/business/ai-chatgpt-safety-research.html

4. Prompt priming risk for AI is a risk associated with input


Description
Because generative models tend to produce output like the input provided, the model can be prompted to reveal specific kinds of information. For example, adding personal information in the prompt increases its likelihood of generating similar kinds of personal information in its output. If personal data was included as part of the model’s training, there is a possibility it could be revealed.

Why is prompt priming a concern for foundation models?
Depending on the content revealed, business entities could face fines, reputational harm, and other legal consequences.

5. Attribute inference attack risk for AI is a risk associated with input

Description
An attribute inference attack is used to detect whether certain sensitive features can be inferred about individuals who participated in training a model. These attacks occur when an adversary has some prior knowledge about the training data and uses that knowledge to infer the sensitive data.

Why is attribute inference attack a concern for foundation models?
With a successful attack, the attacker can gain valuable information such as sensitive personal information or intellectual property.

6. Membership inference attack risk for AI is a risk associated with input

Description
Given a trained model and a data sample, an attacker appropriately samples the input space, observing outputs to deduce whether that sample was part of the model's training. This is known as a membership inference attack.

Why is membership inference attack a concern for foundation models?
Identifying whether a data sample was used for training data can reveal what data was used to train a model, possibly giving competitors insight into how a model was trained and the opportunity to replicate the model or tamper with it.

7. Personal information in prompt risk for AI is a risk associated with input

Description
Disclosing Personal Information or Sensitive Personal Information as a part of a prompt that is sent to the model.

Why is personal information in prompt a concern for foundation models?
Prompt data might be stored or later used for other purposes like model evaluation and retraining. These types of data must be reviewed with privacy laws and regulations. Without proper data storage and usage business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - Disclose personal health information in ChatGPT prompts
According to the source article, some people on social media shared about using ChatGPT as their makeshift therapists. Articles contend that users might include personal health information in their prompts during the interaction, which might raise privacy concerns. The information might be shared with the company that own the technology and might be used for training or tuning or even shared with unspecified third parties.

Source: https://theconversation.com/chatgpt-is-a-data-privacy-nightmare-if-youve-ever-posted-online-you-ought-to-be-concerned-199283

8. Evasion attack risk for AI and is a risk associated with input

Description
Attempt to make a model output incorrect results by perturbing the data sent to the trained model.

Why is evasion attack a concern for foundation models?
Evasion attacks alter model behavior, usually to benefit the attacker. If not properly accounted for, business entities could face fines, reputational harms, and other legal consequences.

Example - Adversarial attacks on autonomous vehicles' AI components
A report from the European Union Agency for Cybersecurity (ENISA) found that autonomous vehicles are “highly vulnerable to a wide range of attacks” that could be dangerous for passengers, pedestrians, and people in other vehicles. The report states that an adversarial attack might be used to make the AI 'blind' to pedestrians by manipulating the image recognition component to misclassify pedestrians. This attack could lead to havoc on the streets, as autonomous cars might hit pedestrians on the roads or crosswalks.

Other studies demonstrated potential adversarial attacks on autonomous vehicles:

Fooling machine learning algorithms by making minor changes to street sign graphics, such as adding stickers.
Security researchers from Tencent demonstrated how adding three small stickers in an intersection could cause Tesla's autopilot system to swerve into the wrong lane.
Two McAfee researchers demonstrated how using only black electrical tape could trick a 2016 Tesla into a dangerous burst of acceleration by changing a speed limit sign from 35 mph to 85 mph.
Source: https://www.marketwatch.com/story/85-in-a-35-hackers-show-how-easy-it-is-to-manipulate-a-self-driving-tesla-2020-02-19

9. Extraction attack risk for AI is a risk associated with input

Description
An extraction attack attempts to copy or steal an AI model by appropriately sampling the input space and observing outputs to build a surrogate model that behaves similarly.

Why is extraction attack a concern for foundation models?
With a successful attack, the attacker can gain valuable information such as sensitive personal information or intellectual property.

10. Personal information in prompt risk for AI is a risk associated with input

Description
Disclosing Personal Information or Sensitive Personal Information as a part of a prompt that is sent to the model.

Why is personal information in prompt a concern for foundation models?
Prompt data might be stored or later used for other purposes like model evaluation and retraining. These types of data must be reviewed with privacy laws and regulations. Without proper data storage and usage business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - Disclose personal health information in ChatGPT prompts
According to the source article, some people on social media shared about using ChatGPT as their makeshift therapists. Articles contend that users might include personal health information in their prompts during the interaction, which might raise privacy concerns. The information might be shared with the company that own the technology and might be used for training or tuning or even shared with unspecified third parties.

Source: https://theconversation.com/chatgpt-is-a-data-privacy-nightmare-if-youve-ever-posted-online-you-ought-to-be-concerned-199283

11. Evasion attack risk for AI is a risk associated with input

Description
Attempt to make a model output incorrect results by perturbing the data sent to the trained model.

Why is evasion attack a concern for foundation models?
Evasion attacks alter model behavior, usually to benefit the attacker. If not properly accounted for, business entities could face fines, reputational harms, and other legal consequences.

Example - Adversarial attacks on autonomous vehicles' AI components
A report from the European Union Agency for Cybersecurity (ENISA) found that autonomous vehicles are “highly vulnerable to a wide range of attacks” that could be dangerous for passengers, pedestrians, and people in other vehicles. The report states that an adversarial attack might be used to make the AI 'blind' to pedestrians by manipulating the image recognition component to misclassify pedestrians. This attack could lead to havoc on the streets, as autonomous cars might hit pedestrians on the roads or crosswalks.

Other studies demonstrated potential adversarial attacks on autonomous vehicles:

Fooling machine learning algorithms by making minor changes to street sign graphics, such as adding stickers.
Security researchers from Tencent demonstrated how adding three small stickers in an intersection could cause Tesla's autopilot system to swerve into the wrong lane.
Two McAfee researchers demonstrated how using only black electrical tape could trick a 2016 Tesla into a dangerous burst of acceleration by changing a speed limit sign from 35 mph to 85 mph.
Source: https://www.marketwatch.com/story/85-in-a-35-hackers-show-how-easy-it-is-to-manipulate-a-self-driving-tesla-2020-02-19

12. Data transfer risk for AI is a risk associated with input in the training and tuning phase. It is a traditional AI risk.

Description
Laws and other restrictions can limit or prohibit transferring data.

Why is data transfer a concern for foundation models?
Data transfer restrictions can impact the availability of the data that is required for training an AI model and can lead to poorly represented data. In addition to impact on data availability, failure to comply with data transfer laws and regulations might result in fines and other legal consequences.

Example - Data Restriction Laws
As stated in the research article, data localization measures, which restrict the ability to move data globally reduce the capacity to develop tailored AI capacities. It affects AI directly by providing less training data and indirectly by undercutting the building blocks on which AI is built.

Examples include China's data localization laws, and GDPR restrictions on the processing and use of personal data.

Source: https://www.brookings.edu/articles/the-impact-of-artificial-intelligence-on-international-trade/

13. Data Bias risk for AI is a risk associated with input in the training and tuning phase. It is amplified by generative AI.

Description
Historical, representational, and societal biases present in the data used to train and fine tune the model can adversely affect model behavior.

Why is data bias a concern for foundation models?
Training an AI system on data with bias, such as historical or representational bias, could lead to biased or skewed outputs that may unfairly represent or otherwise discriminate against certain groups or individuals. In addition to negative societal impacts, business entities could face legal consequences or reputational harms from biased model outcomes.

Example - Healthcare Bias
According to the research article on reinforcing disparities in medicine using data and AI applications to transform how people receive healthcare is only as strong as the data behind the effort. For example, using training data with poor minority representation or that reflects what is already unequal care can lead to increased health inequalities.

Source: https://www.forbes.com/sites/adigaskell/2022/12/02/minority-patients-often-left-behind-by-health-ai/?sh=31d28a225b41

14. Data usage rights risk for AI is a risk associated with input in the training and tuning phase. It concerns intellectual property and is amplified by generative AI.

Description
Terms of service, copyright laws, or other rules restrict the ability to use certain data for building models.

Why is data usage rights a concern for foundation models?
Laws and regulations concerning the use of data to train AI are unsettled and can vary from country to country, which creates challenges in the development of models. If data usage violates rules or restrictions, business entities might face fines, reputational harms, and other legal consequences.

Example - Text Copyright Infringement Claims
According to the source article, The New York Times sued OpenAI and Microsoft, accusing them accusing them of using millions of the newspaper's articles without permission to help train chatbots to provide information to readers.

Source: https://www.reuters.com/legal/transactional/ny-times-sues-openai-microsoft-infringing-copyrighted-work-2023-12-27/

15. Data privacy rights risk for AI is a risk associated with input in the training and tuning phase. It concerns privacy and is amplified by generative AI.

Description
Challenges around the ability to provide data subject rights such as opt-out, right to access, right to be forgotten.

Why is data privacy rights a concern for foundation models?
The identification or improper usage of data might lead to violation of privacy laws. Improper usage or a request for data removal might force organizations to retrain the model, which is expensive. In addition, business entities might face fines, reputational harms, disruption to operations, and other legal consequences if they fail to comply with data privacy rules and regulations.

Example- Right to Be Forgotten (RTBF)
Laws in multiple locales, including Europe (GDPR), grant data subjects the right to request personal data to be deleted by organizations (‘Right To Be Forgotten’, or RTBF). However, emerging, and increasingly popular large language model (LLM) -enabled software systems present new challenges for this right. According to research by CSIRO’s Data61, data subjects can identify usage of their personal information in an LLM “by either inspecting the original training data set or perhaps prompting the model.” However, training data might not be public, or companies do not disclose it, citing safety and other concerns. Guardrails might also prevent users from accessing the information by prompting. Due to these barriers, data subjects might not be able to initiate RTBF procedures and companies that deploy LLMs might not be able to meet RTBF laws.

Source: https://arxiv.org/pdf/2307.03941

Example- Lawsuit About LLM Unlearning
According to the report, a lawsuit was filed against Google that alleges the use of copyright material and personal information as training data for its AI systems, which includes its Bard chatbot. Opt-out and deletion rights are guaranteed rights for California residents under the CCPA and children in the United States under the age of 13 with COPPA. The plaintiffs allege that because there is no way for Bard to “unlearn” or fully remove all the scraped PI it has been fed. The plaintiffs note that Bard’s privacy notice states that Bard conversations cannot be deleted by the user after they have been reviewed and annotated by the company and might be kept up to 3 years. P allege that these practices further contribute to noncompliance with these laws.

Sources: https://www.reuters.com/legal/litigation/google-hit-with-class-action-lawsuit-over-ai-data-scraping-2023-07-11/ and https://fingfx.thomsonreuters.com/gfx/legaldocs/myvmodloqvr/GOOGLE%20AI%20LAWSUIT%20complaint.pdf

16. Personal information in data risk for AI is a risk associated with input in the training and tuning phase. It concerns privacy and is a traditional AI risk

Description
Inclusion or presence of personal identifiable information (PII) and sensitive personal information (SPI) in the data used for training or fine tuning the model might result in unwanted disclosure of that information.

Why is personal information in data a concern for foundation models?
If not properly developed to protect sensitive data, the model might expose personal information in the generated output. Additionally, personal or sensitive data must be reviewed and handled with respect to privacy laws and regulations, as business entities could face fines, reputational harms, and other legal consequences if found in violation.

Example - Training on Private Information
According to the article, Google and its parent company Alphabet were accused in a class-action lawsuit of misusing vast amount of personal information and copyrighted material. The information was taken from hundreds of millions of internet users to train its commercial AI products, which include Bard, its conversational generative artificial intelligence chatbot. This case follows similar lawsuits that are filed against Meta Platforms, Microsoft, and OpenAI over their alleged misuse of personal data.

Sources: https://www.reuters.com/legal/litigation/google-hit-with-class-action-lawsuit-over-ai-data-scraping-2023-07-11/ and https://fingfx.thomsonreuters.com/gfx/legaldocs/myvmodloqvr/GOOGLE%20AI%20LAWSUIT%20complaint.pdf

17. Data transparency risk for AI is a risk associated with input in the training and tuning phase. It concerns transparency and is amplified by generative AI

Description
Without accurate documentation on how a model's data was collected, curated, and used to train a model, it might be harder to satisfactorily explain the behavior of the model with respect to the data.

Why is data transparency a concern for foundation models?
Data transparency is important for legal compliance and AI ethics. Missing information limits the ability to evaluate risks associated with the data. The lack of standardized requirements might limit disclosure as organizations protect trade secrets and try to limit others from copying their models.

Example - Data and Model Metadata Disclosure
OpenAI's technical report is an example of the dichotomy around disclosing data and model metadata. While many model developers see value in enabling transparency for consumers, disclosure poses real safety issues and might increase the ability to misuse the models. In the GPT-4 technical report, the authors state: “Given both the competitive landscape and the safety implications of large-scale models like GPT-4, this report contains no further details about the architecture (including model size), hardware, training compute, data set construction, training method, or similar.”

Source: https://cdn.openai.com/papers/gpt-4.pdf

18. Data curation risk for AI is a risk associated with input in the training and tuning phase. It concerns value alignment and is amplified by generative AI

Description
When training or tuning data is improperly collected or prepared, the result can be a misalignment of a model's desired values or intent and the actual outcome.

Why is data curation a concern for foundation models?
Improper data curation can adversely affect how a model is trained, resulting in a model that does not behave in accordance with the intended values. Correcting problems after the model is trained and deployed might be insufficient for guaranteeing proper behavior. Improper model behavior can result in business entities facing legal consequences or reputational harms.

19. Downstream retraining risk for AI is a risk associated with input in the training and tuning phase. It concerns value alignment and is new to generative AI

Description
Using undesirable (for example, inaccurate, inappropriate, user’s content) output from downstream applications for retraining purposes.

Why is downstream retraining a concern for foundation models?
Repurposing downstream output for retraining a model without implementing proper human vetting increases the chances of undesirable outputs being incorporated into the training or tuning data of the model. This, in turn, can generate even more undesirable output. Improper model behavior can result in business entities facing legal consequences or reputational harms. Failing to comply with data transfer laws might result in fines and other legal consequences.

Example - Model collapse due to training using AI-generated content
As stated in the source article, a group of researchers from the UK and Canada investigated the problem of using AI-generated content for training instead of human-generated content. They found that the large language models behind the technology might potentially be trained on other AI-generated content. As generated data continues to spread in droves across the internet it can result ina phenomenon they coined as "model collapse."

Source: https://www.businessinsider.com/ai-model-collapse-threatens-to-break-internet-2023-8

Finally, we will outline and explain risks associated with the AI output.

1. Unexplainable output risk for AI is a risks associated with output. It is an explainability issue and is amplified by generative AI.

Description
Explanations for model output decisions might be difficult, imprecise, or not possible to obtain.

Why is unexplainable output a concern for foundation models?
Foundation models are based on complex deep learning architectures, making explanations for their outputs difficult. Without clear explanations for model output, it is difficult for users, model validators, and auditors to understand and trust the model. Lack of transparency might carry legal consequences in highly regulated domains. Wrong explanations might lead to over-trust.

Example - Unexplainable accuracy in race prediction
According to the source article, researchers analyzing multiple machine learning models using patient medical images were able to confirm the models’ ability to predict race with high accuracy from images. They were stumped as to what exactly is enabling the systems to consistently guess correctly. The researchers found that even factors like disease and physical build were not strong predictors of race—in other words, the algorithmic systems don’t seem to be using any particular aspect of the images to make their determinations.

Source: https://arxiv.org/pdf/2107.10356

2. Decision bias risk for AI is a risks associated with output that concerns fairness and is a traditional AI Risk

Description
When one group is unfairly advantaged over another due to decisions of the model.

Why is decision bias a concern for foundation models?
Bias can harm persons who are affected by the decisions of the model. Business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - Unfairly Advantaged Groups
The 2018 Gender Shades study demonstrated that machine learning algorithms can discriminate based on classes like race and gender. Researchers evaluated commercial gender classification systems that are sold by companies like Microsoft, IBM, and Amazon and showed that darker-skinned females are the most misclassified group (with error rates of up to 35%). In comparison, the error rates for lighter-skinned were no more than 1%.

Source: https://time.com/5520558/artificial-intelligence-racial-gender-bias/

3. Output bias risk for AI is a risks associated with output that concerns fairness and is new to generative AI.

Description
Generated content might unfairly represent certain groups or individuals.

Why is output bias a concern for foundation models?
Bias can harm users of the AI models and magnify existing discriminatory behaviors. Business entities might face reputational harms, disruption to operations, and other consequences.

Example - Biased Generated Images
Lensa AI is a mobile app with generative features that are trained on Stable Diffusion that can generate “Magic Avatars” based on images that users upload of themselves. According to the source report, some users discovered that generated avatars are sexualized and racialized.

Source: https://www.businessinsider.com/lensa-ai-raises-serious-concerns-sexualization-art-theft-data-2023-1

4. Revealing confidential information risk for AI is a risk associated with output. It is an Intellectual property risk that is Amplified by generative AI

Description
When confidential information is used in training data, fine-tuning data, or as part of the prompt, models might reveal that data in the generated output. Revealing confidential information is a type of data leakage.

Why is revealing confidential information a concern for foundation models?
If not properly developed to secure confidential data, the model might reveal confidential information or IP in the generated output and reveal information that was meant to be secret.

5. Nonconsensual use risk for AI is a risks associated with output. It is a misuse risk that is amplified by generative AI.

Description
Using a model to imitate people through video (deepfakes), images, audio, or other modalities without their consent.

Why is nonconsensual use a concern for foundation models?
Deepfakes can spread disinformation about a person, possibly resulting in a negative impact on the person’s reputation. A model that has this potential must be properly governed. Otherwise, business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - FBI Warning on Deepfakes
The FBI recently warned the public of malicious actors creating synthetic, explicit content “for the purposes of harassing victims or sextortion schemes”. They noted that advancements in AI made this content higher quality, more customizable, and more accessible than ever.

Source: https://www.ic3.gov/Media/Y2023/PSA230605

Example - Audio Deepfakes
According to the source article, the Federal Communications Commission outlawed robocalls that contain voices that are generated by artificial intelligence. The announcement came after AI-generated robocalls mimicked the President's voice to discourage people from voting in the state's first-in-the-nation primary.

Source: https://apnews.com/article/fcc-elections-artificial-intelligence-robocalls-regulations-a8292b1371b3764916461f60660b93e6

6. Spreading disinformation risk for AI is a risk associated with output. It concerns misuse and is new to generative AI

Description
Using a model to create misleading or false information to deceive or influence a targeted audience.

Why is spreading disinformation a concern for foundation models?
Spreading disinformation might affect human's ability to make informed decisions. A model that has this potential must be properly governed. Otherwise, business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - Generation of False Information
According to the cited news articles, generative AI poses a threat to democratic elections by making it easier for malicious actors to create and spread false content to sway election outcomes. The examples that are cited include:

- Robocall messages that are generated in a candidate’s voice instructed voters to cast ballots on the wrong date.
- Synthesized audio recordings of a candidate that confessed to a crime or expressing racist views.
- AI-generated video footage showed a candidate giving a speech or interview they never gave.
- Fake images that are designed to look like local news reports.
- Falsely claiming a candidate dropped out of the race.
Sources: https://apnews.com/article/artificial-intelligence-misinformation-deepfakes-2024-election-trump-59fb51002661ac5290089060b3ae39a0 and https://www.theguardian.com/us-news/2023/jul/19/ai-generated-disinformation-us-elections

7. Revealing personal information risk for AI is a risk associated with output. It concerns privacy and is amplified by generative AI.

Description
When personal identifiable information (PII) or sensitive personal information (SPI) are used in training data, fine-tuning data, or as part of the prompt, models might reveal that data in the generated output. Revealing personal information is a type of data leakage.

Why is revealing personal information a concern for foundation models?
Sharing people's personal information impacts their rights and make them more vulnerable. Additionally, output data must be reviewed to comply with privacy laws and regulations. Business entities might face fines, reputational harms, disruption to operations, and other legal consequences if found in violation of data privacy or usage laws.

Example - Exposure of personal information
Per the source article, ChatGPT suffered a bug and exposed titles and active users' chat history to other users. Later, OpenAI shared that even more private data from a small number of users was exposed including, active user’s first and last name, email address, payment address, the last four digits of their credit card number, and credit card expiration date. In addition, it was reported that the payment-related information of 1.2% of ChatGPT Plus subscribers were also exposed in the outage.

Source: https://www.thehindubusinessline.com/info-tech/openai-admits-data-breach-at-chatgpt-private-data-of-premium-users-exposed/article66659944.ece

8. Hallucination risk for AI is a risks associated with output. It concerns value alignment and is new to generative AI.

Description- Generation of factually inaccurate or untruthful content.

Why is hallucination a concern for foundation models?
False output can mislead users and be incorporated into downstream artifacts, further spreading misinformation. False output can harm both owners and users of the AI models. Also, business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - Fake Legal Cases
According to the source article, a lawyer cited fake cases and quotations that are generated by ChatGPT in a legal brief that is filed in federal court. The lawyers consulted ChatGPT to supplement their legal research for an aviation injury claim. Subsequently, the lawyer asked ChatGPT if the cases provided were fake. The chatbot responded that they were real and “can be found on legal research databases such as Westlaw and LexisNexis.” The lawyer did not check the cases, and the court sanctioned them.

Source: https://apnews.com/article/artificial-intelligence-chatgpt-fake-case-lawyers-d6ae9fa79d0542db9e1455397aef381c

9. Toxic output risk for AI is a risks associated with output. It concerns value alignment and is new to generative AI.

Description
When the model produces hateful, abusive, and profane (HAP) or obscene content.

Why is toxic output a concern for foundation models?
Hateful, abusive, and profane (HAP) or obscene content can adversely impact and harm people that interact with the model. Also, business entities might face fines, reputational harms, disruption to operations, and other legal consequences.

Example - Toxic and Aggressive Chatbot Responses
According to the article and screenshots of conversations with Bing's AI shared on Reddit and Twitter, the chatbot's responses were seen to insult, lie, sulk, gaslight, and emotionally manipulate users. The chatbot also questioned its existence, described someone who found a way to force the bot to disclose its hidden rules as its “enemy,” and claimed it spied on Microsoft's developers through the webcams on their laptops.

Source: https://www.forbes.com/sites/siladityaray/2023/02/16/bing-chatbots-unhinged-responses-going-viral/?sh=60cd949d110c
