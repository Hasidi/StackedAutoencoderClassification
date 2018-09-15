# StackedAutoencoderClassification

## Classify cells to cell cycle stage using neural networks with stacked auto encoders. 
The experiment: https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-2805/ -
Read about single cell RNA sequencing, mESC and cell cycle stages.

Evaluate classification accuracy using a stacked autoencoder neural network.

Evaluating an ordinal classifier that consists of two models: 

    a. binary classifier of G1 vs. S+G2/M  
    b. binary classifier of G1+S vs. G2/M

![Image description](https://github.com/Hasidi/StackedAutoencoderClassification/blob/master/Autoencoder_scheme_A.png)

![Image description](https://github.com/Hasidi/StackedAutoencoderClassification/blob/master/Autoencoder_scheme_B.png)
