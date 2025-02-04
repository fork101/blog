---
title: "State of AI Development: 34x growth in AI projects, OpenAI's dominance, the rise of open-source, and more"
author: Jeff Burke
date: 2023-07-14
cover: https://blog.replit.com/images/aiOnReplit/01_AIProjectsOnReplit.png
categories: news,ai
---

With the introduction of Large Language Models (LLMs), for the first time, Machine Learning (ML) and Artificial Intelligence (AI) became accessible to everyday developers. Apps that feel magical, even software that was practically impossible to build by big technology companies with billions in R&D spend, suddenly became not only possibly, but a joy to build and share.

The surge in building with AI started in 2021, grew rapidly in 2022, and exploded in the first half of 2023. The speed of development has increased with more LLM providers (e.g., Google, OpenAI, Cohere, Anthropic) and developer tools (e.g., ChromaDB, LangChain). In parallel, natural language interfaces to generate code have made building accessible to more people than ever.

Throughout this boom Replit has grown to become the central platform for AI development. Tools like ChatGPT can generate code, but creators still need infrastructure to run it. On Replit, you can create a development environment (Repl) in seconds in [any language or framework](https://replit.com/templates) which comes with an active Linux container on Google Cloud, an editor complete with the necessary tools to start building, including a customizable Workspace, extensions, and [Ghostwriter](https://replit.com/site/ghostwriter): an AI pair programmer that has project context and can actively help developers debug. [Deployments](https://replit.com/site/deployments) allowed developers to ship their apps in secure and scalable cloud environments.

Given our central role in the AI wave, we wanted to share some stats with the community on the state of AI development.

## Building with AI

Since Q4 of 2022, we have seen an explosion in AI projects. At the end of Q2 ‘23, there were almost **300,000 distinct projects** that were AI related. By contrast, a search of GitHub shows only **~33k** OpenAI repositories over the same time period. 

![AI Projects on Replit](/images/aiOnReplit/01_AIProjectsOnReplit.png)

**~160,000** of these projects were created in Q2 ‘23. That’s **~80%** QoQ growth, and it is **+34x** YoY. We continue to see these numbers accelerate.

The majority of these projects are using OpenAI. When we compare providers, OpenAI dominates **>80%** of distinct AI projects on Replit. [The OpenAI GPT-3.5 Turbo template has **+8,000** forks today.](https://replit.com/@replit/OpenAI-Python-GPT-35-Turbo?v=1). But there are signs that things might be changing.

![Unique OpenAI Projects](/images/aiOnReplit/02_OpenAIRepls.png)

In Q2 ‘23, we saw:
- **OpenAI** projects cross +125k (up ~80%)
- **Cohere** projects cross +1k (up +100%)
- **Anthropic** and **Google** projects remain < 1k

## The emergence of LangChain
One of the most notable names in AI activity has been LangChain. Using LangChain as a wrapper for some of these models has accelerated development, and we continue to see mass adoption. 

![LangChain Projects](/images/aiOnReplit/03_LangChainProjects.png)

As of Q2’ 23, there were almost **25k** active LangChain projects on Replit. **+20k** of them were created that quarter, which is **+400%** growth from the previous quarter.

Important to note that LangChain provides sufficient abstraction around LLM providers that makes it easy for developers to switch. The growth of the project might be playing a role in the rise of new LLM providers and open-source LLMs.

Takeoff School, founded by [Mckay Wrigley](https://twitter.com/mckaywrigley), built a course called [LangChain 101](https://replit.com/@MckayWrigley/Takeoff-School-LangChain-101-Models?v=1) where people can get started on LangChain today. The project is already about to pass 1,000 forks.

## The rise of open source models
We are also seeing an increase in projects leveraging open source models. Hugging Face and Replicate are two API providers and SDKs that are great entrypoints to open source models.

![Open Source Models](/images/aiOnReplit/04_OpenSource.png)

In Q2 ‘23, we surpassed 5k projects using open-source models. The cumulative number grew **141%** QoQ. Over **70%** of the projects leverage Hugging Face, but Replicate usage grew almost **6x** QoQ.

[Replicate](https://replit.com/@replicate) has templates to run ML models on their verified Replit profile. [The Hugging Face](https://replit.com/@huggingface) verified Gradio template has +600 forks.

## The breakdown of programming languages
Interestingly, we are seeing both Python and JavaScript growing at very similar rates, with Python being the slightly more common language in AI development. JavaScript, however, grew slightly faster during Q2.

![Python vs. JavaScript](/images/aiOnReplit/05_Python.png)

It’s worth noting that projects can have Python AND JavaScript. The two are not mutually exclusive. Many (if not most) projects have a Python backend and JavaScript frontend.

Interestingly, languages vary by geographic location. Certain geographies are building with JavaScript more than Python.

![Geographic Breakdown of AI Developers](images/aiOnReplit/06_GeoBreakdown.png)

Of **~50k** Python developers in the past 90 days:
- **United States:** 32%
- **India:** 11%
- **United Kingdom:** 7%
- **Canada:** 3%
- **Brazil:** 3%

Interestingly, it looks very different for JavaScript! Of ~34k JavaScript developers, we see that: 
- **United States:** 22% 
- **Indonesia:** 10%
- **India:** 9%
- **Vietnam:** 7%
- **Philippines:** 5%

JavaScript developers in AI much more heavily skew to Asia, whereas Python developers skew much more to North America. India appears to be relatively balanced in representation.


## What are they building
The apps being built are remarkable, and we cannot possibly do all of them justice here. What's super exciting is that AI is paving the way for a new generation of entrepeneurs building apps that weren't possible before. Examples include:

- **[CampLingo](https://blog.replit.com/camp-lingo)**: a generative language learning product.
- **[NodePad.space](https://blog.replit.com/nodepad)** - Visual ideation with AI.
- **[MagicSchool](https://blog.replit.com/replit-deployments-magic-school)** - AI tools for educators.
-**[ MightyDeals AI](https://ai.mightydeals.com/)** - Scoring affordable deals across the internet [(story)](https://twitter.com/Replit/status/1665855817160032258?s=20).
- **[AI Avatars with LeapAPI](https://replit.com/@leap-ai/AI-Avatars-App-Javascript-Harry-Potter-Professional?v=1)** - Templates to create professional or themed headshots.
- **[BabyAGI](https://replit.com/@YoheiNakajima/BabyElfAGI?v=1)** - An agent that can read and write its own code.

From supporting under-served teachers to an autonomous agent that can take actions of its own, the projects are evolving every day. 

## Get started today
To get started, there are a few places to begin. You can use ready-to-go templates for the following:
- OpenAI
  - [GPT 3.5 Turbo](https://replit.com/@replit/OpenAI-Python-GPT-35-Turbo?v=1) (+8k forks)
  - [GPT-4](https://replit.com/@replit/OpenAI-Python-GPT-4?v=1) (+7k forks)
- [HuggingFace](https://replit.com/@huggingface)
- [Replicate](https://replit.com/@Replicate)
- [LangChain](https://replit.com/@Langchain)
- [Cohere template](https://replit.com/@NickReed/Generative-Text-AI-Cohere?v=1)
-[ All AI templates on Replit](https://replit.com/templates/ai)

You can also get started with [Takeoff School](https://replit.com/@MckayWrigley/Takeoff-School-LangChain-101-Models?v=1). To add templates or share your project, reach out to our team directly.

If you don't know how to code you can learn using the [100 days of code](https://replit.com/learn/100-days-of-python) course or [hire](https://replit.com/bounties) someone from our community to build your dream app.
