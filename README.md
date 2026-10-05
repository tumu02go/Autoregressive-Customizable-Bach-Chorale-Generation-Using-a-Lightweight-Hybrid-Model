# Autoregressive-Customizable-Bach-Chorale-Generation-Using-a-Lightweight-Hybrid-Model
This repository contains the codebase and dataset for Umut Olmez's master thesis: Autoregressive Customizable Bach Chorale Generation Using a Lightweight Hybrid Model. The all_data_augmented_text_compressed.zip file contains the zipped dataset that consists of 4584 text files where each represent a chorale from JS. Bach. Each file contains differing number of rows where each row contains 4 numbers (midi number for the played notes) separated by a space. Following is the format of each file:

61 52 44 37

61 52 44 37

61 52 44 37

61 52 44 37
.
.
.
61 56 53 37

61 56 53 37

The first number in each row represents the soprano voice, second represents alto, third represents tenor and the fourth represents the bass.

FINAL_MODEL_github.ipynb file contains the code and architecture of
