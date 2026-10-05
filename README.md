# Autoregressive-Customizable-Bach-Chorale-Generation-Using-a-Lightweight-Hybrid-Model
This repository contains the codebase and dataset for Umut Olmez's master thesis: Autoregressive Customizable Bach Chorale Generation Using a Lightweight Hybrid Model. The all_data_augmented_text_compressed.zip file contains the zipped dataset that consists of 4584 text files where each represent a chorale from JS. Bach. Each file contains differing number of rows where each row contains 4 numbers (midi number for the played notes) separated by a space. Following is an example for the format of each file:

61 52 44 37

61 52 44 37

61 52 44 37

61 52 44 37

.

.

.

61 56 53 37

61 56 53 37

The first number in each row represents the soprano voice, second represents alto, third represents tenor and the fourth represents the bass. The data set is an augmented version of an existing dataset “ageron/handson-ml2/datasets/jsb_chorales” on github, which was based on czhuang's JSB-Chorales-dataset.


FINAL_MODEL_github.ipynb file contains the code for unzipping the data in the zip file to local disk, the code for processing the data to create the data tensor that will be used to train and validate the model, the hybrid model overview with dimensions, the code for the model architecture, the code for training and validation and the code for chorale generation. The generated chorale is in the same format as the training chorales.

ChoraleTextToMuseScoreCode.ipynb file contains the code for turning the generated chorales into musescore files from text files. The final musescore file may require some manual tweaking to get the final result.

Both code files have descriptions in them to help understand what is happening at every step and how everything is processed. You can access the thesis paper in the repository or from the following official Carnegie Mellon University link:

http://reports-archive.adm.cs.cmu.edu/anon/2025/CMU-CS-25-157.pdf
