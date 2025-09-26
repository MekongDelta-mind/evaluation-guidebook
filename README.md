# The LLM Evaluation guidebook ⚖️

If you've ever wondered how to make sure an LLM performs well on your specific task, this guide is for you! 
It covers the different ways you can evaluate a model, guides on designing your own evaluations, and tips and tricks from practical experience.

Whether working with production models, a researcher or a hobbyist, I hope you'll find what you need; and if not, open an issue (to suggest ameliorations or missing resources) and I'll complete the guide!

## How to read this guide
- **Beginner user**: 
  If you don't know anything about evaluation, you should start by the  `Basics` sections in each chapter before diving deeper. 
  You'll also find explanations to support you about important LLM topics in `General knowledge`: for example, how model inference works and what tokenization is.
- **Advanced user**:
  The more practical sections are the `Tips and Tricks` ones, and `Troubleshooting` chapter. You'll also find interesting things in the `Designing` sections.
- **User coming back to the site**: 
  Every year I do a dive on a topic, check them out!

In text, links prefixed by ⭐ are links I really enjoyed and recommend reading.

## Table of contents
If you want an intro on the topic, you can read this [blog](https://huggingface.co/blog/clefourrier/llm-evaluation) on how and why we do evaluation!

### Automatic benchmarks
- [Basics](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/automated-benchmarks/basics.md)
- [Designing your automatic evaluation](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/automated-benchmarks/designing-your-automatic-evaluation.md)
- [Some evaluation datasets](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/automated-benchmarks/some-evaluation-datasets.md)
- [Tips and tricks](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/automated-benchmarks/tips-and-tricks.md)

### Human evaluation
- [Basics](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/human-evaluation/basics.md)
- [Using human annotators](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/human-evaluation/using-human-annotators.md)
- [Tips and tricks](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/human-evaluation/tips-and-tricks.md)

### LLM-as-a-judge
- [Basics](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/model-as-a-judge/basics.md)
- [Getting a Judge-LLM](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/model-as-a-judge/getting-a-judge-llm.md)
- [Designing your evaluation prompt](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/model-as-a-judge/designing-your-evaluation-prompt.md)
- [Evaluating your evaluator](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/model-as-a-judge/evaluating-your-evaluator.md)
- [What about reward models](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/model-as-a-judge/what-about-reward-models.md)
- [Tips and tricks](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/model-as-a-judge/tips-and-tricks.md)

### Troubleshooting
The most densely practical part of this guide. 
- [Troubleshooting inference](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/troubleshooting/troubleshooting-inference.md)
- [Troubleshooting reproducibility](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/troubleshooting/troubleshooting-reproducibility.md)

### General knowledge
These are mostly beginner guides to LLM basics, but will still contain some tips and cool references! 
If you're an advanced user, I suggest skimming to the `Going further` sections.
- [Model inference and evaluation](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/general-knowledge/model-inference-and-evaluation.md)
- [Tokenization](https://github.com/huggingface/evaluation-guidebook/blob/main/contents/general-knowledge/tokenization.md)

## Yearly dives
- [2023, year of Open Source](https://github.com/huggingface/evaluation-guidebook/blob/main/yearly_dives/2023-year-of-open-source.md)
- [2024, what should evaluation be for?](https://github.com/huggingface/evaluation-guidebook/blob/main/yearly_dives/2024-evals-thoughts-from-iclr.md)
- [2025, evaluations to build "real life" useful models](https://github.com/huggingface/evaluation-guidebook/blob/main/yearly_dives/2025-evaluations-for-useful-models.md)

## Resources
Links I like
- [About evaluation](https://github.com/huggingface/evaluation-guidebook/blob/main/resources/about-evaluation.md)
- [About general NLP](https://github.com/huggingface/evaluation-guidebook/blob/main/resources/about-NLP.md)
- [The UltraScale Playbook](https://huggingface.co/spaces/nanotron/ultrascale-playbook)

## Community translations
This guide has been kindly community translated!
- 🇨🇳 https://github.com/huggingface/evaluation-guidebook/tree/main/translations/zh/contents, thanks to @SuSung-boy 
- 🇫🇷 https://huggingface.co/spaces/CATIE-AQ/Guide_Evaluation_LLM, thanks to @lbourdois

## Thanks
This guide has been heavily inspired by the [ML Engineering Guidebook](https://github.com/stas00/ml-engineering) by Stas Bekman! Thanks for this cool resource!

Many thanks also to all the people who inspired this guide through discussions either at events or online, notably and not limited to:
- 🤝 Luca Soldaini, Kyle Lo and Ian Magnusson (Allen AI), Max Bartolo (Cohere), Kai Wu (Meta), Swyx and Alessio Fanelli (Latent Space Podcast), Hailey Schoelkopf (EleutherAI), Martin Signoux (Open AI), Moritz Hardt (Max Planck Institute), Ludwig Schmidt (Anthropic)
- 🔥 community users of the Open LLM Leaderboard and lighteval, who often raised very interesting points in discussions
- 🤗 people at Hugging Face, like Lewis Tunstall, Hynek Kydlíček, Guilherme Penedo and Thom Wolf, and of course my teammate Nathan Habib with whom I've been doing evaluation and leaderboards since 2022

and of course to all the contributors :)

## Citation
[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC-BY--NC--SA-4.0-lightgrey.svg

```
@misc{fourrier2024evaluation,
  author = {Clémentine Fourrier and The Hugging Face Community},
  title = {LLM Evaluation Guidebook},
  year = {2024},
  journal = {GitHub repository},
  url = {https://github.com/huggingface/evaluation-guidebook)
}
```
