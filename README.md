# UrbanSoundClassif

## Description
AI project on UrbanSound8k dataset, which can be found : https://www.kaggle.com/prabhavsingh/urbansound8k-classification/notebook

There is multiple notebooks :
- BIGNN using Transfer learning on wide_resnet
- NN using small CNN on "compressed spectrogram" 

## Getting started  
You can choose one of the notebbok.

It is possible to run only the predict part, you just need to run the cells allowing to import required libraries, define paths, until the one loading the dataset, in this case the prediction will be based on pretrained network, which are training from previous run of the complete notebook.
### On Colab : 
Import the notebook on google colab and clone the dataset on your own drive

### On jupyter notebook :
- Clone the dataset on your desktop from the drive
- Replace the paths according to location of dataset on your computer
- Remove google colab import and drive.mount() call.
- Run it in jupyter


### Executing program
Before running you must require to install : 
- torchvision
- torch
- torchaudio
- numpy
- pandas
- scikit-learn
- matplotlib

## Help
In case of issue, you can contact me by mail : jordan.jouanchicot[at]gmail[dot]com

## Author 
Jordan Rey-Jouanchicot
mail : jordan.jouanchicot[at]gmail[dot]com

## Version history :
0.1 : June 6 2021 : Initial Release with two notebooks : BigNN and NN

## License 
This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, dataset source, code snippets, etc.
- https://arxiv.org/pdf/2007.11154.pdf
- https://www.kaggle.com/prabhavsingh/urbansound8k-classification/notebook
- https://pytorch.org/
- https://www.fast.ai/2018/07/02/adam-weight-decay/
