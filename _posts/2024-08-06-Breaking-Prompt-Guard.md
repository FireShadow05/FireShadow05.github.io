---
layout: post
---
### Introduction

The recent release of Meta AI's Llama 3.1 Family of Models introduced Prompt Guard, a transformer-based classifier designed to act as a safeguard against prompt injections and jailbreaking attempts. However, Large Language Models (LLMs) like Llama have already demonstrated vulnerability to gradient-based attacks, resulting in successful jailbreaks. This susceptibility stems from a general weakness in deep learning models to gradient-based adversarial perturbations.

Given this context, a critical question arises: Do guardrails such as Prompt Guard truly enhance the security of LLMs against harmful outputs? Or are they, like other deep learning models, equally susceptible to adversarial attacks?

This blog post aims to address this question by exploring the effectiveness of Prompt Guard and similar safeguards. We introduce a novel approach that builds upon the concept of Greedy Coordinate Gradient (GCG), which adds an adversarial suffix to harmful prompts. Our method generates an adversarial prefix that, when used on an adversarial payload, can effectively deceive Prompt Guard into misclassifying potentially harmful inputs as benign.

Through this investigation, we seek to shed light on the robustness of current LLM safeguards and contribute to the ongoing discussion on AI safety and security.

[Continue Reading...](https://repello.ai/blog/breaking-metas-prompt-guard-why-your-ai-needs-more-than-just-guardrails)