# melody-conditioned-lyrics-generation

This repo contains the code for melody conditioned SeqGANS and melody conditioned RelGANs.

The dataset is obtained from the work done by Yi Yu, Abhishek Srivastava, Simon Canales for the work "Conditional LSTM-GAN for Melody Generation from Lyrics"

The preprocessing required for the models to work is done in the notebook "Create Dataset"

The baseline used for this is SeqGAN based on the work "Melody-Conditioned Lyrics Generation with
SeqGANs" by Yihao Chen and Alexander Lerch.

The RelGAN model is based on the work "RelGAN: Relational Generative Adversarial Networks for Text Generation" by Weili Nie, Nina Narodytska, Ankit Patel. This work builds upon the RelGAN and uses techniques from Reinforcement Learning to build a model that uses BLEU scores, precision and recall as rewards to train a better model.

Works with torch 1.8.2. Requires tensorflow only for preprocessing and tokenizing data.