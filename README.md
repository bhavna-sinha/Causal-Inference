# Causal-Inference
Causal Inference with Meta Learners This repository contains experiments and implementations related to Causal Inference using Meta Learners, including T-Learner, S-Learner and  X-Learner. The focus is on estimating heterogeneous treatment effects (HTE) and evaluating different methodologies on synthetic and real-world datasets.

# Causal Inference with Meta Learners

## Overview
This repository explores **Causal Inference** techniques using **Meta Learners** to estimate heterogeneous treatment effects (HTE). The goal is to experiment with different methodologies, compare their performance, and understand their practical applications in observational data settings.

## What are Meta Learners?
Meta Learners are machine learning-based approaches for estimating treatment effects in causal inference. They decompose the problem into multiple predictive models and allow flexible estimation of individualized treatment effects.

The main types of Meta Learners include:
- **S-Learner**: Uses a single model with treatment as an additional feature.
- **T-Learner**: Trains separate models for treatment and control groups.
- **X-Learner**: Designed for high-dimensional, imbalanced data using two-stage learning.

