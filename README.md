# Kaggle_OpenVaccine_COVID-19_mRNA_Vaccine_Degradation_Prediction


## M2 Bioinformatics - Kaggle - Université de Paris


### OpenVaccine: COVID-19 mRNA Vaccine Degradation Prediction

Link : https://www.kaggle.com/c/stanford-covid-vaccine/overview/additional-resources


### Objectif : As part of a bioinformatics course project on AI. Determine which mRNAs are eligible for a vaccine with the lowest gradation rate.


### Data :

#### Files :
- train.json - the training data
- test.json - the test set, without any columns associated with the ground truth.
- sample_submission.csv - a sample submission file in the correct format


## Modules 
- python 3.9
- numpy
- pandas
- matplotlib
- scipy
- keras
- tensorflow
- jupyter
- google.colab (Uniquement sur Google Colab)



## Creating manually conda environment

```
$ conda create env -n open_vaccin python=3.9
$ conda activate open_vaccin
$ conda install numpy pandas matplotlib scipy keras tensorflow jupyter
```

To use this program, put the data in the same file as the notebook "OpenVaccine_Kaggle.ipynb".



## Références:

How RNA vaccines work, and their issues, featuring Dr. Rhiju Das
https://www.pbs.org/wgbh/nova/video/rna-coronavirus-vaccine/

Launch of the OpenVaccine challenge
https://scopeblog.stanford.edu/2020/05/20/stanford-biochemist-works-with-gamers-to-develop-covid-19-vaccine/

The impossibility of mass immunization with current RNA vaccines
https://www.wsj.com/articles/from-freezer-farms-to-jets-logistics-operators-prepare-for-a-covid-19-vaccine-11598639012

CDC prepares for frozen mRNA vaccines
https://www.cdc.gov/vaccines/acip/meetings/downloads/slides-2020-08/COVID-08-Dooling.pdf

Eterna, the crowdsourcing platform for RNA design where OpenVaccine's RNA sequences are coming from
https://eternagame.org

How to build a better vaccine from the comfort of your own web browser
https://medium.com/eternaproject/how-to-build-a-better-vaccine-from-the-comfort-of-your-own-web-browser-233343e0210d
