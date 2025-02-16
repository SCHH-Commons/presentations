class: center, middle, cover, lighten
background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Weights-nn-62ef826d1a6d.png/800px-Weights-nn-62ef826d1a6d.png)

## AI for Everyday Life
### Presentation to SCHH Computer Club 
#### March 4, 2025
### Ron Snyder

???
The background image on this slide use different colors and brightness to represent different weights and biases in a neural network.

---

.left-column[
### Meal-planning example
- Ask for the meal plan with some specific guidance
- Get a shopping list to use directly or add to an shopping app
]

.right-column[
<iframe src="chat?src=chats/chat-1.md"></iframe>
]

---

## Agenda

1. Introduction
1. Some History & A Review of the Current AI Landscape
1. Uses of AI in Everyday Life
1. Hands-on Exploration
1. Wrap-up and Q&A

---

## About Me

**Married, father of 6 (including triplets), retired in 2024**

**+45 years in software engineering, in both hands-on and management roles**
- 9 years in the US Air Force
- 15 years in various defense contracting roles with McDonnell Douglas, General Electric, and General Dynamics
  - Software Engineering Manager for the M1A2 Abrams MBT
- 4 years working with a small startup on DARPA autonomous agents research project
- 18 years working for a non-profit in the academic community
  - 10 years as director of R&D for their innovation Lab

Interests included digital imaging, knowledge graphs, digital mapping, and artificial Intelligence

---

## What is Artificial Intelligence

Artificial Intelligence (AI) refers to the capability of machines, particularly computer systems, to perform tasks that typically require human intelligence.

These tasks include understanding language, recognizing patterns, solving problems, and making decisions.

AI encompasses a range of technologies and approaches, enabling machines to learn from experience, adapt to new inputs, and execute human-like functions. 

---

## Key Components of AI

1. **Machine Learning (ML):** A subset of AI that involves training algorithms to learn from and make predictions based on data, improving their performance over time without explicit programming. 
2. **Neural Networks:** Computational models inspired by the human brain’s structure, consisting of interconnected nodes (neurons) that process information in layers to recognize patterns and make decisions.
3. **Natural Language Processing (NLP):** The ability of machines to understand, interpret, and generate human language, enabling interactions through speech and text.
4. **Computer Vision:** The capability of machines to interpret and process visual information from the world, such as images and videos.

---

## Some Applications of AI

- **Virtual Assistants:** Tools like Siri, Alexa, and Google Assistant that understand and respond to voice commands, assisting users with various tasks.
- **Autonomous Vehicles:** Self-driving cars that utilize AI to navigate roads, interpret traffic conditions, and make real-time driving decisions.
- **Healthcare Diagnostics:** AI systems that analyze medical data to assist in diagnosing diseases and recommending treatments.
- **Recommendation Systems:** Algorithms that suggest products, services, or content to users based on their preferences and behavior, commonly used by platforms like Netflix and Amazon.

---

## Popular AI Chatbots

| Company | Chatbot | Free Models |
| ------- | ------- | ----------- |
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] OpenAI] | [ChatGPT](https://chatgpt.com/) | GPT-4o, o3-mini (reasoning) |
| .flex[.logo[![](images/gemini.svg)] Google] | Gemini | 2.0 Flash, 2.0 Flash Thinking (reasoning) |
| .flex[.logo[![](images/claude.svg)] Anthropic] | Claude | 3.5 Sonnet |
| .flex[.logo[![](images/meta-ai.png)] Meta AI] | Meta AI | Llama 3.2, Llama 3,1, Llama 3.2 Editor |
| .flex[.logo[![](images/copilot.svg)] Microsoft] | Copilot | GPT-4o, Prometheus |
| .flex[.logo[![](images/qwen.png)] Alibaba] | Qwen | Qwen-2.5-Max, Qwen-2.5-Plus |
| .flex[.logo[![](images/deepseek.png)] DeepSeek] | DeepSeek | DeepSeek-V3, DeepSeek-R1 (reasoning) |
| .flex[.logo[![](images/mistral.svg)] Mistral AI] | Le Chat | Mistral Small, Mistral Large, Mistral Next |
| .flex[.logo[![](images/perplexity.png)] Perplexity] | Perplexity| Auto (mix of OpenAi, Anthropic and Sonar models), o3-mini (reasoning), DeepSeek-R1 (reasoning) |

---

## Considerations

As AI becomes increasingly integrated into society, it raises important ethical, legal, and social questions. Concerns include
- data privacy, 
- job displacement due to automation, and 
- ensuring that AI systems operate fairly and without bias. 

Ongoing discussions and research aim to address these challenges, promoting the responsible development and deployment of AI technologies.

---

background-image: url(https://upload.wikimedia.org/wikipedia/commons/2/22/Sputnik-516.jpg)
class: cover, lighten

## A Brief History of AI

**1950s-1980s:** Rule-based AI (if-then logic)  
**1990s-2010s:** Machine Learning revolution  
**2020s:** Deep learning & Chatbots (ChatGPT, Gemini, Claude)  

An AI *“Sputnik Moment”* occurred in November of 2022 with the release of ChatGPT, resulting in
- Mass adoption and public awareness
- Industry disruption
- Government and regulatory response
- Investment surge
- Fierce competition

???

A "Sputnik moment" refers to a turning point that triggers a significant response, particularly in terms of technological advancement, innovation, or competition. The term originates from the Soviet Union's successful launch of Sputnik 1 in 1957, which was the first artificial satellite to orbit Earth. This event shocked the United States and spurred a rapid acceleration in space research, leading to the Space Race and ultimately the Apollo moon landings.

Today, a "Sputnik moment" is used more broadly to describe any event that serves as a wake-up call, prompting urgent action or investment in response to a perceived technological or strategic challenge. For example, discussions around AI advancements, climate change, or global competitiveness often invoke the term to highlight the need for rapid innovation and policy shifts.

---

## AI Terms

- **Artificial Intelligence (AI):** Machines that mimic human intelligence
    - **ANI (Narrow AI):** Focused on specific tasks (e.g., Alexa, ChatGPT) - Today
    - **AGI (General AI):** Hypothetical AI with human-level intelligence - “Near-term” goal
    - **ASI (Superintelligence):** Hypothetical AI surpassing human intelligence 
    - **Technological Singularity:** A hypothetical future point where technological growth becomes uncontrollable and irreversible
- **LLMs (Large Language Models):** AI trained on vast amounts of text
- **RAG (Retrieval-Augmented Generation):** AI that retrieves and considers external information before responding
    - RAG sources can include the web and proprietary data sources
    - Enables citations for documents used to generate responses and can reduce hallucination
- **Multi-modal AI:** AI that can process text, images, audio, and video
- **Hallucination:** When AI generates incorrect or misleading information but presents it as fact (“confidently wrong”)

---

## Types of LLM

- **General purpose** - These LLMs are designed for broad applications such as chatbots, content creation, and general problem-solving.
    - Proprietary Models (Closed-Source) - These are developed and controlled by companies, often requiring paid access.
    - Open-Source - These models are available for public use and modification.
- **Specialized** - These models are fine-tuned for specific domains.
    - Code Generation
    - Scientific and Medical
- **Multi-modal** - These models are able to process audio, images and video in addition to text
- **Reasoning** - These models able to perform complex, structured problem-solving tasks

---

## AI Hallucinations – When AI Gets It Wrong

AI sometimes "hallucinates" — makes up facts

Example: AI confidently says, “The Eiffel Tower is in London.”

Why?
- AI predicts text based on patterns, but it doesn’t understand facts
- It may generate plausible-sounding but false information

---

## AI in Everyday Life

- **Smart Assistants:** Alexa, Siri, Google Assistant
- **Writing & Research:** ChatGPT, Grammarly
- **AI-Generated Art & Music**
- **Translation Tools:** Google Translate
- **Planning & Organization:** AI for travel, scheduling, reminders

---

## Chatbot Prompting

A good chatbot prompt is clear, concise, specific, and provides enough context to guide the AI model towards generating a relevant and accurate response; it should be phrased in a way that is easy for the chatbot to understand, avoiding ambiguity and unnecessary jargon, while also potentially including details like the desired tone or format of the answer. 

Key elements of a good chatbot prompt:
- **Clarity:** Use simple language and avoid complex sentence structures. 
- **Specificity:** Clearly state what information you need, including important details and parameters. 
- **Context:** Provide relevant background information to help the chatbot understand the situation. 
- **Conciseness:** Keep the prompt short and to the point, focusing on the essential elements. 
- **Appropriate Tone:** Set the tone for the response by indicating whether you want a formal, casual, or informative answer. 

---

## Chatbot Prompting

### Examples of good chatbot prompts:
- "Explain the concept of artificial intelligence in simple terms." 
- "Recommend a family-friendly restaurant near downtown Chicago." 
- "Write a short poem about the beauty of nature, using imagery of a sunset." 
- "What are the side effects of taking medication X?" 
- "Summarize the key points of this article about climate change." 

### What to avoid in a chatbot prompt:
- Ambiguity: "Tell me something interesting" (too vague) 
- Jargon: "What is the ROI of this marketing campaign?" (may not be understood by the chatbot) 
- Open-ended questions: "What do you think about this?" (may lead to irrelevant responses) 
- Excessive complexity: "Provide a detailed analysis of the economic impact of the recent trade war, including historical data and potential future scenarios." (too much information at once) 

---

name: test
class: chat

## Example: Simple prompt

--

template: test

.prompt[
Tell me about Sun City
]

--

template: test

.response[
<iframe src="md?src=examples/example-1.md"></iframe>
]

---

name: test
class: chat

## Example: Simple prompt

--

template: test

.prompt[
You are a helpful assistant.  
- You are an expert on Sun City Hilton Head.
- You return all answers in markdown
]

--

template: test

.response[
<iframe src="md?src=examples/example-1.md"></iframe>
]

---