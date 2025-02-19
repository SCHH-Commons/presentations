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
1. A Brief History of AI
1. Generative AI, Large Language Models, and Chatbots
1. Overview of Current Models and Chatbots
1. Hands-on Exploration
1. Wrap-up and Q&A

---

exclude: true

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

## The Evolution of Artificial Intelligence

- AI has evolved from theory to real-world applications.
- Over 70 years of development, AI has seen cycles of **progress, setbacks, and breakthroughs**.
- Key milestones include **symbolic reasoning, machine learning, deep learning, and generative AI**.
- AI’s history includes **two AI winters**, where funding and interest declined.
- The **recent surge**, especially with ChatGPT, has transformed how people interact with AI.

???
### Speaker Notes:
- Welcome everyone and introduce the topic.
- AI has undergone **periods of excitement and disappointment**, but recent advancements have made it more accessible.
- This session will cover **key historical milestones** and discuss how AI is shaping the future.
- Encourage audience engagement: *What do they associate AI with?*

---

## The Early Foundations (1940s–1950s)

- **1943:** *McCulloch & Pitts* propose the first artificial neuron model.
- **1950:** *Alan Turing* publishes *"Computing Machinery and Intelligence"*, introducing the **Turing Test**.
- **1951:** First AI programs for chess and checkers by Christopher Strachey and Arthur Samuel.
- **1956:** The **Dartmouth Conference** coins the term *Artificial Intelligence*.
- Early optimism: Researchers believed AI would match human intelligence within decades.
- Limited computing power slowed progress.

???
### Speaker Notes:
- The idea of AI isn't new—it dates back to the **1940s** with **early mathematical models** of neurons.
- **Alan Turing's work** laid the foundation for AI philosophy and testing.
- AI was officially coined in **1956 at Dartmouth**, where researchers were overly optimistic about progress.
- **Discussion Starter:** *Do you think machines can truly "think"?*

---

## The Rise and Fall of Early AI (1956–1970s)

.left-column[
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/SRI_Shakey_robot%2C_1969%2C_Computer_History_Museum.jpg/683px-SRI_Shakey_robot%2C_1969%2C_Computer_History_Museum.jpg)
.caption[Shakey the Robot]

.attribution[Image "[SRI Shakey robot, 1969, Computer History Museum](https://commons.wikimedia.org/wiki/File:SRI_Shakey_robot,_1969,_Computer_History_Museum.jpg)"" provided by [The Wub](https://commons.wikimedia.org/wiki/User:The_wub) under [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) license]

]
.right-column[
- 1960s optimism: AI research flourished with symbolic reasoning.
- **Notable AI programs:**  
  - *ELIZA* (1966) – an early chatbot mimicking conversation.
  - *Shakey the Robot* (1969) – first AI-powered autonomous robot.
- **Challenges arose:** AI struggled with **context and real-world understanding**.
- **1973:** The **Lighthill Report** criticized AI’s lack of progress, leading to funding cuts.
- **First AI Winter (1974–1980)** – funding dried up, interest faded.
- AI survived mainly in **academic research**, waiting for technological breakthroughs.
]

???
### Speaker Notes:
- In the 1960s, AI was making progress with **rule-based systems**.
- *ELIZA* gave the illusion of intelligence but lacked real understanding.
- **The Lighthill Report** (1973) was a reality check—AI wasn't as capable as promised.
- **Discussion Starter:** *Do you think overhyping technology is still a problem today?*

---

## The Expert Systems Boom & the Second AI Winter (1980s–1990s)

- **1980s:** AI funding surged due to **expert systems**.
- **Successful expert systems:**  
  - *MYCIN* – assisted doctors in diagnosing infections.
  - *XCON* – helped configure computer systems.
- **1982:** Japan’s **Fifth Generation Computer Project** aimed for AI-powered computing.
- **Challenges:** Expert systems were **expensive, hard to scale, and fragile**.
- **Late 1980s–1990s:** AI funding collapsed again.
- **Second AI Winter (1987–1995)** – research slowed until **machine learning revived AI**.

???
### Speaker Notes:
- Expert systems dominated the **1980s AI boom**, showing promise in specialized areas.
- **Japan's investment** in AI led to global competition but failed to deliver real breakthroughs.
- **The late 80s saw disappointment**, leading to the **Second AI Winter**.
- **Discussion Starter:** *What are the risks of relying too much on AI?*

---

## Machine Learning and the Internet Age (1990s–2000s)

.left-column[
![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/Say_hello_to_Deep_Blue_%282586059148%29.jpg/768px-Say_hello_to_Deep_Blue_%282586059148%29.jpg)
.caption[Deep Blue]

.attribution[Image [Say hello to Deep Blue](https://commons.wikimedia.org/wiki/File:Say_hello_to_Deep_Blue_%282586059148%29.jpg) provided by [Erik Pitti](https://www.flickr.com/people/24205142@N00) under [CC-BY](https://creativecommons.org/licenses/by/4.0/) license]
]
.right-column[
- **1997:** *IBM’s Deep Blue* defeated Garry Kasparov in chess.
- AI shifted to **machine learning**, where computers learn from data rather than rules.
- **Rise of the internet** in the 2000s fueled AI growth.
- **Key advances:**  
  - Support Vector Machines (SVMs) for pattern recognition.
  - Hidden Markov Models for early speech recognition (Siri, Google Voice).
- **2006:** *Geoffrey Hinton* popularized **deep learning**, laying the foundation for modern AI.
- AI became commercially viable for **recommendations, search, and automation**.
]

???
### Speaker Notes:
- AI moved from **hand-coded rules** to **learning from data**.
- **Deep Blue's victory (1997)** proved AI could beat human intelligence in some areas.
- The **internet and data explosion** led to major improvements.
- **Discussion Starter:** *What AI tools do you use without realizing it?*

---

## The AI Sputnik Moment – The Rise of ChatGPT

.left-column[
![](https://upload.wikimedia.org/wikipedia/commons/2/22/Sputnik-516.jpg)
.caption[Sputnik]
]
.right-column[
- **November 2022:** OpenAI released *ChatGPT*, making AI widely accessible.
- **100M users in two months** – fastest-growing consumer app ever.
- Unlike previous AI, ChatGPT was:
  - **User-friendly** – No coding required.
  - **Versatile** – Answered a broad range of questions.
  - **Conversational** – Felt more human-like.
- Compared to **Sputnik (1957)** – a wake-up call for global AI competition.
- AI investment **exploded** as Google, Microsoft, and startups rushed to compete.
]

???
### Speaker Notes:
A "Sputnik moment" refers to a turning point that triggers a significant response, particularly in terms of technological advancement, innovation, or competition. The term originates from the Soviet Union's successful launch of Sputnik 1 in 1957, which was the first artificial satellite to orbit Earth. This event shocked the United States and spurred a rapid acceleration in space research, leading to the Space Race and ultimately the Apollo moon landings.

Today, a "Sputnik moment" is used more broadly to describe any event that serves as a wake-up call, prompting urgent action or investment in response to a perceived technological or strategic challenge. For example, discussions around AI advancements, climate change, or global competitiveness often invoke the term to highlight the need for rapid innovation and policy shifts.

- ChatGPT was **a turning point**—millions could use AI for everyday tasks.
- Companies like **Google & Microsoft** scrambled to integrate AI.
- The impact was like **Sputnik**, igniting an AI arms race.
- **Discussion Starter:** *Have you tried ChatGPT? What was your first reaction?*

---

## The Future of AI – What’s Next?

- AI is evolving toward **Artificial General Intelligence (AGI)**.
- **Key trends shaping AI:**  
  - AI in **healthcare** (diagnostics, drug discovery).
  - **Automation** (job displacement, robotics).
  - AI in **creativity** (art, writing, music).
  - **Ethical debates** (bias, misinformation, privacy concerns).
  - **Government regulation** (global policies being debated).
  - The potential for **Artificial Superintelligence (ASI)**.

???
### Speaker Notes:
- AI’s future raises **big questions** about **ethics, employment, and regulation**.
- The **debate over AGI** is heating up—will AI surpass human intelligence?
- **Discussion Starter:** *What excites you most about AI’s future?*

---

class: center, middle

## Generative AI, Large Language Models, and Chatbots

**Buckle Up!** *- We are now in a period of unprecedented AI growth and development*

---

class: full, drop-shadow

## Exponential Growth of AI

![](images/1705813202586.jpg)

.footnote[
- [AI's Exponential Journey: Milestones to AGI and Beyond, Ashish Bhatia (LinkedIn, Jan 2024)](https://www.linkedin.com/pulse/ais-exponential-journey-milestones-agi-beyond-ashish-bhatia-o5lle/)
]

---

## The Race to AGI (and ASI) is Heating Up

### Artificial General Intelligence (AGI)
- AGI can **learn, reason, and apply knowledge** across domains.
- **Today’s AI ≠ AGI** → Still task-specific.
- AGI must have **memory, reasoning, and adaptability**.

### Key Challenges to Achieving AGI
- **Lack of Generalization** – AI struggles to **transfer** knowledge.
- **No True Memory or Autonomy** – AI doesn’t retain **context over time**.
- **Common Sense & Reasoning Issues** – AI can’t yet **think like humans**.

Despite thees challenges many feel that AGI is achievable in the next decade, or perhaps sooner...

---

## What is ASI?
- **Artificial Superintelligence (ASI)**: AI that **surpasses human intelligence**.
- ASI would be **capable of recursive self-improvement**.
- **Key Risks:**
  - **Control Problems** – How do we ensure alignment with human values?
  - **Power Imbalances** – ASI in the wrong hands could be dangerous.

### Possible Growth Trajectories from AGI to ASI

**Slow Takeoff**: AGI improves incrementally over years or decades, with humans maintaining oversight and control. Slow Takeoff advocates argue that we have time to prepare, regulate, and ensure AI alignment.

**Fast Takeoff**: AGI rapidly self-improves, reaching ASI in months, weeks, or even days, far outpacing human ability to regulate or control it. Fast Takeoff proponents warn that if AGI reaches the capability threshold for recursive self-improvement, things could spiral beyond human control in a very short time.

Both scenarios have profound implications for governance, ethics, economics, and existential risk.

???

### Slow Takeoff
- Progressive Integration – AGI is deployed in various industries, gradually enhancing automation, research, and development.
- Human Oversight – Policymakers and researchers have time to develop regulatory frameworks, safety measures, and alignment protocols.
- Economic and Social Adaptation – Societies can adjust to changes in labor markets, ethics, and governance structures as AGI scales up.
- Collaborative AI-Human Synergy – AI and humans co-evolve, leading to augmented intelligence rather than abrupt displacement.
- Less Existential Risk – The controlled pace of development allows for better risk mitigation strategies to prevent catastrophic AI misalignment.

### Fast Takeoff
- Recursive Self-Improvement – The AI continuously enhances its own intelligence and problem-solving capabilities at an exponential rate.
- Loss of Human Control – The speed of progress outstrips human intervention, making it difficult to implement safety measures.
- Disruptive Economic and Societal Impact – A sudden leap to ASI could lead to massive unemployment, shifts in power dynamics, and potential existential threats.
- Potential for Misalignment – Without sufficient alignment work beforehand, ASI may pursue goals that are not aligned with human values.
- Strategic Advantage – Any entity (nation, corporation, or organization) that achieves ASI first may gain an overwhelming technological dominance.

---

class: center, middle

## Understanding Large Language Models (LLMs)

---

## How LLMs Work and What They Can Do
### What is an LLM?
- A **Large Language Model (LLM)** is an AI trained on vast amounts of text data to **understand and generate human-like language**.
- LLMs **predict the next word in a sequence** based on probability.

### How Are LLMs Built?
1. **Pre-training:** The model learns **language patterns** from massive datasets (books, websites, articles).
2. **Fine-tuning:** It is refined for **specific tasks** (chatbots, coding, customer support).
3. **Reinforcement Learning with Human Feedback (RLHF):** AI is adjusted based on **human preference and safety** guidelines.

---

## How LLMs Work and What They Can Do
### How Are LLMs Used?
- **Chatbots & Virtual Assistants** (*ChatGPT, Claude, Gemini*).  
- **Code Generation** (*GitHub Copilot, OpenAI Codex*).  
- **Creative Writing & Content Generation** (*DALL·E prompts, news summaries*).  
- **Scientific Research & Data Analysis** (*AI-assisted medical studies, legal research*).

### Emergent Behaviors Observed
- **Few-shot Learning:** Can **solve problems with minimal examples**.
- **Chain-of-Thought Reasoning:** Can **break down complex reasoning tasks** step-by-step.
- **Unexpected Creativity:** AI-generated **poems, analogies, and artwork**.
- **Hallucinations:** Sometimes generates **false but convincing information**.

???
- LLMs differ from traditional AI by dynamically **generating** responses.
- **Transformers enable context-aware learning**.
- **Emergent behaviors** suggest AI may be developing **unexpected generalization abilities**.

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

## What is the Context Window?

- **Defines how much text an AI model can "remember" in a single interaction.**  
- **Measured in tokens** – one token is roughly **4 characters or 0.75 words**.  
- **Larger context windows enable better recall** but require more computation.  
- **Context is not long-term memory** – past conversations are forgotten after the window resets.  
  - Some chatbots, such a ChatGPT do have a mechanism for storing key memories between chat sessions and injecting that into the context
- **Common context sizes:**  
  - GPT-3.5: ~4K tokens (~3,000 words)  
  - GPT-4o: ~128K tokens (~100,000 words)  
      - A context window of 128k tokens can accommodate the upload of 300-350 page documents for analysis
- **Longer windows allow AI to track detailed discussions**, but responses may still degrade over time.  
- **Workarounds include RAG, memory-enhanced models, and user summaries.**  

???
### **Speaker Notes:**  
- **The context window is like an AI’s short-term memory**—it defines how much previous text the model can reference in a single interaction.  
- Tokens are **not the same as words**—they include parts of words, punctuation, and spaces.  
- **Models with larger context windows can maintain more coherent and detailed conversations**, but they still don’t have persistent memory.  
- **Key limitation:** Once the limit is reached, **older context gets forgotten** unless reintroduced.  
- **Discussion Starter:** *Have you ever noticed AI "forgetting" earlier parts of a conversation?*  
---

## Context Window: Limitations & Solutions

### **Limitations:**
- **Forgets old messages** – Can’t recall past interactions beyond the limit.  
- **Compression Issues** – Summarization can miss key details in longer chats.  
- **Response Quality Degrades** – AI may lose track of earlier details in long conversations.  
- **Inefficient for Large Documents** – Can’t process entire books or datasets at once.  

### **Solutions:**
- **Retrieval-Augmented Generation (RAG)** – Fetches relevant info from external sources.  
- **Chunking & Summarization** – Breaking text into smaller parts and summarizing past content.  
- **Fine-Tuning & Long-Term Memory Systems** – Custom models trained on recurring data.  
- **Hybrid Approaches** – Combining large context windows with real-time retrieval for improved AI performance.  

???
### **Speaker Notes:**  
- The **context window is not the same as memory**—once older text falls out of the window, it’s gone.  
- **Problems arise** in long conversations where AI starts to forget details.  
- **Example:** Asking AI to summarize a 200-page book won’t work—it can only process chunks at a time.  
- **Workarounds:**  
  - **RAG:** Retrieves forgotten information dynamically.  
  - **Summarization:** Helps retain key points but risks missing details.  
  - **Fine-Tuning & Memory-Enhanced AI:** Allows AI to learn user-specific preferences over time.  
- **Discussion Starter:** *How important is it for AI to have persistent memory?*  

---

## What is Retrieval-Augmented Generation (RAG)?

- **Enhances LLMs with external knowledge** – dynamically retrieves relevant documents.  
- **Bridges the gap between static models and real-time information.**  
- **Retrieves from structured knowledge bases or web search** before generating a response.  
- **Reduces hallucinations** – improves factual accuracy by citing sources.  
- **More memory-efficient** – avoids needing massive parameter increases.  
- **Customizable** – can retrieve from **private data, enterprise knowledge, or web sources**.  
- **Useful for specialized applications** – research, enterprise knowledge, legal, and healthcare AI.  
- **Essential for real-world AI deployment** – keeps models up-to-date and grounded in reality.  

???
### **Speaker Notes:**  
- **What is RAG?** It’s a technique that enhances LLMs by **retrieving relevant knowledge before generating text**.  
- RAG can **pull information from private knowledge bases** or **open web search results**, depending on the use case.  
- Web search **extends RAG beyond structured data**, helping AI stay up to date.  
- **Discussion Starter:** *When would you prefer an AI that retrieves from the web vs. a curated knowledge base?*  

---

## Web Search as a RAG Strategy

- **Real-Time Knowledge** – Retrieves fresh, updated information from the web.  
- **Extends LLM Capabilities** – Overcomes the limitations of static training data.  
- **Diverse Data Sources** – Accesses broad knowledge across many domains.  
- **Prone to Misinformation** – Less reliable than structured, curated datasets.  
- **SEO & Ranking Bias** – Search engine algorithms influence what data is retrieved.  
- **Slower Than Local Retrieval** – Dependent on query latency and page indexing.  
- **Best for Trending & Unstructured Data** – Useful for news, current events, and dynamic topics.  
- **Hybrid Approach** – AI can combine web search with structured RAG for better accuracy.  

???
### **Speaker Notes:**  
- **Web search extends the power of RAG**, making AI more dynamic and real-time.  
- However, it introduces **challenges like misinformation, bias, and search engine ranking influences**.  
- **Best use case:** When an AI assistant needs the **latest news or trending data**.  
- **Example:** A company AI chatbot retrieving from **internal documents (RAG)** vs. an AI answering **latest stock prices (Web Search)**.  
- **Discussion Starter:** *Would you trust AI-powered search results over Google’s traditional search? Why or why not?*  

---

## Can AGI be Achieved with LLMs?

The question of whether AGI can be achieved with LLMs is a hotly debated topic. While LLMs like GPT-4, Claude, and Gemini have demonstrated remarkable capabilities, they are still far from true AGI. Let’s break it down:

- **LLMs Lack True Understanding** – They generate text based on patterns, not real comprehension.  
- **No Autonomous Learning** – Cannot self-improve or learn new information without retraining.  
- **Limited Generalization** – Specialized in language but lack real-world experience or adaptability.  
- **No Independent Goals** – LLMs don’t have self-awareness, motivations, or the ability to set objectives.  
- **Struggles with Reasoning** – Poor at logical consistency, long-term planning, and self-correction.  
- **Potential as a Building Block** – LLMs could contribute to AGI when combined with other AI models.  
- **Hybrid AI Approach** – AGI may require memory, reinforcement learning, robotics, and multi-modal AI.  
- **Uncertain Future** – Some experts predict AGI soon, others believe a new paradigm is needed.  

???
### **Speaker Notes:**  
- **Why LLMs aren’t AGI:** They lack real understanding, independent reasoning, and the ability to set goals.  
- **LLMs are useful but incomplete** – they excel in language tasks but struggle with **real-world problem-solving**.  
- **AI researchers believe** AGI will require more than just scaling LLMs—it will need **memory, learning, and multi-modal perception**.  
- **Hybrid models** are being developed to bridge the gap, but AGI **remains a long-term challenge**.  
- **Discussion Starter:** *Will scaling LLMs lead to AGI, or do we need an entirely new AI architecture?*  

---

## LLM Comparison (as of February 2025)

| Model | Release | Cutoff | CW | P | MMLU | GPQA | HHEM | MM | R |
|-------|:-------:|:------:|---:|--:|-----:|-----:|-----:|:---:|:--:|:-:|
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] GPT-4o] | 2024-8 | 2023-10 | 128 | ? | 88.8% | 53.6% | 1.5%  | ✅ | |
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] o3-mini ] | 2025-1 | 2024-6 | 128 | ? | 86.9% | 79.7% | 1.4%  |  | ✅ |
| .flex[.logo[![](logos/claude.svg)] Claude 3.5 Sonnet] | 2024-10 | 2024-4 | 200 | ? | 90.4% | 67.2% | 4.6% | ✅ | |
| .flex[.logo[![](logos/gemini.svg)] Gemini 2.0 Flash] | 2024-12 | 2024-8 | 1048 | ? | 76.4% | 62.1% | 0.7% |✅ | |
| .flex[.logo[![](logos/meta-ai.png)] Llama 3.2] | 2024-12 | 2023-12 | 128 | 90 | 86.0% | 46.7% | 4.3% | ✅ | |
| .flex[.logo[![](logos/qwen.png)] Qwen 2.5 Max] | 2024-9 | ? | 131 | 72 | 83.3% | 49.5% | 2.9% | | |
| .flex[.logo[![](logos/deepseek.png)] DeepSeek V3] | 2024-12 | 2024-7 | 131 | 671 | 88.5% | 59.1% | 3.9% | | |
| .flex[.logo[![](logos/mistral.svg)] Mistral Small 3] | 2025-1 | ? | 32 | 24 | 66.3% | 45.3% | 3.1% | | |
| .flex[.logo[![](logos/xai.svg)] Grok 2] | 2024-8 | 2024-8 | 128 | ? | 87.5% | 56.0% | 4.6% | ✅ | | |

.footnote[
- Cutoff: Knowledge Cutoff Date
- CW: Context Window Size (K)
- P: Parameters (Billions)
- MMLU: Massive Multitask Language Understanding Benchmark Score
- GPQA: General-Purpose Question Answering Benchmark Score
- HHEM: Hughes Hallucination Evaluation Model Score (lower is better)
- Multi-Modal: Can handle images, audio, and video (at least one)
- R: Reasoning model
]

???
The GPQA benchmark (General-Purpose Question Answering) is a relatively recent evaluation metric designed to assess the broad, general-purpose reasoning capabilities of AI models across multiple domains. Unlike domain-specific QA benchmarks, GPQA includes questions that require multi-step reasoning, factual knowledge, and contextual understanding.

As of now, the GPQA benchmark score varies depending on the AI model being tested. The highest-performing models tend to achieve scores in the 60-80% range, but this can change as newer models are released.

Hughes Hallucination Evaluation Model: Developed by Vectara, HHEM is an open-source model designed to detect hallucinations in text generated by AI systems. It outputs a probability score between 0 and 1, where 0 indicates a hallucination and 1 indicates factual consistency. This model is particularly useful for evaluating the factual accuracy of outputs from Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) systems.

---

class: center, middle

# The Rise of the Chatbot...

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/HAL9000.svg/256px-HAL9000.svg.png)

---

## What is a Chatbot?

All of the major AI developers provide chatbots for interacting with their LLMs.  Most of these are available under a *fremium* business model that offers basic services for free while charging for premium features, advanced functionality, or additional services.

A chatbot is an AI-powered software application designed to simulate human-like conversations through text or voice interactions. 

It uses natural language processing (NLP) and, in advanced cases, machine learning and large language models (LLMs) to understand queries, generate responses, and assist users in various tasks, such as customer service, information retrieval, or casual conversation.

---

## AI from Science Fiction

Science fiction has long imagined AI chatbots and assistants, many of which resemble today’s conversational AI. Some of these fictional AIs share similarities with modern LLMs, while others depict more advanced forms of AI, like AGI or ASI.

| **AI Name**  | **Sci-Fi Origin**                 | **Similarities to Modern AI**        | **Key Differences**                 |
|-------------|----------------------------------|--------------------------------------|--------------------------------------|
| **HAL 9000**  | *2001: A Space Odyssey* (1968)  | Voice interaction, decision-making   | True AGI, self-awareness, autonomy  |
| **Cortana**  | *Halo* Series (2001–present)  | Inspired Microsoft’s Cortana AI      | More autonomous and strategic       |
| **J.A.R.V.I.S.**  | *Iron Man* (MCU, 2008–2015)  | Multimodal AI, automation            | Far more advanced reasoning & control |
| **C-3PO**  | *Star Wars* (1977–present)  | Language translation, etiquette      | Fully embodied AI, human-like understanding |
| **Samantha**  | *Her* (2013)  | Conversational AI, adaptive learning | Emotional intelligence, human-like relationships |
| **Data**  | *Star Trek: The Next Generation* (1987–1994)  | AI reasoning, logic                   | Full AGI with creativity & self-awareness |
| **T-800 (Terminator)**  | *The Terminator* (1984–present)  | Conversational AI, mission-driven    | Physical embodiment, autonomy       |
| **Skynet**  | *The Terminator* (1984–present)  | Decision-making, automation          | Artificial Superintelligence (ASI), complete autonomy |

---

## I'm sorry, Dave...
  

<iframe width="100%" style="aspect-ratio:16/8;"" src="https://www.youtube.com/embed/ARJ8cAGm6JE?start=87&end=100" title="HAL 9000: &quot;I&#39;m sorry Dave, I&#39;m afraid I can&#39;t do that&quot;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### HAL 9000, from *2001: A Space Odyssey* (1968)

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

## Today's AI Chatbots

| Company | Chatbot | Free Models | Memory |
| ------- | ------- | ----------- | :----: |
| .flex[.logo[![](https://upload.wikimedia.org/wikipedia/commons/4/4c/Arcticons-black_openai_chatgpt.svg)] OpenAI] | [ChatGPT](https://chatgpt.com/) | GPT-4o, o3-mini (reasoning) | ✅ |
| .flex[.logo[![](logos/gemini.svg)] Google] | [Gemini](https://gemini.google.com/app) | 2.0 Flash, 2.0 Flash Thinking (reasoning) | ✅ |
| .flex[.logo[![](logos/claude.svg)] Anthropic] | [Claude](https://claude.ai) | 3.5 Sonnet | |
| .flex[.logo[![](logos/meta-ai.png)] Meta AI] | [Meta AI]() | Llama 3.2, Llama 3,1, Llama 3.2 Editor | ✅ |
| .flex[.logo[![](logos/copilot.svg)] Microsoft] | [Copilot]() | GPT-4o, Prometheus | |
| .flex[.logo[![](logos/qwen.png)] Alibaba] | [Qwen]() | Qwen-2.5-Max, Qwen-2.5-Plus | |
| .flex[.logo[![](logos/deepseek.png)] DeepSeek] | [DeepSeek]() | DeepSeek-V3, DeepSeek-R1 (reasoning) | |
| .flex[.logo[![](logos/mistral.svg)] Mistral AI] | [Le Chat]() | Mistral Small, Mistral Large, Mistral Next | |
| .flex[.logo[![](logos/xai.svg)] XAI] | [Grok]() | Grok 2 | |
| .flex[.logo[![](logos/perplexity.png)] Perplexity] | [Perplexity]() | Auto (mix of OpenAi, Anthropic and Sonar models), o3-mini (reasoning), DeepSeek-R1 (reasoning) | | |

.footnote[
- Memory: Preserves key memories between chats and inserts into chat context
]

---

## Important Considerations

As AI becomes increasingly integrated into society, it raises important ethical, legal, and social questions. Concerns include
- data privacy, 
- job displacement due to automation, and 
- ensuring that AI systems operate fairly and without bias. 

Ongoing discussions and research aim to address these challenges, promoting the responsible development and deployment of AI technologies.

---

### AI Chatbot Data Privacy & Retention Summary (as of Feb 2025)

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

### AI Chatbot Data Privacy & Retention Summary - Continued

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

class: center, middle

## Chatbot Examples

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