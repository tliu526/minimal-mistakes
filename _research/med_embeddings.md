---
title: Medical Concept Embeddings
excerpt: "An ongoing research project at IBM. We are applying temporal and ontological information via attention mechanisms to improve learned medical code embeddings."
# link: TODO
date: 2017-06-01
---

This is an ongoing research project under Dr. Kenney Ng, manager of the Healthcare Analytics Research Group (HARG), and Dr. Soumya Ghosh, a HARG research staff member.

## Abstract
The widespread adoption and usage of electronic medical records (EMRs) in recent years has facilitated improvements and new techniques in medical informatics. Neural Network Language Models (NNLMs) in particular have shown great promise in learning distributed, low-dimensional representations of medical concepts. However there are some challenges to be addressed: 1) NNLMs require large amounts of data to train, which may not be feasible to obtain given the privacy and interoperability challenges of healthcare ecosystems and 2) NNLMs with static contexts do not account for the temporal burstiness of medical record information. We propose a modification to the CBOW Word2Vec model that address these concerns by integrating both ontological and temporal information via attention mechanisms. Our method incorporates both sources of information while still maintaining the lightweight shallow model architecture of Word2Vec. We evaluate the quality of our learned medical embeddings through a quantitative measure of medical similarity, the downstream prediction task of heart failure onset prediction, as well as through patient stratification and clustering analysis.
