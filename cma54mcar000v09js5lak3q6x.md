---
title: "AI Training Basics"
seoTitle: "Learn a Little: AI Training Basics"
seoDescription: "General glance at loss, epochs, learning rates, and more."
datePublished: Thu May 01 2025 08:52:05 GMT+0000 (Coordinated Universal Time)
cuid: cma54mcar000v09js5lak3q6x
slug: lal-ai-training-basics
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1746089184175/e4d5eeed-582f-454d-96c1-8430bcdc9121.jpeg
tags: ai, machine-learning, techexplained

---

*In a nutshell, training an AI model is an attempt to find just the right settings, data and learning speed for the model to absorb meaningful insight from the training data without the process taking forever.*

In practice AI model training consists of multiple training runs called epochs, which all aim to minimize loss (failure). That’s done by updating the models internal settings called parameters after each run based on the results called gradients from the previous run.

## Loss

Loss is simply a numerical value describing the magnitude of an AI model failing to provide an optimal answer to a given query. (what’s considered optimal is task and model specific).

*Higher loss = less accurate answer & lower loss = more accurate answer.*

**Loss is always bad and loss spikes even worse.**

### **Loss Function**

Loss function is how the amount of loss is measured in a given task. There’s different types of loss function for measuring different types of tasks.

### **Loss Spike**

Loss spike is a sudden unexpected increase (spike) in loss during training, which could imply too high learning rate or bad training data. Loss and loss spikes are used during training runs to monitor performance and to identify areas of improvement.

## Parameters & Hyperparameters

### Parameters

Parameters are like the models internal settings, which are adjusted during training. They include model weights (numbers deciding how much each input matters in the model), and biases into which I won’t go for now.

### Hyperparameters

Hyperparameters are like the models global settings which are defined once before starting to train the model. They include learning rate, data batch sizes, epoch count (explicitly or implicitly) and a lot more.

## Epoch

An epoch is one full run through all the training data. Training a model tends to take multiple iterations, i.e. epochs due to **learning rate** limitations.

Epoch count is a part of the models “global settings” called hyperparameters. Epoch count can be staticly defined as a pre determined number but usually it’s set dynamically by **learning rate** and a **stopping condition** like reaching good enough a loss threshold.

Epochs also involve something called forward and backward passes (basically predictions and updates to model weights using backpropagation but more on that later).

## Learning Rate

The amount of adjustments to the models settings after a training run to minimize loss where there were some.

A rate too large can lead to over correction and result in to loss spikes to the opposite direction of what was being fixed (unexpected incorrect results).

A rate too small results in increasing iterations needed to train the model.

## Overfitting & Underfitting

### **Overfitting**

Overfitting is when the model learns the training data too well (noise included), leading to failing with new data due to the difference in noise. It’s like memorizing everything while not understanding nothing.

### **Underfitting**

Underfitting is when model is too simple and misses the key insight (patterns) from the data, leading it not to learn any meaningful insight from it.

## TL;DR

Loss spikes shown by loss functions reveal where the AI model is wrong, epochs give the model multiple chances to incrementally improve, and the learning rate controls how fast it adjusts and therefore indirectly affects how many epochs successfully training a model requires.