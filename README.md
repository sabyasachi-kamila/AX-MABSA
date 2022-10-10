# AX-MABSA

This repository is a pytorch implementation for the following paper accepted in # EMNLP 2022 (main):

#### [AX-MABSA: A Framework for Extremely Weakly Supervised Multi-label Aspect Based Sentiment Analysis]

[Sabyasachi Kamila], 
[Walid Magdy], 
[Sourav Dutta], 
[MingXue Wang]

## Requirements

- Python 3.8
- argparse=1.1
- torch=1.6.0
- torchvision=0.11.1
- scikit_learn=1.0
- numpy=1.21.2
- nltk=3.6.5
- pandas=1.4.1
- transformers=4.11.0
- sentence_transformers=2.0.0-py3.8
- scipy-1.7.1

# Fine-tuned Models
Download the models from *. Place the models in the models folder. 

# Dataset

Required datasets are placed in the data folder. For new dataset place them in the following manner:

```bash
|flabsa
|--- data
|    |--- rest-14
|    |    |--- dataset.txt
|    |    |--- labels-cat.txt
|    |    |--- labels-pol.txt
|    |    |--- classes-cat.txt
|    |    |--- classes-pol.txt
|--- models (models: fine-tuned, updatable)
|    |--- model-bert-uncased-rest-train-80k
|--- outputs (results, automatically build)
|
```

# Run
Run ./run.sh in the command line.
You should edit run.sh for choosing different domains, datasets, algorithms.

## Citation
NA
