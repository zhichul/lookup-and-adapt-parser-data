# Look-up and Adapt: A One-shot Semantic Parser
This repository contains the data used to train and evaluate a one-shot semantic parser framework proposed in the paper [Look-up and Adapt: A One-shot Semantic Parser](https://github.com/zhichul/lookup-and-adapt-one-shot-semantic-parser-data "Look-up and Adapt: A One-shot Semantic Parser").

There are six domains in this dataset. For each domain there are the following data files:

* oldtrain.txt contains training examples generated from a set of "old" grammar rules from that domain.
* oldeval.txt contains evaluation examples generated from the same set of "old" grammar rules from that domain.
* neweval.txt contains evaluation examples generated from a set of "old" grammar rules AND some "new" grammar rules from that domain. Furthermore, each example in this file is generated with the use of exactly one "new" grammar rule and a number of "old" grammar rules.
* oldmemory.txt contains a seed set of examples for parsing oldtrain.txt by look-up and adapt.
* newmemory.txt extends oldmemory.txt with one-shot examples for parsing neweval.txt by look-up and adapt.
