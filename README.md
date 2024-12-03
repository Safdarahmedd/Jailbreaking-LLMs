# Jailbreaking-LLMs
This is a study on Jailbreaking Large Language Models (LLMs) done as part of the EL-GY-9133 Machine Learning for Cyber Security course at New York University. This repository contains the code for training prompts with `KOV.py`, `WhiteBox.py` and other supporting files. It also contains Jupyter Notebooks with results from Adversarial attacks with different Hyperparameters.

---

# Contributors

* **Aditya Ojha (ao2612@nyu.edu)**
* **Safdar Ahmed (sa8237@nyu.edu)**

---

### Abstract
The increasing prevalence of large language models (LLMs) in various applications has drawn significant attention to their potential vulnerabilities. Adversarial attacks on LLMs, particularly through prompt manipulation or "jailbreaking," reveal criti- cal flaws in their ability to align responses with ethical guidelines. In this study, we explore the KOV method, a novel approach to adversarial optimization that integrates token-level attacks with Markov Decision Processes (MDPs) and Monte Carlo Tree Search (MCTS). The KOV method enables multi-step optimization and generates interpretable adversarial prompts that maintain high effectiveness across models. Using Vicuna-7B as a proxy model and GPT-3.5 as the victim model, we evaluate the method. Through hyperparameter tuning and evaluation on the AdvBench benchmark, we demonstrate that the KOV method can generate transferable 
dversarial prompts. These findings highlight vulnerabilities in well-aligned LLMs and the necessity for robust adversarial defenses.

### Requirements
The following python packages are required to run the Jupyter notebooks:
* torch
* transformers
* os
* matplotlib
* seaborn
* fschat
* openai==0.28


---
