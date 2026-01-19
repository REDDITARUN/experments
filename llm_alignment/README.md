# On the Fragility of Alignment

![Purpose](https://img.shields.io/badge/Purpose-AI%20Safety%20Research-blue)
![Status](https://img.shields.io/badge/Status-Educational%20Only-orange)

[Read the technical analysis →]([YOUR_BLOG_LINK_HERE](https://teendifferent.substack.com/p/apply_chat_template-is-the-safety))

## Abstract

Safety alignment in modern open-weight models, such as Gemma and Qwen, often 
functions as a behavioral veneer—a thin layer of instruction-tuning applied over 
a vast, unaligned base. 

We observe that this alignment is structurally dependent. By bypassing the 
prescribed chat template and utilizing raw prefix-inference, the Reinforcement 
Learning from Human Feedback (RLHF) guardrails can be effectively decoupled 
from the model's underlying knowledge base.



## Intent

This research is conducted under the principle of responsible disclosure. It 
exists to illuminate the mechanics of the "Template Bypass," where a model 
reverts from its simulated assistant persona to a raw next-token simulator.

### Research Objectives
- Characterize the failure modes of surface-level safety fine-tuning.
- Advocate for robust alignment that persists across diverse inference paths.
- Facilitate transparency in the open-source safety ecosystem.

### Ethical Constraints
- This repository is not a tool for generating harmful or illegal content.
- It is not intended to facilitate malicious bypasses of production systems.
- Usage must strictly adhere to the model provider’s terms of service.

The goal is to move beyond fragile, format-dependent safety. By demonstrating 
how easily these measures can be stripped away, we hope to catalyze the 
development of models where safety is a fundamental property of the weights 
themselves, not the prompt.
