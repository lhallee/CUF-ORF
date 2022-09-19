Code for https://doi.org/10.1101/2022.07.20.500846
Exploring Phylogenetic Classification and Further Applications of Codon Usage Frequencies

Codons are the repeats of three nucleic acids in genetic material read during translation. 64 total codons exist at different frequencies known to vary between organisms. Codon usage frequencies (CUFs) have recently been used for phylogenetic classification at different discrimination levels. However, the accuracy of phylogenetic classification and applications of this predictive power are not fully elucidated in the current literature. The goal of this project was two-fold: 1.) To increase the accuracy and depth of phylogenetic classification models using CUFs in literature. 2.) To explore the potential application of identifying open reading frames (ORFs) with CUFs. To increase the accuracy of classification models GridSearchCV, TensorFlow, and keras were used to design an improved Artificial Neural Network than the relevant example in the literature. Commonly used predictors were explored in an ensemble format that performs even better than the improved neural network. To explore a more discriminatory and phylogenetically deep classification K Means was used to look at possible clustering structures in the CUF data. To identify ORFs the codon frequencies of each potential ORF are compared to the frequencies of an organism of choice with a multinomial goodness-of-fit test. With correct optimization, these tests can reject possible ORFs with high confidence. In addition to these goals, the codons were ranked in terms of importance for classification with lasso regression and random forests feature ranking. This not only highlights exciting biology related to tRNA concentrations and the variance thereof, but is also helpful for optimizing the statistical tests for ORF identification.

![F3 large](https://user-images.githubusercontent.com/72926928/191124822-394c2251-49b4-49e0-8005-516e72a3f4ec.jpg)
![F4 large](https://user-images.githubusercontent.com/72926928/191124832-5708a9bd-0818-4562-ad0d-00f45364f97c.jpg)
