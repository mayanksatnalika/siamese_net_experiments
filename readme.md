### Siamese network using Keras (v2.x) 
---
#### My experiments on Quora question similarity challenge

#### To Run: 

Download the dataset available [here](https://data.quora.com/First-Quora-Dataset-Release-Question-Pairs) 

Download glove word embeddings and keep them in root folder of project. 

#### Relevant references: 

* [the orginal research paper](http://www.aclweb.org/anthology/W16-1617) 
* [blog helpful to understand the actual distance metric used in paper.](https://medium.com/mlreview/implementing-malstm-on-kaggles-quora-question-pairs-competition-8b31b0b16a07) 

#### PS: 

* Seems the notebook fails to render most of the times on github and understanding it in raw-fromat close to impossible, use [this](https://nbviewer.jupyter.org/) to properly view the notebook in the browser. 
* Code is incomplete, had removed last few blocks to actually verify the output shapes from the network. Need to understand working of `np.sum (  )` in much more detailed. 