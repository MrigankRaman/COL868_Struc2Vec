# COL868_Struc2Vec
This repository provides an implementation of benchmarking of Struc2Vec on BrightKite and Proteins Dataset
For creating the embeddings python2 is required and for the python notebooks python3 is required

before using this be sure to install the following packages
pip install futures
pip install fastdtw
pip install gensim
pip install keras
pip install tensorflow

Basic Usage:
To get the embeddings on a dataset just run
python src/main.py --input *edgelist* --output *output file* --num-walks 20 --walk-length 80 --window-size 5 --dimensions 128 --OPT1 True --OPT2 True --OPT3 True --until-layer 3

Then once embeddings have been generated just run the kernels in the python notebooks for the tasks. This repo can be used for other datasets as well. Just write the file locations correctly
