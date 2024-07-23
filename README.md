### PDGeneFormer
This repository contains a fine-tuned version of the [GeneFormer model](https://huggingface.co/ctheodoris/Geneformer/tree/main) that is capable of discerning between Parkinson's and healthy control single cell transcriptomes.

Execute the following in a virtual environment to install Geneformer and its dependencies.
```
git clone https://huggingface.co/ctheodoris/Geneformer.git
cd Geneformer
pip install -r requirements.txt
```

#### Available files
``` 1.scRNAseq_data_exploration.ipynb ``` should be executed first to create the tokenized scRNAseq dataset that will be used as input to the Geneformer model.

``` 2.geneformer_finetuning.ipynb ``` contains the steps for fine-tuning the Geneformer model on classifying PD single cell transcriptomes.

``` 3.evaluation.ipynb ``` contains an evaluation of simpler baseline models compared to fine-tuned Geneformer.