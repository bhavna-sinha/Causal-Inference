# Causal-Inference
Causal Inference with Meta Learners This repository contains experiments and implementations related to Causal Inference using Meta Learners, including T-Learner, S-Learner and  X-Learner. The focus is on estimating heterogeneous treatment effects (HTE) and evaluating different methodologies on synthetic and real-world datasets.

# Causal Inference with Meta Learners

## Overview
This repository explores **Causal Inference** techniques using **Meta Learners** to estimate heterogeneous treatment effects (HTE). The goal is to experiment with different methodologies, compare their performance, and understand their practical applications in observational data settings.

## What are Meta Learners?
Imagine you’re a bank manager deciding whether to increase a customer’s credit limit. You want to know:

- Will increasing the credit limit make them spend more?
- Will it increase the risk of them not paying back?
- Will it make them more loyal, reducing the chance they switch to another bank?
  
To make a smart decision, you could look at historical data—what happened to customers when their limits were increased in the past. But here’s the challenge:

- Some people naturally spend more, even without a credit limit increase.
- Some customers would have stayed loyal anyway, regardless of the limit.
- Some customers would have defaulted, even if their limit remained the same.
  
So, how do we separate the real effect of increasing the credit limit from other factors? That’s where Meta-Learners come in.

## Simple Explanation of Meta-Learners
Think of Meta-Learners like different ways of answering the question:
"What would have happened if we had (or had not) increased a customer's credit limit?"



The main types of Meta Learners include:
- **S-Learner**: Uses a single model with treatment as an additional feature.
- **T-Learner**: Trains separate models for treatment and control groups.
- **X-Learner**: Designed for high-dimensional, imbalanced data using two-stage learning.

