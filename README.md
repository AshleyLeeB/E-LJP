# Construction and Interpretability Evaluation of Large Language Model for Legal Judgement Prediction

<table align="center" style="border: 1px solid white;">
  <tr>
    <td style="border: 1px solid white;"><img src="figs/swufe-logo.png" width="250"/></td>
    <td style="border: 1px solid white;"><img src="figs/Ethical-logo.jpg" width="60"/></td>
  </tr>
</table>

The goal of legal judgment prediction (LJP) is to predict results based on facts and provide convincing explanations. This task plays a critical role in upholding fairness within the legal system. However, the conventional explainable techniques are often convoluted to grasp. Large language models have advantages such as natural language output and multi-round dialogue, enabling clearer explanation for users. The current evaluation benchmarks are limited in handling complex evidence. Therefore, there is an urgent need to develop an explainable large language model of LJP and evaluation benchmarks and methods that align with real-world judicial processes to guide and improve model development. 

## Table of Contents
1. [Overview](#overview)
2. [E-LJP Construction](#e-ljp-construction)
3. [Interpretability Evaluation](#interpretability-evaluation)
4. [Conclusion](#conclusion)

## Overview

Through the use of P-Tuning v2 technology, the ChatGLM-6B was fine-tuned to create a lightweight, localized LJP model known as **Explainable Law Judgement Predition (E-LJP)**. The E-LJP focuses on two main areas: predicting multi-crime judgment and crime judgment reasoning. Following the principles of subjective and objective consistency and elementary trial in legal decision prediction, we aim to establish a benchmark and evaluation methods for evaluating the prediction based on concept forest. This dataset seeks to uncover the connections and differences between decision-making reasoning for crimes and the overarching concepts across different crimes.

<figure style="text-align: center;">
  <img src="figs/overview.jpg" alt="Overview of Construction and Interpretability Evaluation of Large Language Model for Legal Judgement Prediction">
</figure>

**Contact**:

<div style="overflow: hidden;">
  <ul>
    <li>Wangyue Li  (<a href="mailto:alee90792@gmail.com">alee90792@gmail.com</a>)
    <li>Wei Deng (<a href="mailto:dengwei@swufe.edu.cn">dengwei@swufe.edu.cn</a>)
  </ul>
</div>

## E-LJP Construction

<figure style="text-align: center;">
  <img src="figs/E-LJP.jpg" alt="Overview of Construction and Interpretability Evaluation of Large Language Model for Legal Judgement Prediction">
</figure>


### Model Annotations

### ChatGLM-6B P-Tuning

<figure style="text-align: center;">
  <img src="figs/chatglm.jpg" alt="Overview of Construction and Interpretability Evaluation of Large Language Model for Legal Judgement Prediction">
</figure>


### Gradio User interaction

## Interpretability Evaluation

<figure style="text-align: center;">
  <img src="figs/E-dataset.jpg" alt="Overview of Construction and Interpretability Evaluation of Large Language Model for Legal Judgement Prediction">
</figure>


## Conclusion
