---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm a first-year PhD student in Computer Science at the University of Cambridge. Previously, I worked on AI safety research at LASR in London.

**I find neural networks really cool and work on making LLMs safe.** Driven both by curiosity about their internal mechanisms and by concern for their safe deployment, I currently explore how white-box interpretability methods can aid alignment and monitoring. I also appreciate the awesome, research-driven engineering[^1] behind highly performant deep learning systems!

**Please, don't hesitate to [reach out](mailto:andrzejszablewskias[at]gmail[dot]com)!** I'm very happy to hear about your research, tell you a bit about mine, or just chat about *anything* interesting!

<div class="research-updates" markdown="1">

## Research updates

- 2026-09: Accepted to the **MATS 12 Neel Nanda's Exploration Phase**.
- 2026-09: Serving as a reviewer for ICLR 2027.
- 2026-08: [LangMAP](https://arxiv.org/abs/2606.23566) will be presented as an **oral** at [EMNLP 2026](https://2026.emnlp.org) in Budapest, Hungary 🇭🇺 and as a **poster** at the [2nd Tokenization Workshop at COLM 2026](https://tokenization-workshop.github.io) in San Francisco, USA 🇺🇸
- 2026-07: **Secured ~£14k funding** with [Marek Masiak](https://www.linkedin.com/in/marekmasiak/) for further research on the interpretable-by-design TopKLoRA fine-tuning method.
- 2026-07: Presented [The Model Organism Lottery 🎲](https://arxiv.org/abs/2607.01033) **poster** at the [ICML 2026](https://icml.cc/Conferences/2026) _Mechanistic Interpretability Workshop_ in Seoul, South Korea! 🎉🇰🇷 
- 2026-07: "The Model Organism Lottery 🎲" on unrealistically easily interpretable model organisms for AI safety is here! \[[arxiv](https://arxiv.org/abs/2607.01033) \| [code](https://github.com/model-organisms-for-real/model-organism-lottery)\]
<!-- - 2026-06: [LangMAP](https://arxiv.org/abs/2606.23566), our collaborative (Cambridge-ETH-EPFL) work towards an alternative tokenisation paradigm for multilingual LLMs has shipped! \[[arxiv](https://arxiv.org/abs/2606.23566)\] 🇬🇧🇨🇭 -->
- 2026-05: Serving as a reviewer for the [ICML 2026 Mechanistic Interpretability Workshop](https://mechinterpworkshop.com).
- 2026-05: Participating in the [Research Accelerator Week](https://www.meridiancambridge.org/research-accelerator-week). Cambridge, UK! 🇬🇧
- 2026-04: **Secured ~£200k funding** for continuing our team's work on model organism research throughout LASR Extension. London, UK! 🇬🇧

<details class="updates-more" markdown="1">
<summary>See previous updates</summary>

- 2026-01: Joined [LASR Labs](https://www.lasrlabs.org) to work on technical AI safety research. London, UK! 🇬🇧
- 2025-12: Presented [Activation Transport Operators](https://arxiv.org/abs/2508.17540) as **Spotlight** at the Mechanistic Interpretability Workshop at NeurIPS 2025 in San Diego, US! 🎉🇺🇸 \[[poster](/files/poster_ato25.pdf)\]
- 2025-08: Our recent work "Activation Transport Operators" on transporting SAE features across transformer layers is available! \[[arxiv](https://arxiv.org/abs/2508.17540) \| [code](https://github.com/marek357/activation-transport-operators)\]
- 2025-07: Presented my [MPhil dissertation](/files/mphil_dissertation.pdf) at MobiUK 2025 in Edinburgh, UK! 🇬🇧 \[[poster](/files/poster_mobiuk25.pdf)\]
- 2024-07: Presented preliminary results for *Data-Efficient Task Unlearning* at EEML 2024 in Novi Sad, Serbia! 🇷🇸 \[[poster](/files/poster_eeml24.pdf)\]

</details>

</div>


## More about me

In early 2026, I joined the [LASR fellowship](https://www.lasrlabs.org), which I highly recommend[^2]. Under the supervision of Stefan Heimersheim, my team and I showed that model organism training methodology significantly affects white-box interpretability. We presented it as [The Model Organism Lottery](https://arxiv.org/abs/2607.01033) at an ICML 2026 Workshop in Seoul. At the end of the fellowship in April, my team was awarded a ~£200k research grant for further research work until September. Simultaneously, I worked on [LangMAP](https://arxiv.org/abs/2606.23566) -- our collaborative (Cambridge-ETH-EPFL) work towards an alternative tokenisation paradigm for multilingual LLMs, which was accepted as an oral at EMNLP 2026. Towards the end of summer, I focused on TopKLoRA, a fine-tuning method providing interpretable-by-design and composable feature latents. Following my [mini-project on cross-model thought anchors](https://www.lesswrong.com/posts/EmcEPCFSKKMtCBBkw/thought-anchors-don-t-transfer-between-models), I was accepted into the exploration phase of Neel Nanda's MATS 12 stream.

Throughout my year-long MPhil degree, I was supervised by Prof. Nic Lane and worked with the [CaMLSys](https://mlsys.cst.cam.ac.uk) group, where I focused on Federated Learning. My [dissertation](/files/mphil_dissertation.pdf) explored how several institutions with limited computational resources can collaborate on training a joint foundational language model. During my studies, I also [benchmarked the inner workings](/files/torch_compile.pdf) of `torch.compile()`, and explored the KV-caching strategies in LLM inference. On the more theoretical front, I looked into the phenomenon of [attention sinks](https://github.com/TheRootOf3/understanding-attention-sinks)[^3] in transformers and studied the concept of dynamic tokenisation. What a year it was!

Previously, I have been working with researchers from UCL NLP on [BritLLM](https://llm.org.uk/) -- a joint effort towards producing freely available Large[^4] Language Models for UK languages[^5]. In my [undergraduate dissertation](/files/undergrad_dissertation.pdf) supervised by Prof. Pontus Stenetorp, I focused on the problem of the poor availability of LLMs for low-resource languages and worked on _language model adaptation methods for African languages_. Furthermore, we explored _Data-Efficient Task Unlearning in LMs_, a method for increasing the safety of language models and removing their undesired capabilities.

### Notes

[^1]: [Awesome Engineering!](https://huggingface.co/blog/bloom-megatron-deepspeed)
[^2]: Kaushik, another LASR fellow, wrote a good [retrospective on his experience at LASR](https://www.lesswrong.com/posts/CCxB3e2oL8yeLKESH/lasr-retrospective-and-advice).
[^3]: <del>Write-up in progress.</del> **Update:** It's arrived!
[^4]: As of the time of writing (2024-08-27), 3 billion parameters make the model be considered _large_. **Update**: As of 2025-07-28, a 3B model is still pretty big. **Update 2**: Reflecting on this during ICML 2026, I still think that 3B is quite substantial...
[^5]: Isn't this just... English?! Explore [our work](https://llm.org.uk/) to see what other languages are spoken in the UK!
