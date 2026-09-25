his repository contains the source codes used for the theoretical and experimental evaluation of the 5-round truncated differential distinguisher presented in our work.

The repository includes:

- A program for computing the theoretical probability of the distinguisher for Small-AES and the corresponding probability ratio with respect to a random permutation.

- Experimental programs for testing the distinguisher on Small-AES. The experiments are performed in the decryption direction for the four possible positions of the active nibble in a given column.

For each active-nibble position, the experiment uses 2^30 structures, each containing 2^4 ciphertexts, and is repeated over 2^5 independent keys. The results obtained for the four positions are combined to determine the experimental probability.

The implementations are written in C.

## Related Paper

**Another Truncated Differential Attack on 6-Round AES with All Key Sizes**

Can Balıkçı and Orhun Kara
