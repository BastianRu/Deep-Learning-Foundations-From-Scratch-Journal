# Deep-Learning-Foundations-From-Scratch-Journal

This repository is a collection of my personal research and implementations of core Machine Learning architectures. Instead of relying on high-level abstractions, I focus on building models from the ground up to master the mathematical and computational principles behind Artificial Intelligence.

**The Mission**: 
My goal is to document my journey through the "first principles" of AI, moving from basic scalar autograd engines to large-scale Transformers.

Note: This is a **Work In Progress**. These notebooks serve as a live journal of my learning process, featuring detailed theoretical annotations and manual tensor operations.

## 📂 Research Notebooks

### 1. Autograd & MLP from Scratch
A deep dive into the mechanics of backpropagation.

* Key Insights: Implementation of a custom Value class to handle scalar autograd with topological sort. (Based on Karpathy's Micrograd)

* Features: Manual implementation of __add__, __mul__, and __pow__ with their respective _backward gradient flows.
___

### 2. Probabilistic Neural Language Models
Inspired by the seminal Bengio et al. (2003) paper.

* Key Insights: Building word feature vectors (embeddings) and analyzing the effects of Batch Normalization.

* Features: Manual management of bngain and bnbias to control pre-activation distributions and avoid "hockey stick" training issues.  
___

### 3. Energy-Based Models (EBM) Variants
Exploring alternative energy-based architectures for language modeling.

* Key Insights: Implementing custom energy functions and logits through manual tensor contractions.

* Features: Use of F.cross_entropy for numerical stability while maintaining full control over the energy-to-logit pipeline.
___

### 4. Character-Level Language Models
Foundation of generative modeling using character transitions.

* Key Insights: Mastery of Multinomial Sampling and deterministic generation using torch.Generator.

* Features: Detailed analysis of bigram probability matrices and the transition from uniform to learned distributions.
