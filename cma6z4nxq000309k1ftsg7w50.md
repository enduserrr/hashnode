---
title: "Gradients in AI Training"
seoTitle: "Gradients in AI Training oversimplified"
seoDescription: "Learn about gradients in AI training, their role in optimizing model parameters, and how they help reduce loss through backpropagation"
datePublished: Fri May 02 2025 15:53:54 GMT+0000 (Coordinated Universal Time)
cuid: cma6z4nxq000309k1ftsg7w50
slug: gradients-in-ai-training
tags: ai, machine-learning-models, llm

---

Gradients are essentially vectors expressing the changes (direction and magnitude) to be applied to the parameters of the model being trained. Gradients are produced by a miner during a training run and they aim to minimize loss by optimizing model parameters.

Parameters are the internal setting of the model in training, expressed as vectors, which are mathematical values representing a direction and a magnitude for a value. Gradients are used to change any parameters that caused loss in the previous epoch in order to minimize loss in the next one.

## Use:

1. A given miner computes gradients on their assigned data batch.
    
2. Once done, resulting gradients are sent to the network to be aggregated (averaged) with the gradients by other miners of the network.
    
3. Aggregated gradient is then used to update the model parameters, optimally resulting in less loss than before the run.
    
4. Shared for the next iteration and training run.
    

## Creation Process

Gradients get created during a training run based on any loss occuring during the run. The trained model uses something called **backpropagation** to determine the amount much each parameter contributed to the loss in relation to other parameters, and based on that the gradients get created to show which parameters need adjusting, to which direction and for how much.

## TL:DR

Gradients are instructions for tweaking the trained model’s parameters in order reduce loss. They are produced by miners during a training run, after which they are applied to the model before the next training run.