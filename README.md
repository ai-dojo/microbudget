
<br />
<div align="center">
  <h2 align="center">AI on a Microbudget</h2>

  <a href="https://github.com/clstaudt/audiomariner">
    <img src="fig/logo.jpg" alt="Logo" width="140" height="140">
  </a>


  <p align="justify">
<i>In recent years, the AI field has pursued ever larger models, trained at “eye-watering” cost. In this talk we explore ideas for the rest of us, the GPU-poor. We’ll show you how to make do with less – less computing power, less person power, less data – while still building powerful models.</i>
  </p>
</div>


## Part 1: Methods of Machine Learning Miniaturization

Current progress in AI has seen remarkable capabilities emerging from simple prediction tasks – if we scale them massively. Surprisingly, we get sparks of reasoning and intelligence in a model that was trained to do little more than masked word prediction. Since that realization the AI field has pursued ever larger models, trained at “eye-watering” cost. If scaling is all you need – does it follow that, in practice, money is all you need?

In this talk we explore ideas for the rest of us, the GPU-poor. Taking examples from language processing and computer vision, we’ll show you how to make do with less – less computing power, less person power, less data – while still building powerful models. We will introduce a set of methods and open source tools for the efficient reuse and miniaturization of models, including transfer learning and fine-tuning, knowledge distillation, and model quantization. We will also discuss how to choose efficient model architectures, and investigate ways in which small and specialized models can outperform large models. Our talk aims to provide an overview for ML practitioners, draws from our combined project experience, and is accompanied by a repository of code examples to get you started with building AI on a microbudget.

📙 [**Companion Notebooks: Table of Contents**](notebooks/ai-on-a-microbudget.ipynb)


## Setup

1. Clone repository
2. Install requirements listed in `requirements.txt`, e.g.

> `pip install -r requirements.txt`

3. Run workflow notebooks.

---
_This material is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). Copyright © 2024 [Christian Staudt](https://clstaudt.me), [Katharina Rasch](https://krasch.io)_