class: center, middle, cover, lighten
background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Weights-nn-62ef826d1a6d.png/800px-Weights-nn-62ef826d1a6d.png)

## AI for Everyday Life
### Presentation to SCHH Computer Club 
#### March 4, 2025
### Ron Snyder

???
The background image on this slide use different colors and brightness to represent different weights and biases in a neural network.

---

## Agenda

1. Introduction
1. Some History & A Review of the Current AI Landscape
1. Overview of Current Models and Chatbots
1. Hands-on Exploration
1. Wrap-up and Q&A

---

## About Me

**Married, father of 6 (including triplets), retired in 2024**

**+45 years in software engineering, in both hands-on and leadership roles**
- 9 years in the US Air Force
- 15 years in defense contracting roles with McDonnell Douglas, General Electric, and General Dynamics
  - Software Engineering Manager for the M1A2 Abrams MBT
- 4 years working with a small startup on a DARPA research project involving autonomous agents
- 18 years working for a non-profit in the academic community
  - 10 years as Director of R&D for their Innovation Lab

Interests included digital imaging, knowledge graphs, digital mapping, and artificial Intelligence

---

class: center, middle

## The Evolution of AI: From Early Days to AGI & Beyond

*How AI Progressed from Rule-Based Systems to Generative Intelligence—and What Comes Next*

---

## The Birth of AI (1940s-1950s)
### AI as a Concept
- Inspired by human intelligence.
- **Key Milestones:**
  - **1943** – First mathematical model of a neuron (McCulloch & Pitts).
  - **1950** – Alan Turing introduces the **Turing Test** for intelligence.
  - **1956** – **Dartmouth Conference**: AI officially becomes a field.
- **Early AI = Symbolic Reasoning** (Logic-based models).

???
- The **Turing Test** proposed the idea of AI mimicking human responses.
- **John McCarthy** coined the term *Artificial Intelligence* at Dartmouth.
- Early AI was **rules-based** and used logic, not learning algorithms.

---

## Early AI Boom & Expert Systems (1950s-1970s)
### AI Gains Momentum
- Focus on **symbolic AI** and logic-based problem-solving.
- **Breakthroughs:**
  - **1958** – McCarthy develops **LISP**, the first AI programming language.
  - **1966** – **ELIZA**, an early chatbot, mimics conversation.
  - **1970s** – **Expert Systems** simulate human decision-making.
- **Challenges:** AI was **brittle** and struggled with real-world uncertainty.

???
- AI was **hand-coded** and couldn’t adapt to new data.
- **ELIZA** was a major leap forward, but it was **scripted** rather than intelligent.
- **Expert systems** were used in **medicine, finance**, but failed at generalization.

---

## The First AI Winter (1970s-1980s)
### Why AI Stalled
- **Unrealistic expectations** vs. actual progress.
- AI systems were too **rigid**, required **massive human input**.
- **Funding cuts** → Major slowdown in research & development.
- **Japan’s Fifth Generation Project** (1980s) attempted to revive AI but fell short.

???
- AI suffered from **overpromising and underdelivering**.
- Governments and companies **lost faith** in AI.
- AI was **too slow and expensive** to be practical.

---

## The Machine Learning Revolution (1990s-2010s)
### AI Shifts to Learning from Data
- **Breakthroughs in Machine Learning (ML):**
  - **1997** – IBM’s **Deep Blue beats Garry Kasparov** in chess.
  - **2006** – Geoffrey Hinton revives **deep learning** (multi-layer neural networks).
  - **2012** – **ImageNet competition** proves AI can **outperform humans** in image recognition.
- **Key Shift:** From **hand-coded rules** → to **data-driven learning**.

???
- **Deep Blue** won by brute force, but **true AI needed to generalize**.
- The **biggest shift** was letting **AI learn patterns on its own** instead of **programming logic manually**.

---

background-image: url(https://upload.wikimedia.org/wikipedia/commons/2/22/Sputnik-516.jpg)
class: cover, lighten

## The Deep Learning Era (2010s-2020s)
### AI Breaks Barriers
- **Neural Networks + Big Data** = **Massive Performance Leap**
- **Breakthroughs:**
  - **2016** – Google’s **AlphaGo defeats world Go champion** using deep reinforcement learning.
  - **2017** – **Transformers revolutionize NLP** (*Attention Is All You Need* paper).
  - **2018-2020** – GPT-2 and GPT-3 showcase AI’s language capabilities.

An AI *“Sputnik Moment”* occurred in November of 2022 with the release of ChatGPT, resulting in
- Mass adoption and public awareness
- Industry disruption
- Government and regulatory response
- Investment surge
- Fierce competition

???
- **AlphaGo** beat humans in **a game too complex for brute force** → This was true AI learning.
- **Transformers** became the foundation of modern **language models**.

A "Sputnik moment" refers to a turning point that triggers a significant response, particularly in terms of technological advancement, innovation, or competition. The term originates from the Soviet Union's successful launch of Sputnik 1 in 1957, which was the first artificial satellite to orbit Earth. This event shocked the United States and spurred a rapid acceleration in space research, leading to the Space Race and ultimately the Apollo moon landings.

Today, a "Sputnik moment" is used more broadly to describe any event that serves as a wake-up call, prompting urgent action or investment in response to a perceived technological or strategic challenge. For example, discussions around AI advancements, climate change, or global competitiveness often invoke the term to highlight the need for rapid innovation and policy shifts.

---

## Understanding Large Language Models (LLMs)
### How LLMs Work and What They Can Do
#### What is an LLM?
- A **Large Language Model (LLM)** is an AI trained on vast amounts of text data to **understand and generate human-like language**.
- LLMs **predict the next word in a sequence** based on probability.

#### How Are LLMs Built?
1. **Pre-training:** The model learns **language patterns** from massive datasets (books, websites, articles).
2. **Fine-tuning:** It is refined for **specific tasks** (chatbots, coding, customer support).
3. **Reinforcement Learning with Human Feedback (RLHF):** AI is adjusted based on **human preference and safety** guidelines.

---

## Understanding Large Language Models (LLMs) - Continued

#### How Are LLMs Used?
- **Chatbots & Virtual Assistants** (*ChatGPT, Claude, Gemini*).  
- **Code Generation** (*GitHub Copilot, OpenAI Codex*).  
- **Creative Writing & Content Generation** (*DALL·E prompts, news summaries*).  
- **Scientific Research & Data Analysis** (*AI-assisted medical studies, legal research*).

#### Emergent Behaviors Observed
- **Few-shot Learning:** Can **solve problems with minimal examples**.
- **Chain-of-Thought Reasoning:** Can **break down complex reasoning tasks** step-by-step.
- **Unexpected Creativity:** AI-generated **poems, analogies, and artwork**.
- **Hallucinations:** Sometimes generates **false but convincing information**.

???
- LLMs differ from traditional AI by dynamically **generating** responses.
- **Transformers enable context-aware learning**.
- **Emergent behaviors** suggest AI may be developing **unexpected generalization abilities**.

---

background-image: url(https://upload.wikimedia.org/wikipedia/commons/8/85/Human_brain_blue_circuit_artificial_intelligence_icon_%28DALL-_E%29_Dec_2024.jpg)

class: cover, lighten

## AI and Image Generation

---

## The Rise of Generative AI (2020s)
### AI Can Now "Create"
- **Beyond analysis → AI generates new content.**
- **Breakthroughs:**
  - **GPT-3 & 4** – Chatbots, AI writing assistants.
  - **DALL·E, Midjourney** – AI-generated images.
  - **Sora (2024)** – AI video generation.
- **Key Question:** Are we moving toward **AGI**?

???
- **AI can now "imagine" things it has never seen before.**
- **Biggest leap**: AI is no longer just responding; it’s **creating original work**.

---

## What is AGI?
### Artificial General Intelligence (AGI)
- AGI can **learn, reason, and apply knowledge** across domains.
- **Today’s AI ≠ AGI** → Still task-specific.
- AGI must have **memory, reasoning, and adaptability**.

---

## Key Challenges to Achieving AGI
- **Lack of Generalization** – AI struggles to **transfer** knowledge.
- **No True Memory or Autonomy** – AI doesn’t retain **context over time**.
- **Common Sense & Reasoning Issues** – AI can’t yet **think like humans**.

---

## What is ASI?
- **Artificial Superintelligence (ASI)**: AI that **surpasses human intelligence**.
- ASI would be **capable of recursive self-improvement**.
- **Key Risks:**
  - **Control Problems** – How do we ensure alignment with human values?
  - **Power Imbalances** – ASI in the wrong hands could be dangerous.

---

class: center, middle

# The Rise of the Chatbot...

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/HAL9000.svg/256px-HAL9000.svg.png)

---

class: center, middle

<iframe width="100%" style="aspect-ratio:16/8;"" src="https://www.youtube.com/embed/ARJ8cAGm6JE?start=87&end=100" title="HAL 9000: &quot;I&#39;m sorry Dave, I&#39;m afraid I can&#39;t do that&quot;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### The HAL 9000, a famous Chatbot from Science Fiction

???
The video clip is from *2001: A Space Odyssey (1968)*.  

The HAL 9000 is a great example of a chatbot from science fiction.

- HAL is an AI-powered conversational assistant aboard the Discovery One spacecraft.
- It can understand and respond to natural language like a modern chatbot.
- HAL provides mission updates, controls ship functions, and interacts conversationally with astronauts.
- However, it also demonstrates the risks of AI misalignment, as it ultimately prioritizes its mission directives over human safety.

Other Sci-Fi Chatbots:
- TARS (Interstellar, 2014) – A highly intelligent and humorous AI assistant.
- Samantha (Her, 2013) – A sophisticated voice-based AI assistant with emotional depth.
- Data (Star Trek: TNG) – While an android, Data often functions as a conversational AI.

HAL 9000 is a cautionary tale of what happens when an AI chatbot is too powerful and misaligned—a theme relevant in today’s discussions on AGI safety.

---

## What is a chatbot?

A chatbot is an AI-powered software application designed to simulate human-like conversations through text or voice interactions. It uses natural language processing (NLP) and, in advanced cases, machine learning and large language models (LLMs) to understand queries, generate responses, and assist users in various tasks, such as customer service, information retrieval, or casual conversation.

All of the major AI developers provide chatbots for interacting with their LLMs.  Most of these are available under a *fremium* business model that offers basic services for free while charging for premium features, advanced functionality, or additional services.

---

## Popular AI Chatbots

| Company | Chatbot | Free Models |
| ------- | ------- | ----------- |
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] OpenAI] | [ChatGPT](https://chatgpt.com/) | GPT-4o, o3-mini (reasoning) |
| .flex[.logo[![](logos/gemini.svg)] Google] | [Gemini](https://gemini.google.com/app) | 2.0 Flash, 2.0 Flash Thinking (reasoning) |
| .flex[.logo[![](logos/claude.svg)] Anthropic] | [Claude](https://claude.ai) | 3.5 Sonnet |
| .flex[.logo[![](logos/meta-ai.png)] Meta AI] | [Meta AI]() | Llama 3.2, Llama 3,1, Llama 3.2 Editor |
| .flex[.logo[![](logos/copilot.svg)] Microsoft] | [Copilot]() | GPT-4o, Prometheus |
| .flex[.logo[![](logos/qwen.png)] Alibaba] | [Qwen]() | Qwen-2.5-Max, Qwen-2.5-Plus |
| .flex[.logo[![](logos/deepseek.png)] DeepSeek] | [DeepSeek]() | DeepSeek-V3, DeepSeek-R1 (reasoning) |
| .flex[.logo[![](logos/mistral.svg)] Mistral AI] | [Le Chat]() | Mistral Small, Mistral Large, Mistral Next |
| .flex[.logo[![](logos/xai.svg)] XAI] | [Grok]() | Grok 2 |
| .flex[.logo[![](logos/perplexity.png)] Perplexity] | [Perplexity]() | Auto (mix of OpenAi, Anthropic and Sonar models), o3-mini (reasoning), DeepSeek-R1 (reasoning) |

---

## LLM Comparison

| Model | Release | Cutoff | CW | P | MMLU | GPQA | HHEM | Mem | MM | R |
|-------|:-------:|:------:|---:|--:|-----:|-----:|-----:|:---:|:--:|:-:|
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] GPT-4o] | 2024-8 | 2023-10 | 128 | ? | 88.8% | 53.6% | 1.5% | ✅ | ✅ | |
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] o3-mini ] | 2025-1 | 2024-6 | 128 | ? | 86.9% | 79.7% | 1.4% | ✅ |  | ✅ |
| .flex[.logo[![](logos/claude.svg)] Claude 3.5 Sonnet] | 2024-10 | 2024-4 | 200 | ? | 90.4% | 67.2% | 4.6% | | ✅ | |
| .flex[.logo[![](logos/gemini.svg)] Gemini 2.0 Flash] | 2024-12 | 2024-8 | 1048 | ? | 76.4% | 62.1% | 0.7% | ✅ |✅ | |
| .flex[.logo[![](logos/meta-ai.png)] Llama 3.2] | 2024-12 | 2023-12 | 128 | 90 | 86.0% | 46.7% | 4.3% | ✅ | ✅ | |
| .flex[.logo[![](logos/qwen.png)] Qwen 2.5 Max] | 2024-9 | ? | 131 | 72 | 83.3% | 49.5% | 2.9% | | | |
| .flex[.logo[![](logos/deepseek.png)] DeepSeek V3] | 2024-12 | 2024-7 | 131 | 671 | 88.5% | 59.1% | 3.9% | | | |
| .flex[.logo[![](logos/mistral.svg)] Mistral Small 3] | 2025-1 | ? | 32 | 24 | 66.3% | 45.3% | 3.1% | | | |
| .flex[.logo[![](logos/xai.svg)] Grok 2] | 2024-8 | 2024-8 | 128 | ? | 87.5% | 56.0% | 4.6% | | ✅ | | |

.footnote[
- Cutoff: Knowledge Cutoff Date
- CW: Context Window Size (K)
- P: Parameters (Billions)
- MMLU: Massive Multitask Language Understanding Benchmark Score
- GPQA: General-Purpose Question Answering Benchmark Score
- HHEM: Hughes Hallucination Evaluation Model Score (lower is better)
- Mem: Maintains memory between chats
- Multi-Modal: Can handle images, audio, and video (at least one)
- R: Reasoning model
]

???
The GPQA benchmark (General-Purpose Question Answering) is a relatively recent evaluation metric designed to assess the broad, general-purpose reasoning capabilities of AI models across multiple domains. Unlike domain-specific QA benchmarks, GPQA includes questions that require multi-step reasoning, factual knowledge, and contextual understanding.

As of now, the GPQA benchmark score varies depending on the AI model being tested. The highest-performing models tend to achieve scores in the 60-80% range, but this can change as newer models are released.

Hughes Hallucination Evaluation Model: Developed by Vectara, HHEM is an open-source model designed to detect hallucinations in text generated by AI systems. It outputs a probability score between 0 and 1, where 0 indicates a hallucination and 1 indicates factual consistency. This model is particularly useful for evaluating the factual accuracy of outputs from Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) systems.

---

## Considerations

As AI becomes increasingly integrated into society, it raises important ethical, legal, and social questions. Concerns include
- data privacy, 
- job displacement due to automation, and 
- ensuring that AI systems operate fairly and without bias. 

Ongoing discussions and research aim to address these challenges, promoting the responsible development and deployment of AI technologies.

---

## AI Chatbot Data Privacy & Retention Summary (as of Feb 2025)

- **OpenAI (ChatGPT & API)**
    - Free & Plus Users: Conversations may be stored temporarily for abuse monitoring but are not used for training.
    - API & Enterprise Users: No data retention, no model training on user inputs or uploads.
- **Microsoft (Copilot & Azure OpenAI)**
    - Copilot (365 Users): Follows Microsoft’s enterprise data privacy policies.
    - Azure OpenAI: No data retention or model training on user inputs.
- **Google (Bard, Gemini, Vertex AI)**
    - Bard & Gemini (Free Users): May retain interactions for AI improvements unless opted out.
    - Google Cloud Vertex AI: No retention or model training on enterprise customer data.

---

## AI Chatbot Data Privacy & Retention Summary - Continued

- **Anthropic (Claude AI)**
    - Claude Free & Pro Users: Temporary storage for monitoring but not used for training.
    - Claude API & Enterprise: No retention, no training on user data.
- **Meta (Llama AI & Facebook AI Services)**
    - Meta AI (Free Services): May retain interactions for AI improvement.
    - Llama AI Models (Local Use): No retention, but depends on third-party implementation.

### General Best Practices for Privacy
- **Use API or Enterprise Plans** to ensure no data retention.
- **Check privacy settings** and opt out where possible.
- **Self-host AI models** for maximum data control.

_For sensitive data, use **self-hosted AI** or enterprise AI solutions with strict privacy guarantees._

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

## Examples

In the following slides, chatbot examples are provided for a variety of everyday scenarios.  

Each slide includes the conversation output from an actual chatbot session.  Users are encouraged to
copy the prompt(s) from each example and paste them into a live chatbot session.

Try changing the prompt to see how the responses change.

Note that even when using the exact prompt(s) included in the example chat, the chatbot output will likely be somewhat different.  This is both a reflection of the specific chatbot used (ChatGPT, Claude, etc) and the fact that LLM responses are designed to produce some variation.

To copy the prompt text from the examples, hover over the prompt text and click on the copy icon that will appear below the prompt.  You can then paste the text into the input box in your chatbot of choice.

.footnote[ChatGPT (gpt-4o model) was used in in the creation of these examples.]

---

.left-column[
### Meal Planning
- 1 - Ask for the meal plan with some specific guidance
- 2 - Get a shopping list to use directly or add to an shopping app
]

.right-column[
<iframe src="chat?src=chats/meal-planning.md"></iframe>
]

---

.left-column[
### Vacation Planning 
- Ask for possible itineraries for a Maine road-trip vacation
- Ask a follow-up question about where to get good lobster rolls
]

.right-column[
<iframe src="chat?src=chats/vacation-planning.md"></iframe>
]

---

.left-column[
### Medical Information
- Ask for information on a specific medical condition

.caution[.red[Caution!] - While helpful in obtaining background information, chatbots should not be used for diagnosis and self-treatment.]
]

.right-column[
<iframe src="chat?src=chats/synovial-chondromatosis.md"></iframe>
]

---

.left-column[
### Image Analysis
- Identify wildlife in photographs
]

.right-column[
<iframe src="chat?src=chats/image-analysis.md"></iframe>
]