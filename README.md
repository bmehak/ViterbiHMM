# Viterbi HMM

## Objective

To implement the Viterbi algorithm for predicting the most probable sequence of hidden states in a DNA sequence.

## Model

States:

* S (Start)
* E (Exon)
* SS (Splice Site)
* I (Intron)
* END

## Method

* Used transition and emission probability matrices
* Applied dynamic programming (Viterbi)
* Used log probabilities to avoid numerical underflow

## Output

* Best hidden state sequence
* Log probability of the sequence

## Tools

* Python
* NumPy
* Google Colab
