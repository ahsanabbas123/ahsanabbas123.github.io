---
layout: default
---

## Projects [under construction please refer to github repos]
---

### **Cervical Cancer Classification | CEERI, Pilani**

*August 2019 - Present*

I am currently working on making a mobile application for Cervical Cancer diagnosis and low-cost Colposcopic examinations at the Machine Vision Laboratory, CEERI-Pilani under [Dr. J L Raheja](https://www.ceeri.res.in/profiles/j-l-raheja/). 

---

### **Transformer Architecture From Scratch**

*April 2020*

PyTorch implementation of the Transformer model in "[Attention is All You Need](https://arxiv.org/abs/1706.03762)". 
This model is based solely on attention mechanisms and introduces Multi-Head Attention. The encoder and decoder are made of multiple layers, with each layer consisting of Multi-Head Attention and Positionwise Feedforward sublayers. This model is currently used in many state-of-the-art sequence-to-sequence and transfer learning tasks.  

The model reaches a bleu score of 35.44 which is comparable to the state of the art performances of recent models such as 'Multi-Agent Dual Learning' which reaches ~40 as reported on this [leaderboard](https://paperswithcode.com/sota/machine-translation-on-wmt2016-english-german).

---

### **Neural Machine Translation by Jointly Learning to Align and Translate**

*April 2020*

Allievates the information compression problem by allowing the decoder to "look back" at the input sentence by creating context vectors that are weighted sums of the encoder hidden states. The weights for this weighted sum are calculated via an attention mechanism, where the decoder learns to pay attention to the most relevant words in the input sentence.     
Based on the paper [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) on English to French [translation pairs](https://download.pytorch.org/tutorial/data.zip).

---

### **Entropy Based Distance Metric, Python Package | Institute of Genomics and Integrative Biology, New Delhi**

*May 2019 - July 2019*

A Unified Entropy-Based Distance Metric for Ordinal-and-Nominal-Attribute Data Clustering, used on calculating distances between phenotypic profiles.
Based on this [paper](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8671525&isnumber=8949827).

---
 
### **Applied Econometrics | Mentor: [Dr. N V M Rao](https://www.bits-pilani.ac.in/Pilani/nvmrao/profile)**

*February 2020*

Student grade prediction using an ensemble of SVM, Random Forest, Lasso/Ridge Regression. Also trained a two layer neural network with similar results to the ensemble but more robust to cross validation. Beating the reported scores in this [paper](http://www3.dsi.uminho.pt/pcortez/student.pdf) in 2/3 tasks.
[Dataset](http://archive.ics.uci.edu/ml/datasets/Student+Performance)

---

### **Realtime Reproduction Number for COVID-19**

*April 2020*

As a pandemic evolves, increasing restrictions (or potential releasing of restrictions) change R<sub>t</sub>. Knowing the current R<sub>t</sub> is essential. When R<sub>t</sub> > 1, the pandemic will spread through the entire population. If R<sub>t</sub> < 1, the pandemic will grow to some fixed number less than the population. The lower R<sub>t</sub>, the more manageable the situation. The value of R<sub>t</sub> helps us (1) understand how effective our measures have been controlling an outbreak and (2) gives us vital information about whether we should increase or reduce restrictions based on our competing goals of economic prosperity and human safety. 
[Well-respected epidemiologists](https://www.nytimes.com/2020/04/06/opinion/coronavirus-end-social-distancing.html) argue that tracking Rt is the only way to manage through this crisis.

Based on the implementation of [Bettencourt & Ribeiro 2008](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0002185) by [Kevin Systrom](http://systrom.com/blog/the-metric-we-need-to-manage-covid-19/) and applied to [data](https://bit.ly/patientdb) retrieved on April 13, 2020.
<br>

---


