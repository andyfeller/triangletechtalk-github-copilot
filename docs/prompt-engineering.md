# Prompt Engineering

- [GitHub Blog > LLM](#github-blog-llm)
- [OpenAI](#openai)
- [Prompt Engineering Guide](#prompt-engineering-guide)
- [Microsoft](#microsoft)
  - [Azure AI services](#azure-ai-services)
  - [Learn](#learn)
  - [Responsible AI (RAI)](#responsible-ai-rai)

## [GitHub Blog](https://github.blog) > [LLM](https://github.blog/tag/llm/)

- [How we’re experimenting with LLMs to evolve GitHub Copilot](https://github.blog/2023-12-06-how-were-experimenting-with-llms-to-evolve-github-copilot/)
- [The architecture of today’s LLM applications](https://github.blog/2023-10-30-the-architecture-of-todays-llm-applications/)
- [Demystifying LLMs: How they can do things they weren’t trained to do](https://github.blog/2023-10-27-demystifying-llms-how-they-can-do-things-they-werent-trained-to-do/)
- [A developer’s guide to open source LLMs and generative AI](https://github.blog/2023-10-05-a-developers-guide-to-open-source-llms-and-generative-ai/)
- [How to build an enterprise LLM application: Lessons from GitHub Copilot](https://github.blog/2023-09-06-how-to-build-an-enterprise-llm-application-lessons-from-github-copilot/)
- [A developer’s guide to prompt engineering and LLMs](https://github.blog/2023-07-17-prompt-engineering-guide-generative-ai-llms/)
- [Inside GitHub: Working with the LLMs behind GitHub Copilot](https://github.blog/2023-05-17-inside-github-working-with-the-llms-behind-github-copilot/)
- [How GitHub Copilot is getting better at understanding your code](https://github.blog/2023-05-17-how-github-copilot-is-getting-better-at-understanding-your-code/)

## OpenAI

- [OpenAI Platform documentation](https://platform.openai.com/docs/introduction)
  - [Introduction](https://platform.openai.com/docs/introduction)
  - [Models](https://platform.openai.com/docs/models)
  - [Text generation capabilities](https://platform.openai.com/docs/guides/text-generation)
  - [Embeddings capabilities](https://platform.openai.com/docs/guides/embeddings)
  - [Prompt engineering](https://platform.openai.com/docs/guides/prompt-engineering)
  - [Safety best practices](https://platform.openai.com/docs/guides/safety-best-practices)

- Additional OpenAI resources
  - [What is ChatGPT Doing ... and Why Does it Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
  - [Best practices for prompt engineering with OpenAI API](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
  - [openai/openai-cookbook examples](https://github.com/openai/openai-cookbook/tree/main/examples)

## [Prompt Engineering Guide](https://www.promptingguide.ai/)

- [Basics of Prompting](https://www.promptingguide.ai/introduction/basics)
- [Few-shot Prompting](https://www.promptingguide.ai/techniques/fewshot)
- [Retrieval Augmented Generation (RAG)](https://www.promptingguide.ai/techniques/rag)
- [ReAct Prompting](https://www.promptingguide.ai/techniques/react)

## Microsoft

### [Azure AI services](https://learn.microsoft.com/en-us/azure/ai-services/)

- [Microsoft Azure OpenAI Service documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
  - [Red teaming large language models (LLMs)](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming)
  - [Intro to prompt engineering](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering)
  - [Prompt engineering techniques](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/advanced-prompt-engineering?pivots=programming-language-chat-completions)
    - [Citations / Specifying the output structure](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/advanced-prompt-engineering?pivots=programming-language-chat-completions#specifying-the-output-structure)
  - [How-to completions & chat completions](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/chatgpt?tabs=python&pivots=programming-language-chat-completions)

- [Responsible AI overview](https://learn.microsoft.com/en-us/legal/cognitive-services/openai/overview?context=%2Fazure%2Fai-services%2Fopenai%2Fcontext%2Fcontext)

### Learn

- [Microsoft Azure AI Fundamentals: AI Overview](https://learn.microsoft.com/en-us/training/paths/get-started-with-artificial-intelligence-on-azure/)

### Responsible AI (RAI)

Source: [Microsoft](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2)

> Responsible Artificial Intelligence (Responsible AI) is an approach to developing, assessing, and deploying AI systems in a safe, trustworthy, and ethical way. AI systems are the product of many decisions made by those who develop and deploy them. From system purpose to how people interact with AI systems, Responsible AI can help proactively guide these decisions toward more beneficial and equitable outcomes. That means keeping people and their goals at the center of system design decisions and respecting enduring values like fairness, reliability, and transparency.
>
> Microsoft developed a Responsible AI Standard. It's a framework for building AI systems according to six principles: fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability. For Microsoft, these principles are the cornerstone of a responsible and trustworthy approach to AI, especially as intelligent technology becomes more prevalent in products and services that people use every day.
>
> ![Infographic outlining the 6 goals of Microsoft's Responsible AI practices](https://learn.microsoft.com/en-us/azure/machine-learning/media/concept-responsible-ai/concept-responsible-ml.png)
>
> ### [**Fairness and inclusiveness**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2#fairness-and-inclusiveness)
>
> _AI systems should treat everyone fairly and avoid affecting similarly situated groups of people in different ways. For example, when AI systems provide guidance on medical treatment, loan applications, or employment, they should make the same recommendations to everyone who has similar symptoms, financial circumstances, or professional qualifications._
>
> ### [**Reliability and safety**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2#reliability-and-safety)
>
> _To build trust, it's critical that AI systems operate reliably, safely, and consistently. These systems should be able to operate as they were originally designed, respond safely to unanticipated conditions, and resist harmful manipulation. How they behave and the variety of conditions they can handle reflect the range of situations and circumstances that developers anticipated during design and testing._
>
> ### [**Transparency**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2#transparency)
>
> _When AI systems help inform decisions that have tremendous impacts on people's lives, it's critical that people understand how those decisions were made. For example, a bank might use an AI system to decide whether a person is creditworthy. A company might use an AI system to determine the most qualified candidates to hire._
>
> _A crucial part of transparency is interpretability: the useful explanation of the behavior of AI systems and their components. Improving interpretability requires stakeholders to comprehend how and why AI systems function the way they do. The stakeholders can then identify potential performance issues, fairness issues, exclusionary practices, or unintended outcomes._
>
> ### [**Privacy and security**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2#privacy-and-security)
>
> _As AI becomes more prevalent, protecting privacy and securing personal and business information are becoming more important and complex. With AI, privacy and data security require close attention because access to data is essential for AI systems to make accurate and informed predictions and decisions about people. AI systems must comply with privacy laws that:_
>
> - _Require transparency about the collection, use, and storage of data._
> - _Mandate that consumers have appropriate controls to choose how their data is used._
>
> ### [**Accountability**](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2#accountability)
>
> _The people who design and deploy AI systems must be accountable for how their systems operate. Organizations should draw upon industry standards to develop accountability norms. These norms can ensure that AI systems aren't the final authority on any decision that affects people's lives. They can also ensure that humans maintain meaningful control over otherwise highly autonomous AI systems._
