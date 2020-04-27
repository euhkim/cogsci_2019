# What Syntactic Structures block Dependencies in RNN Language Models?

This repository contains materials needed to reproduce `What Syntactic Structures Block Dependencies in RNN Language Models` presented at the CogSci 2019 in Montreal, CA.

Each folder contains two types of files an `items` file  and an `input` file:

• The `input` file are the test sentences given to the RNNs, with one sentence per line, already tokenized on whitespace.

• The `items` file contains token-by-token information that corresponds with each sentence from the `input` file in `tsv` format. Information included: sentence index, word index, word, word region and condition.

Word-by-word surprisals derived from the `input` files was harmonized with the `items` files to produce the analyses for the paper.