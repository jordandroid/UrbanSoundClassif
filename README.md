# UrbanSoundClassif

## Description
AI project on UrbanSound8k dataset, which can be found : https://www.kaggle.com/prabhavsingh/urbansound8k-classification/notebook

There is two notebooks, one for each model :
- BIGNN using Transfer learning on wide_resnet
- NN using small CNN on "compressed spectrogram" 

For more information, read the pdf report included.
## Getting started  
You can choose one of the notebook.

It is possible to run only the predict part, you just need to run the cells allowing to import required libraries, define paths, until the one loading the dataset, in this case the prediction will be based on pretrained network, which are training from a previous run of the complete notebook.

(Pretrained weights are available in this github)
### On Colab : 
Import the notebook on google colab and clone the dataset on your own drive.

or add to your own drive from the following links :
- BIGNN : https://colab.research.google.com/drive/14ngHKbbtSyR0-YRWsPH9-CDPRlp1xeR7#scrollTo=WVr_xaVtEhOB
- NN : https://colab.research.google.com/drive/1YydWStXOiJ4AO90AaDRcQ56RhqiargTs

And clone the dataset on your own drive.

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
0.2 : June 16 2021 : Updated and cleaned notebooks, updated README file and report
0.1 : June 6 2021 : Initial Release with two notebooks : BigNN and NN

## License 
This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, dataset source, code snippets, etc.
- https://arxiv.org/pdf/2007.11154.pdf
- https://www.kaggle.com/prabhavsingh/urbansound8k-classification/notebook
- https://pytorch.org/
- https://www.fast.ai/2018/07/02/adam-weight-decay/
