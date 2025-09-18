# Precog Task: Language Representations

This repository contains the files I used to run the experiments.

The folder structure is:
- `load_dataset.ipynb`: Load the dataset and creates a split.

- `coccurance_matrix.ipynb`: Consists of constructing embeddings and visualizing them, dimention reduction etc.

- `Cross Language Embeddings`: Contains expreiments with language embeddings (Eng, Hi).

- `HarmFullAssociations`: Contains the experiements for the bonus task.

I didnt include the `wiki.en.vec` and `wiki.hi.vec` files as they were too big, however its easy to download from: 

```bash
wget https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.en.vec.zip
unzip wiki.en.vec.zip

wget https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.hi.vec.zip
unzip wiki.hi.vec.zip
```
`dataset/` folder contains some of the evaluation files I have used too, going through code it is explained.
Requirements are defined at the top of each .ipynb file, since code was run on colab, there is some reduncdunt code to change directories etc on the top of each file. 

Thank you !!
