---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm a first-year PhD student in Computer Science at the University of Cambridge and a MATS&nbsp;12.0 Scholar in Neel Nanda's stream. Previously, I worked on AI safety research at LASR in London. I am a member of [LISA](https://www.safeai.org.uk).

**I find neural networks really cool and work on making LLMs safe.** Driven both by curiosity about their internal mechanisms and by concern for their safe deployment, I currently explore how white-box interpretability methods can aid alignment and monitoring. I also appreciate the awesome, research-driven engineering[^1] behind highly performant deep learning systems!

**Please, don't hesitate to [reach out](mailto:andrzejszablewskias[at]gmail[dot]com)!** I'm very happy to hear about your research, tell you a bit about mine, or just chat about *anything* interesting!

<div class="research-updates" markdown="1">

## Research updates

{% include news.html %}

</div>

## Selected publications

{% include publication-list.html figures=true equal_note=false %}

Blog posts are on the [Publications](/publications/) page.

## More about me

In early 2026, I joined the [LASR fellowship](https://www.lasrlabs.org), which I highly recommend[^2]. Under the supervision of Stefan Heimersheim, my team and I showed that model organism training methodology significantly affects white-box interpretability. We presented it as [The Model Organism Lottery](https://arxiv.org/abs/2607.01033) at an ICML 2026 Workshop in Seoul. At the end of the fellowship in April, my team was awarded a ~£200k research grant for further research work until September. Simultaneously, I worked on [LangMAP](https://arxiv.org/abs/2606.23566) -- our collaborative (Cambridge-ETH-EPFL) work towards an alternative tokenisation paradigm for multilingual LLMs, which was accepted as an oral at EMNLP 2026. Towards the end of summer, I focused on [TopKLoRA](https://arxiv.org/abs/2610.32866), a fine-tuning method providing interpretable-by-design and composable feature latents, which we released as a preprint in October. Following my [mini-project on cross-model thought anchors](https://www.lesswrong.com/posts/EmcEPCFSKKMtCBBkw/thought-anchors-don-t-transfer-between-models), I was accepted into the exploration phase of Neel Nanda's MATS 12.0 stream, after which I was selected as a MATS 12.0 Scholar.

Throughout my year-long MPhil degree, I was supervised by Prof. Nic Lane and worked with the [CaMLSys](https://mlsys.cst.cam.ac.uk) group, where I focused on Federated Learning. My [dissertation](/files/mphil_dissertation.pdf) explored how several institutions with limited computational resources can collaborate on training a joint foundational language model. During my studies, I also [benchmarked the inner workings](/files/torch_compile.pdf) of `torch.compile()`, and explored the KV-caching strategies in LLM inference. On the more theoretical front, I looked into the phenomenon of [attention sinks](https://github.com/TheRootOf3/understanding-attention-sinks)[^3] in transformers and studied the concept of dynamic tokenisation. What a year it was!

Previously, I have been working with researchers from UCL NLP on [BritLLM](https://llm.org.uk/) -- a joint effort towards producing freely available Large[^4] Language Models for UK languages[^5]. In my [undergraduate dissertation](/files/undergrad_dissertation.pdf) supervised by Prof. Pontus Stenetorp, I focused on the problem of the poor availability of LLMs for low-resource languages and worked on _language model adaptation methods for African languages_. Furthermore, we explored _Data-Efficient Task Unlearning in LMs_, a method for increasing the safety of language models and removing their undesired capabilities.

### Notes

[^1]: [Awesome Engineering!](https://huggingface.co/blog/bloom-megatron-deepspeed)
[^2]: Kaushik, another LASR fellow, wrote a good [retrospective on his experience at LASR](https://www.lesswrong.com/posts/CCxB3e2oL8yeLKESH/lasr-retrospective-and-advice).
[^3]: <del>Write-up in progress.</del> **Update:** It's arrived!
[^4]: As of the time of writing (2024-08-27), 3 billion parameters make the model be considered _large_. **Update**: As of 2025-07-28, a 3B model is still pretty big. Reflecting on this **during ICML 2026**, I still think that 3B is quite substantial. In **September 2026**, [I worked with a 1.7B model](https://www.lesswrong.com/posts/EmcEPCFSKKMtCBBkw/thought-anchors-don-t-transfer-between-models) and even that was quite sizeable!
[^5]: Isn't this just... English?! Explore [our work](https://llm.org.uk/) to see what other languages are spoken in the UK!
