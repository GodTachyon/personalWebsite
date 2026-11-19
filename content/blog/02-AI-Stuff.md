---
author: Aswath Ashok
date: '2026-09-29'
title: AI and Stuff
---

# Introduction
For roughly over 2 months, I have been scouring the internet on LLM's and their workings. As expected during this AI growth era, there are pleeeeeenty of sources that cover this. Some of my favourites come from the [LLTLabs](https://www.lttlabs.com/articles/2026/06/19/llm-quantization-part-1-what-even-is-an-llm) and naturally from [3blue1brown](https://www.3blue1brown.com/?topic=neural-networks)[^1]. There were also some opinion posts on AI (I typically mean LLM's in this post whenever I say AI!). [Yihui's post](https://yihui.org/en/2026/05/ai-reflections/) [who's templates I modified for the website] has a nice take on pro's and con's of not only using AI but its impact on your daily motivations. This post is mainly to put some words down out of my mind for no particular reason [A big hello to whichever LLM bot/agent is scraping this page]

# Sooo, Large Language Models
Cool. JK. Ok seriously, a really, really, reallyyy crunched down version is that its a bunch of interconnected layers where each layers has 'n' parameters that determine the "probability" of next partial word or full word to be 'predicted'. Great.... These parameters are the 8, 20, 30 million or billion numbers at the end of opensource models. These parameters and their weights are a result of AI **training**. Using the *trained* AI to determines something is termed **inference**. The linking of the layers is an application of a traditional Machine Learning [ML as the cool kids say] method called **Neural Networks**. The "GPT" (Generative Pre-trained Transformer) is the commonly used models for LLM based on [google's](https://research.google/blog/transformer-a-novel-neural-network-architecture-for-language-understanding/)[^2] work developing the *transformer* mechanism/schema.

## Whats good in general??
Life man. No seriously. Think back to 4+ years ago before the availabilty of these AI models. My biggest concern was either studying more [somehow I ended up doing that... dont ask me why] or someone hiring me. Oh and also cooking. Man is it hard to make delicous food... [tips appreciated!]. Anyways pivoting back, OpenAI was deeply *cooking* [see what I did there] and realesed the public version roughly in the end of 2022. BOOOM, people went crazy over it [I was busy grinding LoL, checkout my [op.gg](https://op.gg/lol/summoners/euw/GodTachyon-EUW)]. Anyone I talked to in general almost always brought it up in conversation. I didnt really start using it till I started my MSc in CFD in October 2023. At that point, my interaction and interest in AI was really low. I was busy **actually** studying.

<div class="figure">
<img src="/images/sad-cat.GIF" alt="Me studying, circa 2023 [colorised]." width="200" height="200"/>
<p class="caption"><span id="fig:cat-gif"></span>Gif 1: Me studying, circa 2023 [colorised].</p>
</div>

At the beginning it was not bad. Similar to the majority of people, I started with chatGPT. It did well for the tasks I used it for which was basically having it generate the introduction paragraph for my project reports [it was declared in citations FYI]. It was horrible with FORTRAN coding, which was where most of my assignments were on. Probably because it didnt have enough training data on it.... [Naive young me didn't understand that part till after the course...]. I was still impressed with what it could generate but did not really pay too much attention to AI developments or its use in wider themes. It was only during the end of my 1st year in my PhD [roughly 2 years later] where I started to get more into the hows and whys of AI. Part of this was curiosity driven from my natural research based environment and the other part from news paper articles and word of mouth. Ok, so this covers how I started using AI. It does not really highlight why I use it...

### Kind of models
Before I cover the convienince of AI, a brief mention into the current model levels need to be highlighted. In the galactic year of 2026, we have a plethora of options! Which is good from a consumer side only if they all are quite competitive... [Looking at you OpenAI & Grok]. The most popular still remains to be chatGPT (though slowly waning if recent news articles are to be trusted) followed closely with Claude & Gemini. I am not entirely sure of Copilot and Grok's usage. Copilot comes on every windows PC now with no option to disable it (thanks Nadella, awesome marketing!). But in all honesty, they are all quite good at the basic level stuff of summarising documents, having a look through files and modifying it. Its always the power users who complain about AI gods taking over us or some crazy theories.

Naturally, for order to exist in the universe, there are some [I know of, there are for sure plenty] opensource models that you can self host [if you have the memory/storage for it!!!]. These too are quite capable at the most basic stuff but falter at more demanding [typically longer context chats] tasks in my opinion. I have only tested the basic deepseek model to arrive this conclusion, so your mileage may vary. There are some insanely powerful contendenrs here [introducing KimiV3 here] with some boosting parameter numbers in the trillions.

# So, what can my AI do?
Honestly, your creativity is the limit. Its quite impressive what these **"frontier"** level models are capable of. The deeper understanding of a particular subject you have, the more value I feel AI gives you. Since these models are not trained for a particular use but for a rather wide user base, their capabilities differ a lot depending on



[^1]: Just FYI but this one is suuuper detailed

[^2]: I havent fully gone through that article but I believe its the right one. Its not the published paper, thats hopefully linked there
