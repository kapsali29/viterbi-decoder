# viterbi decoder

A Viterbi decoder uses the Viterbi algorithm for decoding a bitstream that has been encoded using convolutional code or trellis code.

There are other algorithms for decoding a convolutionally encoded stream (for example, the Fano algorithm). The Viterbi algorithm is the most resource-consuming, but it does the maximum likelihood decoding. It is most often used for decoding convolutional codes with constraint lengths k<=3, but values up to k=15 are used in practice.

Viterbi decoding was developed by Andrew J. Viterbi and published in the paper "Error Bounds for Convolutional Codes and an Asymptotically Optimum Decoding Algorithm", IEEE Transactions on Information Theory, Volume IT-13, pages 260-269, in April, 1967.

There are both hardware (in modems) and software implementations of a Viterbi decoder.
