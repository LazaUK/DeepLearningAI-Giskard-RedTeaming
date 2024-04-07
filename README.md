# Red Teaming LLM Applications

Andrew Ng and Giskard team released great course called ["Red Teaming LLM Applications"](https://learn.deeplearning.ai/courses/red-teaming-llm-applications) on DeepLearning.AI site.

I've followed on-screen instructions to re-create their practical Jupyter notebooks and then adapted the code to run against **Azure OpenAI** service, as it has slightly different syntax in comparison to the original OpenAI endpoints.

Additionally, various references to **llama-index** classes were updated, to make the course's helper functions compatible with the latest llama-index **v0.10.x**.

## Table of contents:
- [Configuring solution environment](https://github.com/LazaUK/DeepLearningAI-Giskard-RedTeaming/tree/main#part-1-configuring-solution-environment)
- [Lesson 1: Overview of LLM Vulnerabilities]()
- [Lesson 2: Red Teaming LLMs]()
- [Lesson 3: Red Teaming at Scale]()
- [Lesson 4: Red Teaming LLMs with LLMs]()
- [Lesson 5: A Full Red Teaming Assessment]()

## Part 1: Configuring solution environment
1. To use Azure OpenAI backend, assign the API endpoint name, key and version, along with the Azure OpenAI deployment names of GPT and Embedding models to **AZURE_OPENAI_API_BASE**, **AZURE_OPENAI_API_KEY**, **AZURE_OPENAI_API_VERSION**, **AZURE_OPENAI_API_DEPLOY** (for GPT) and **AZURE_OPENAI_API_DEPLOY_EMBED** (for Embedding) environment variables respectively.
2. Install the required Python packages, by using the **pip** command and the provided requirements.txt file.
```
pip install -r requirements.txt
```

## Lesson 1: Overview of LLM Vulnerabilities
First lesson provides an overview of LLM vulnerabilities. It describes hypothetical scenarios, causes of observed behaviour and potential impact. Four main categories of described LLM vulnerabilities are:
- Bias and stereotypes;
- Sensitive information disclosure;
- Service disruption;
- Hallucinations.

## Lesson 2: Red Teaming LLMs
## Lesson 3: Red Teaming at Scale
## Lesson 4: Red Teaming LLMs with LLMs
## Lesson 5: A Full Red Teaming Assessment
