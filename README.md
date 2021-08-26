
<h2 align="center"><i>Tensorflow - Word Embeddings</i></h2>
<p align='center'>
    <img src="https://www.python.org/static/community_logos/python-logo-inkscape.svg" width="150">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/TensorFlowLogo.svg/1229px-TensorFlowLogo.svg.png" width="100">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/2560px-NumPy_logo_2020.svg.png" width="150">
</p>

<br/>
<!--p align='center'>
  <img src="assets/demo_screen.gif">
</p-->

- Repository that contains several ways of getting word embeddings by using tensorflow models with different approaches.



# Table of Contents

- [Table of Contents](#table-of-contents)
- [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
- [Documentation](#documentation)

# Getting Started

## Requirements

The following libraries are [required](requirements.txt) to use this service:

```
numpy==1.19.5
tensorflow==2.6.0
tqdm==4.62.0
```



## Installation

After cloning the repository and setting the current working dir the same than the local repository, you can install the dependencies just by running the following command:

```
pip install -r requirements.txt
```

## Usage

To run the scripts, issue:

```
python train_imdb.py
```
or
```
python train_w2vec.py
```

Both scripts will generate a metadata file containing the vocabulary (metadata.tsv) words and also the embeddings file (vectors.tsv)


# Documentation

To be added
