# Awesome Personal AI with stars

📝 A curated list about Personal AI — models, agents, memory, and systems that learn about *you*\~ 📚

Personal AI should not only be powerful, but also understand each user's concepts, memories, preferences, behavior, environment, and goals! 🙋‍♀️✨

<p align="center">
  <img src="https://thaoshibe.github.io/images/Picture1.jpg" width="900" alt="Awesome Personal AI">
</p>

*(This figure is created by me. If there is anything incorrect, please feel free to correct me! Thank you! 🤗)*

## 🧭 Scope

This list covers personal AI assistants, agents, language and multimodal models, long-term memory, user modeling, preference learning, and personal retrieval. A resource should make personalization to a specific user or their data a central contribution.

Generic agents, memory systems, role-playing characters, and recommendation systems are included only when they directly support personal AI.

### Table of Contents

* [🏭 Industrial Tools & Products](#-industrial-tools--products)
* [📚 Surveys & Perspectives](#-surveys--perspectives)
* [🤖 Personal AI Agents](#-personal-ai-agents)
  * [Computer, Mobile, and Tool-Use Agents](#computer-mobile-and-tool-use-agents)
  * [Embodied and Assistive Agents](#embodied-and-assistive-agents)
* [🧠 Memory & User Modeling](#-memory--user-modeling)
* [✨ Personalized Models](#-personalized-models)
  * [Language Models](#language-models)
  * [Vision-Language and Multimodal Models](#vision-language-and-multimodal-models)
  * [Unified Understanding and Generation](#unified-understanding-and-generation)
* [🔎 Personal Retrieval & Representation](#-personal-retrieval--representation)
* [🧪 Benchmarks & Datasets](#-benchmarks--datasets)
* [🌟 Related Awesome Lists](#-related-awesome-lists)
* [🌱 Contributing](#-contributing)

***

## 🏭 Industrial Tools & Products

Products, open-source frameworks, developer tools, and industry updates for building Personal AI\~ 🛠️

| Name                         | Type                | Organization | Description                                                                                         | Links                                                                                                                                                                                                                   |
| :--------------------------- | :------------------ | :----------- | :-------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Muse                         | Personal agent      | Meta         | Personal AI agent that works across the web, apps, Mac, WhatsApp, and Meta AI glasses.              | [Product](https://introducing.muse.ai/) · [Announcement](https://www.meta.com/blog/meta-connect-2026-everything-we-announced/)                                                                                          |
| Muse Charm                   | AI device           | Meta         | Pocket-sized voice device built for interacting with Muse throughout the day.                       | [Product](https://www.meta.com/in/muse-charm/)                                                                                                                                                                          |
| dots                         | Personal agent      | OpenAI       | Persistent, proactive agents that maintain context and work on ongoing tasks across connected apps. | [Announcement](https://openai.com/index/introducing-dots/)                                                                                                                                                              |
| ChatGPT Pulse                | Product feature     | OpenAI       | Proactive, personalized daily updates based on memory, feedback, and connected apps.                | [Announcement](https://openai.com/index/introducing-chatgpt-pulse/)                                                                                                                                                     |
| Gemini Personal Intelligence | Product             | Google       | Connects Gemini with personal context from Google apps.                                             | [Blog](https://blog.google/innovation-and-ai/products/gemini-app/personal-intelligence/)                                                                                                                                |
| ChatGPT Memory               | Product             | OpenAI       | Uses saved memories and conversation history to personalize responses.                              | [Blog](https://openai.com/index/memory-and-new-controls-for-chatgpt/)                                                                                                                                                   |
| mem0                         | Framework           | mem0         | Universal memory layer for AI agents.                                                               | [Code](https://github.com/mem0ai/mem0) ⭐ 66,824 \| 🐛 802 \| 🌐 Python \| 📅 2026-10-08 · [Stars](https://github.com/mem0ai/mem0/stargazers) ⭐ 66,824 \| 🐛 802 \| 🌐 Python \| 📅 2026-10-08                           |
| Graphiti                     | Framework           | Zep          | Real-time temporal knowledge graphs for agent memory.                                               | [Code](https://github.com/getzep/graphiti) ⭐ 31,558 \| 🐛 461 \| 🌐 Python \| 📅 2026-10-07 · [Stars](https://github.com/getzep/graphiti/stargazers) ⭐ 31,558 \| 🐛 461 \| 🌐 Python \| 📅 2026-10-07                   |
| Letta                        | Framework           | Letta        | Stateful agents with persistent memory that can learn over time.                                    | [Code](https://github.com/letta-ai/letta) ⭐ 25,076 \| 🐛 0 \| 📅 2026-09-10 · [Docs](https://docs.letta.com/)                                                                                                           |
| LangMem                      | Developer tool      | LangChain    | Tools for extracting, managing, and updating long-term agent memories.                              | [Code](https://github.com/langchain-ai/langmem) ⭐ 1,697 \| 🐛 74 \| 🌐 Python \| 📅 2026-10-02                                                                                                                          |
| nanobot                      | Open-source product | HKUDS        | Ultra-lightweight personal AI assistant.                                                            | [Code](https://github.com/HKUDS/nanobot) ⭐ 48,868 \| 🐛 822 \| 🌐 Python \| 📅 2026-10-08 · [Stars](https://github.com/HKUDS/nanobot/stargazers) ⭐ 48,868 \| 🐛 822 \| 🌐 Python \| 📅 2026-10-08                       |
| OpenClaw                     | Open-source product | OpenClaw     | Personal AI assistant for different operating systems and platforms.                                | [Code](https://github.com/openclaw/openclaw) ⭐ 391,626 \| 🐛 9,560 \| 🌐 TypeScript \| 📅 2026-10-08 · [Stars](https://github.com/openclaw/openclaw/stargazers) ⭐ 391,626 \| 🐛 9,560 \| 🌐 TypeScript \| 📅 2026-10-08 |

***

## 📚 Surveys & Perspectives

| Title                                                                                                                                                       |            Venue            | Year | Focus                | Resources |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------: | :--: | :------------------- | :-------- |
| [Toward Personalized LLM-Powered Agents: Foundations, Evaluation, and Future Directions](https://arxiv.org/abs/2602.22680)                                  |            arXiv            | 2026 | Agents, evaluation   | Paper     |
| [A Survey of Personalization: From RAG to Agent](https://arxiv.org/abs/2504.10147)                                                                          |            arXiv            | 2025 | RAG, agents          | Paper     |
| [A Survey on Personalized Alignment -- The Missing Piece for Large Language Models in Real-World Applications](https://arxiv.org/abs/2503.17003)            |            arXiv            | 2025 | Preference alignment | Paper     |
| [Personalized Multimodal Large Language Models: A Survey](https://arxiv.org/abs/2412.02142)                                                                 |            arXiv            | 2024 | Multimodal models    | Paper     |
| [Personalization of Large Language Models: A Survey](https://arxiv.org/abs/2411.00027)                                                                      |            arXiv            | 2024 | Language models      | Paper     |
| [The Benefits, Risks and Bounds of Personalizing the Alignment of Large Language Models to Individuals](https://www.nature.com/articles/s42256-024-00820-y) | Nature Machine Intelligence | 2024 | Alignment, safety    | Article   |

***

## 🤖 Personal AI Agents

### Computer, Mobile, and Tool-Use Agents

| Title                                                                                                                               | Venue | Year | Method                        | Modality    | Resources                                                                                                              |
| :---------------------------------------------------------------------------------------------------------------------------------- | :---: | :--: | :---------------------------- | :---------- | :--------------------------------------------------------------------------------------------------------------------- |
| [Personal AI Agent for Camera Roll VQA](https://arxiv.org/abs/2606.05275)                                                           | arXiv | 2026 | Personal context, retrieval   | Image, text | [Page](https://thaoshibe.github.io/camroll)                                                                            |
| [MyPCBench: A Benchmark for Personally Intelligent Computer-Use Agents](https://arxiv.org/abs/2606.16748)                           | arXiv | 2026 | Personal context, tool use    | Image, text | [Page](https://mypcbench.com/) · [Code](https://github.com/ljang0/MyPCBench) ⭐ 9 \| 🐛 3 \| 🌐 Python \| 📅 2026-10-02 |
| [iOSWorld: A Benchmark for Personally Intelligent Phone Agents](https://arxiv.org/abs/2606.09764)                                   | arXiv | 2026 | Personal context, tool use    | Image, text | [Page](https://iosworld.io/) · [Code](https://github.com/ljang0/iosworld) ⭐ 20 \| 🐛 1 \| 🌐 Swift \| 📅 2026-09-30    |
| [ASTRA-bench: Evaluating Tool-Use Agent Reasoning and Action Planning with Personal User Context](https://arxiv.org/abs/2603.01357) | arXiv | 2026 | Personal context, planning    | Text        | Paper                                                                                                                  |
| [PersonaAgent: Bridging Memory and Action for Personalized LLM Agents](https://arxiv.org/abs/2506.06254)                            | arXiv | 2025 | Test-time personalization     | Text        | Paper                                                                                                                  |
| [PEToolLLM: Towards Personalized Tool Learning in Large Language Models](https://arxiv.org/abs/2502.18980)                          | arXiv | 2025 | Tool learning                 | Text        | Paper                                                                                                                  |
| [Hello Again! LLM-powered Personalized Agent for Long-term Dialogue](https://aclanthology.org/2025.naacl-long.272/)                 | NAACL | 2025 | Dynamic persona, event memory | Text        | [Paper](https://aclanthology.org/2025.naacl-long.272.pdf)                                                              |

### Embodied and Assistive Agents

| Title                                                                                                                                                    | Venue | Year | Method                      | Modality           | Resources                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------------- | :---: | :--: | :-------------------------- | :----------------- | :---------------------------------------------- |
| [VisualClaw: A Real-Time, Personalized Agent for the Physical World](https://arxiv.org/abs/2606.16295)                                                   | arXiv | 2026 | Online personalization      | Video, image, text | [Page](https://ucsc-vlaa.github.io/VisualClaw/) |
| [PersonalHomeBench: Evaluating Agents in Personalized Smart Homes](https://arxiv.org/abs/2604.16813)                                                     | arXiv | 2026 | Personal context, planning  | Image, text        | Paper                                           |
| [LifeEval: A Multimodal Benchmark for Assistive AI in Egocentric Daily Life Tasks](https://arxiv.org/abs/2603.00490)                                     | arXiv | 2026 | Egocentric assistance       | Video, text        | Paper                                           |
| [See, Act, Adapt: Active Perception for Unsupervised Cross-Domain Visual Adaptation via Personalized VLM-Guided Agent](https://arxiv.org/abs/2602.23806) | arXiv | 2026 | Online adaptation           | Image, text        | Paper                                           |
| [Embodied Agents Meet Personalization: Exploring Memory Utilization for Personalized Assistance](https://arxiv.org/abs/2505.16348)                       | arXiv | 2025 | Memory, embodied assistance | Multimodal         | Paper                                           |

***

## 🧠 Memory & User Modeling

| Title                                                                                                                                                            | Venue | Year | Method                          | Modality    | Resources                                                                                      |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---: | :--: | :------------------------------ | :---------- | :--------------------------------------------------------------------------------------------- |
| [PersonaTree: Structured Lifecycle Memory for Person Understanding in LLM Agents](https://arxiv.org/abs/2606.04780)                                              | arXiv | 2026 | Structured memory               | Text        | Paper                                                                                          |
| [Personal Visual Memory from Explicit and Implicit Evidence](https://arxiv.org/abs/2605.28806)                                                                   | arXiv | 2026 | Explicit and implicit memory    | Image, text | [Page](https://viettmab.github.io/visualmem-page/)                                             |
| [From Recall to Forgetting: Benchmarking Long-Term Memory for Personalized Agents](https://arxiv.org/abs/2604.20006)                                             | arXiv | 2026 | Evolving memory, forgetting     | Text        | Paper                                                                                          |
| [OmniMem: Autoresearch-Guided Discovery of Lifelong Multimodal Agent Memory](https://arxiv.org/abs/2604.01007)                                                   | arXiv | 2026 | Lifelong memory                 | Image, text | [Code](https://github.com/aiming-lab/SimpleMem) ⭐ 3,824 \| 🐛 10 \| 🌐 Python \| 📅 2026-07-24 |
| [According to Me: Long-Term Personalized Referential Memory QA](https://arxiv.org/abs/2603.01990)                                                                | arXiv | 2026 | Referential memory              | Image, text | [Code](https://github.com/JingbiaoMei/ATM-Bench) ⭐ 68 \| 🐛 1 \| 🌐 Python \| 📅 2026-08-13    |
| [PersonaMem-v2: Towards Personalized Intelligence via Learning Implicit User Personas and Agentic Memory](https://arxiv.org/abs/2512.06688)                      | arXiv | 2025 | Persona inference, memory       | Text        | [Data](https://huggingface.co/datasets/bowen-upenn/PersonaMem-v2)                              |
| [Teaching Language Models to Evolve with Users: Dynamic Profile Modeling for Personalized Alignment](https://arxiv.org/abs/2505.15456)                           | arXiv | 2025 | Dynamic user profiles           | Text        | Paper                                                                                          |
| [Toward Multi-Session Personalized Conversation: A Large-Scale Dataset and Hierarchical Tree Framework for Implicit Reasoning](https://arxiv.org/abs/2503.07018) | arXiv | 2025 | Multi-session profiles          | Text        | Paper                                                                                          |
| [LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://arxiv.org/abs/2410.10813)                                                    | arXiv | 2024 | Long-term memory evaluation     | Text        | Paper                                                                                          |
| [Evaluating Very Long-Term Conversational Memory of LLM Agents](https://aclanthology.org/2024.acl-long.747/)                                                     |  ACL  | 2024 | Long-term conversational memory | Text, image | [Paper](https://aclanthology.org/2024.acl-long.747.pdf)                                        |

***

## ✨ Personalized Models

### Language Models

| Title                                                                                                                                         |     Venue     | Year | Method                          | Modality | Resources                                                                                                                               |
| :-------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :--: | :------------------------------ | :------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| [Evoking User Memory: Personalizing LLM via Recollection-Familiarity Adaptive Retrieval](https://arxiv.org/abs/2603.09250)                    |      ICLR     | 2026 | Adaptive retrieval              | Text     | Paper                                                                                                                                   |
| [PersonaLens: A Benchmark for Personalization Evaluation in Conversational AI Assistants](https://aclanthology.org/2025.findings-acl.927/)    |  ACL Findings | 2025 | Evaluation                      | Text     | [Paper](https://aclanthology.org/2025.findings-acl.927.pdf)                                                                             |
| [PersonaFeedback: A Large-scale Human-annotated Benchmark for Personalization](https://arxiv.org/abs/2506.12915)                              |     arXiv     | 2025 | Preference alignment            | Text     | Paper                                                                                                                                   |
| [Know Me, Respond to Me: Benchmarking LLMs for Dynamic User Profiling and Personalized Responses at Scale](https://arxiv.org/abs/2504.14225)  |      COLM     | 2025 | Dynamic user profiling          | Text     | Paper                                                                                                                                   |
| [Scaling Synthetic Data Creation with 1,000,000,000 Personas](https://arxiv.org/abs/2406.20094)                                               |     arXiv     | 2024 | Synthetic personas              | Text     | Paper                                                                                                                                   |
| [Personalized Large Language Models](https://arxiv.org/abs/2402.09269)                                                                        | ICDM Workshop | 2024 | Personalized generation         | Text     | Paper                                                                                                                                   |
| [LaMP: When Large Language Models Meet Personalization](https://aclanthology.org/2024.acl-long.399/)                                          |      ACL      | 2024 | Retrieval, personalization      | Text     | [Page](https://lamp-benchmark.github.io/) · [Code](https://github.com/LaMP-Benchmark/LaMP) ⭐ 209 \| 🐛 11 \| 🌐 Python \| 📅 2025-02-18 |
| [Learning to Predict Persona Information for Dialogue Personalization without Explicit Persona Description](https://arxiv.org/abs/2111.15093) |      ACL      | 2023 | Persona inference               | Text     | Paper                                                                                                                                   |
| [A Personalized Dialogue Generator with Implicit User Persona Detection](https://arxiv.org/abs/2204.07372)                                    |     COLING    | 2022 | Persona inference               | Text     | Paper                                                                                                                                   |
| [Call for Customized Conversation: Customized Conversation Grounding Persona and Knowledge](https://arxiv.org/abs/2112.08619)                 |      AAAI     | 2022 | Persona and knowledge grounding | Text     | [Code](https://github.com/ncsoft/FoCus) ⭐ 0 \| 🐛 0 \| 📅 2022-03-22                                                                    |
| [Personalizing Dialogue Agents: I Have a Dog, Do You Have Pets Too?](https://arxiv.org/abs/1801.07243)                                        |      ACL      | 2018 | Persona-conditioned dialogue    | Text     | Paper                                                                                                                                   |

### Vision-Language and Multimodal Models

| Title                                                                                                                      |  Venue  | Year | Method                           | Modality           | Resources                                                                                                                                          |
| :------------------------------------------------------------------------------------------------------------------------- | :-----: | :--: | :------------------------------- | :----------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Personalize Your Large Vision-Language Models With In-context Prompt Tuning](https://arxiv.org/abs/2605.31513)            |   ECCV  | 2026 | In-context prompt tuning         | Image, text        | Paper                                                                                                                                              |
| [Personal Visual Context Learning in Large Multimodal Models](https://arxiv.org/abs/2605.10936)                            |  arXiv  | 2026 | Visual context learning          | Video, image, text | [Page](https://vision.cs.utexas.edu/projects/PersonalVCL/)                                                                                         |
| [PersonaVLM: Long-Term Personalized Multimodal LLMs](https://arxiv.org/abs/2604.13074)                                     |   CVPR  | 2026 | Long-term personalization        | Image, text        | [Page](https://personavlm.github.io/) · [Code](https://github.com/MiG-NJU/PersonaVLM) ⭐ 125 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2026-04-16        |
| [PEARL: Personalized Streaming Video Understanding Model](https://arxiv.org/abs/2603.20422)                                |  arXiv  | 2026 | Streaming personalization        | Video, text        | [Code](https://github.com/Yuanhong-Zheng/PEARL) ⭐ 56 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-24                                                         |
| [Ego: Embedding-Guided Personalization of Vision-Language Models](https://arxiv.org/abs/2603.09771)                        |  arXiv  | 2026 | Embedding-guided personalization | Video, image, text | Paper                                                                                                                                              |
| [Contextualized Visual Personalization in Vision-Language Models](https://arxiv.org/abs/2602.03454)                        |   ICML  | 2026 | Contextual personalization       | Image, text        | [Page](https://oyt9306.github.io/covip.github.io/) · [Code](https://github.com/oyt9306/CoViP) ⭐ 10 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2026-09-11 |
| [Online-PVLM: Advancing Personalized VLMs with Online Concept Learning](https://arxiv.org/abs/2511.20056)                  |  arXiv  | 2025 | Online concept learning          | Image, text        | Paper                                                                                                                                              |
| [MMPB: It's Time for Multi-Modal Personalization](https://aidaslab.github.io/MMPB/)                                        | NeurIPS | 2025 | Benchmarking                     | Image, text        | [Page](https://aidaslab.github.io/MMPB/)                                                                                                           |
| [RePIC: Reinforced Post-Training for Personalizing Multi-Modal Language Models](https://arxiv.org/abs/2506.18369)          | NeurIPS | 2025 | Reinforced post-training         | Image, text        | [Code](https://github.com/oyt9306/RePIC) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-01                                                                |
| [Training-Free Personalization via Retrieval and Reasoning on Fingerprints](https://arxiv.org/abs/2503.18623)              |  arXiv  | 2025 | Retrieval, reasoning             | Image, text        | Paper                                                                                                                                              |
| [PVChat: Personalized Video Chat with One-Shot Learning](https://arxiv.org/abs/2503.17069)                                 |  arXiv  | 2025 | One-shot learning                | Video, text        | Paper                                                                                                                                              |
| [Concept-as-Tree: Synthetic Data is All You Need for VLM Personalization](https://arxiv.org/abs/2503.12999)                |  arXiv  | 2025 | Synthetic data                   | Image, text        | Paper                                                                                                                                              |
| [Personalization Toolkit: Training Free Personalization of Large Vision Language Models](https://arxiv.org/abs/2502.02452) |  arXiv  | 2025 | Training-free personalization    | Image, text        | Paper                                                                                                                                              |
| [Personalized Large Vision-Language Models](https://arxiv.org/abs/2412.17610)                                              |  arXiv  | 2024 | Concept personalization          | Image, text        | Paper                                                                                                                                              |
| [MC-LLaVA: Multi-Concept Personalized Vision-Language Model](https://arxiv.org/abs/2411.11706)                             |  arXiv  | 2024 | Multi-concept learning           | Image, text        | [Code](https://github.com/arctanxarc/MC-LLaVA) ⭐ 141 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-17                                                         |
| [Personalized Visual Instruction Tuning](https://arxiv.org/abs/2410.07113)                                                 |   ICLR  | 2025 | Instruction tuning               | Image, text        | Paper                                                                                                                                              |
| [Retrieval-Augmented Personalization for Multimodal Large Language Models](https://arxiv.org/abs/2410.13360)               |   CVPR  | 2025 | Retrieval augmentation           | Image, text        | [Page](https://hoar012.github.io/RAP-Project/) · [Code](https://github.com/Hoar012/RAP-MLLM) ⭐ 86 \| 🐛 1 \| 🌐 Python \| 📅 2026-06-08            |
| [MyVLM: Personalizing VLMs for User-Specific Queries](https://arxiv.org/abs/2403.14599)                                    |   ECCV  | 2024 | Concept heads                    | Image, text        | [Page](https://snap-research.github.io/MyVLM/) · [Code](https://github.com/snap-research/MyVLM) ⭐ 188 \| 🐛 6 \| 🌐 Python \| 📅 2024-07-05        |
| [Yo'LLaVA: Your Personalized Language and Vision Assistant](https://arxiv.org/abs/2406.09400)                              | NeurIPS | 2024 | Concept tokens                   | Image, text        | [Page](https://thaoshibe.github.io/YoLLaVA) · [Code](https://github.com/WisconsinAIVision/YoLLaVA) ⭐ 125 \| 🐛 5 \| 🌐 Python \| 📅 2025-03-26     |

### Unified Understanding and Generation

| Title                                                                                                                                           |  Venue  | Year | Method                               | Modality    | Resources                                                                        |
| :---------------------------------------------------------------------------------------------------------------------------------------------- | :-----: | :--: | :----------------------------------- | :---------- | :------------------------------------------------------------------------------- |
| [TAMEing Long Contexts in Personalization: Towards Training-Free and State-Aware MLLM Personalized Assistant](https://arxiv.org/abs/2512.21616) |   KDD   | 2025 | State-aware, training-free           | Image, text | [Code](https://github.com/ronpay/TAME) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-30 |
| [UniCTokens: Boosting Personalized Understanding and Generation via Unified Concept Tokens](https://arxiv.org/abs/2505.14671)                   | NeurIPS | 2025 | Unified concept tokens               | Image, text | [Page](https://chawuciren11.github.io/UniCTokens.github.io/)                     |
| [YoChameleon: Personalized Vision and Language Generation](https://arxiv.org/abs/2504.20998)                                                    |   CVPR  | 2025 | Unified understanding and generation | Image, text | [Page](https://thaoshibe.github.io/YoChameleon/)                                 |

***

## 🔎 Personal Retrieval & Representation

| Title                                                                                                                                                              | Venue | Year | Method                             | Resources                                                                                          |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---: | :--: | :--------------------------------- | :------------------------------------------------------------------------------------------------- |
| [PhotoBench: Beyond Visual Matching Towards Personalized Intent-Driven Photo Retrieval](https://arxiv.org/abs/2603.01493)                                          | arXiv | 2026 | Intent-driven retrieval            | [Code](https://github.com/LaVieEnRose365/PhotoBench) ⭐ 18 \| 🐛 5 \| 🌐 Python \| 📅 2026-05-17    |
| [DeepImageSearch: Benchmarking Multimodal Agents for Context-Aware Image Retrieval in Visual Histories](https://arxiv.org/abs/2602.10809)                          | arXiv | 2026 | Context-aware retrieval            | [Code](https://github.com/RUC-NLPIR/DeepImageSearch) ⭐ 90 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-02    |
| [Personalized Representation from Personalized Generation](https://personalized-rep.github.io/)                                                                    |  ICLR | 2025 | Generative representation learning | [Code](https://github.com/ssundaram21/personalized-rep) ⭐ 66 \| 🐛 1 \| 🌐 Python \| 📅 2026-05-18 |
| [“This Is My Unicorn, Fluffy”: Personalizing Frozen Vision-Language Representations](https://github.com/NVlabs/PALAVRA) ⭐ 54 \| 🐛 2 \| 🌐 Python \| 📅 2022-07-31 |  ECCV | 2024 | Personalized representations       | [Code](https://github.com/NVlabs/PALAVRA) ⭐ 54 \| 🐛 2 \| 🌐 Python \| 📅 2022-07-31               |

***

## 🧪 Benchmarks & Datasets

### Agent, Memory, and Conversation Benchmarks

| Name             | Year | Focus                                       | Resources                                                                                                                               |
| :--------------- | :--: | :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------- |
| MyPCBench        | 2026 | Personally intelligent computer-use agents  | [Page](https://mypcbench.com/) · [Code](https://github.com/ljang0/MyPCBench) ⭐ 9 \| 🐛 3 \| 🌐 Python \| 📅 2026-10-02                  |
| iOSWorld         | 2026 | Personally intelligent phone agents         | [Page](https://iosworld.io/) · [Code](https://github.com/ljang0/iosworld) ⭐ 20 \| 🐛 1 \| 🌐 Swift \| 📅 2026-09-30                     |
| MemoryAgentBench | 2026 | Incremental multi-turn agent memory         | [Code](https://github.com/HUST-AI-HYZ/MemoryAgentBench) ⭐ 462 \| 🐛 7 \| 🌐 Python \| 📅 2026-09-25                                     |
| PersonaFeedback  | 2025 | Human-annotated personalization preferences | [Paper](https://arxiv.org/abs/2506.12915)                                                                                               |
| LongMemEval      | 2024 | Long-term interactive memory                | [Paper](https://arxiv.org/abs/2410.10813)                                                                                               |
| LoCoMo           | 2024 | Very long-term conversational memory        | [Paper](https://aclanthology.org/2024.acl-long.747/)                                                                                    |
| LaMP             | 2024 | Personalized language modeling              | [Page](https://lamp-benchmark.github.io/) · [Code](https://github.com/LaMP-Benchmark/LaMP) ⭐ 209 \| 🐛 11 \| 🌐 Python \| 📅 2025-02-18 |

### Multimodal Personalization Datasets

| Name       | Year | Concepts | Resources                                                                                                                    | Notes                                                                  |
| :--------- | :--: | :------: | :--------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| ConCon-Chi | 2024 |    20    | [Data](https://github.com/hsp-iit/concon-chi_benchmark) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2024-04-03                           | Personalized visual concepts                                           |
| PODS       | 2024 |    100   | [Data](https://github.com/ssundaram21/personalized-rep/tree/main/dataset) ⭐ 66 \| 🐛 1 \| 🌐 Python \| 📅 2026-05-18         | Released with Personalized Representation from Personalized Generation |
| MC-LLaVA   | 2024 | Multiple | [Data](https://github.com/arctanxarc/MC-LLaVA) ⭐ 141 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-17                                   | Multi-concept personalization                                          |
| Yo'LLaVA   | 2024 |    40    | [Data](https://github.com/WisconsinAIVision/YoLLaVA#yollava-dataset) ⭐ 125 \| 🐛 5 \| 🌐 Python \| 📅 2025-03-26             | Single-concept personalization                                         |
| MyVLM      | 2024 |    29    | [Data](https://github.com/snap-research/MyVLM#dataset--pretrained-concept-heads) ⭐ 188 \| 🐛 6 \| 🌐 Python \| 📅 2024-07-05 | Single-concept personalization                                         |

***

## 🌟 Related Awesome Lists

* [Awesome Agent Memory](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory) ⭐ 663 | 🐛 0 | 🌐 Python | 📅 2026-10-08 — systems, benchmarks, and research for agent memory.
* [Awesome Personalized LLM](https://github.com/HqWu-HITCS/Awesome-Personalized-LLM) ⭐ 148 | 🐛 3 | 📅 2024-09-23 — personalized language models, chat, and role-playing.
* [Awesome Personalized Alignment](https://github.com/liyongqi2002/Awesome-Personalized-Alignment) ⭐ 80 | 🐛 1 | 📅 2026-10-03 — personalized preferences and alignment.
* [Awesome Personalization in MLLMs](https://github.com/Clare-Nie/Awesome-Personalization-in-MLLMs) ⭐ 20 | 🐛 2 | 📅 2026-06-13 — personalization in multimodal large language models.

***

## 🌱 Contributing

Please feel free to create a pull request to add papers, products, tools, datasets, or edit any information. Thank you! 🤗

<a href="https://github.com/thaoshibe/awesome-personalized-lmms/pulls">
  <img src="https://img.shields.io/badge/Submit%20a%20Pull%20Request-blue?style=for-the-badge" alt="Submit a pull request">
</a>

When proposing an entry:

* Please explain how it supports personalization to a specific user or their data.
* Prefer the official paper, project, code, or product URL.
* Add the resource to one primary section and use method tags to describe overlap.
* Avoid generic agents, memory systems, or recommendation work without a direct Personal AI contribution.

If there is anything incorrect or missing, please feel free to correct me. Thank you! ✨

***

⣶⣶⣶⣶⣶⣖⣒⡄⠀⣶⡖⠲⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣤⠠⡄⠀⠀⠀⠀
⠙⠛⣿⣿⣿⡟⠛⠃⢀⣿⣿⣆⣦⣴⠂⠤⠀⠀⠀⣠⣤⣴⣆⠠⢄⠀⠀⠀⣤⡤⢤⣤⣤⠤⢄⠀⠀⢻⣿⣦⡇⢀⣤⢤⠀
⠀⢀⣿⣿⣿⡇⠀⠀⢸⣿⣿⣿⠛⣿⣷⣄⡇⠀⣼⣿⣿⡟⢿⣷⡄⣣⠀⢘⣿⣿⣿⠿⣿⣧⣈⡆⠀⢹⣿⣿⣷⣾⣧⣴⠀
⠀⢰⣿⣿⣿⠀⠀⠀⢸⣿⣿⣿⠀⣿⣿⣿⡇⠀⠙⠛⣻⣧⣾⣿⣿⡷⠀⢸⣿⣿⣿⠀⣿⣿⣿⡇⠀⢸⣿⣿⣿⣿⣿⡇⠀
⠀⢸⣿⣿⣿⠀⠀⠀⢸⣿⣿⡿⠀⣿⣿⣿⠃⠀⣰⣾⣿⡿⣿⣿⣿⣟⠀⢸⣿⣿⣿⠀⣿⣿⣿⡇⠀⢸⣿⣿⣿⣿⡏⢇⠀
⠀⣼⣿⣿⣿⠀⠀⠀⣸⣿⣿⣟⢠⣿⣿⣿⠀⠀⣿⣿⡟⣇⣾⣿⣿⣯⠀⢸⣿⣿⣿⠀⣿⣿⣿⡇⠀⢼⣿⣿⣿⣿⣷⡈⡀
⠀⠻⠿⠿⠟⠀⠀⠀⠻⠿⠿⠏⠸⣿⣿⣿⠀⠀⢿⣿⣿⣿⣿⣿⣿⡇⠀⢸⣿⣿⣿⠀⣿⣿⣿⡇⠀⣿⣿⣿⡟⢻⣿⣧⣇
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠀⠀⠉⠉⠀⠀⠀⠉⠉⠁⠀⠉⠉⠉⠀⠀⠘⠙⠋⠁⠈⠋⠛⠉
⠀⠀⠀⠀⠀⠀⢀⣠⣤⡀⠀⢀⣀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣤⡤⠠⡄⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢹⣿⣄⠱⣠⣿⣧⣴⠀⠀⣠⣤⣤⣀⣀⡀⠀⠀⢀⣤⠤⡀⢀⣠⡤⢄⠀⠈⣿⣿⣦⡇⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠈⢿⣿⣷⣿⣿⣿⡏⠀⣾⣿⣿⣿⣶⣄⡉⡄⠀⣿⣿⣤⣝⢸⣿⣦⣼⠀⠀⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢿⣿⣿⣿⠏⠀⠐⣿⣿⣿⠉⣿⣿⣷⡇⠀⣽⣿⣿⣯⢸⣿⣿⣿⠀⠀⢹⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⠀⠀⢠⣿⣿⣿⠀⣿⣿⣿⡇⠀⣻⣿⣿⡷⢸⣿⣿⣿⠀⠀⢸⣿⣿⠇⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⠀⠀⠀⢿⣿⣿⣄⣿⣿⣿⠇⠀⢹⣿⣿⣿⣸⣿⣿⣿⠀⠀⢠⣽⣧⡄⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠛⠛⠋⠀⠀⠀⠈⠛⠛⠛⠛⠛⠉⠀⠀⠈⠛⠛⠛⠋⠛⠛⠋⠀⠀⠈⠛⠛⠁⠀⠀⠀⠀⠀⠀⠀

*And good luck with your research! 🤗✨*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-08._
