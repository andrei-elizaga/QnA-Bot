# QnA-Bot
QnA bot powered by CoQA + BERT built in Pytorch. This project was done as course project of EE 763 jointly with [Rakesh](https://github.com/RKhobrag) and [Kuber](https://github.com/kuberg1/)

## Installation

- Install [pipenv](https://pipenv-fork.readthedocs.io/en/latest/#install-pipenv-today) to manage dependecies.
- Set the [python version](https://pipenv-fork.readthedocs.io/en/latest/basics.html#specifying-versions-of-python):

```
	pipenv --python 3.6
```
- Install the package requirements found on the Pipfile:

```
	pipenv install
```
- Install the language model used by [spacy](https://spacy.io/models/en#en_core_web_md):

```
	pipenv run python -m spacy download en_core_web_md
```


- Download the pretrained model from : https://drive.google.com/file/d/15HOJmRizBrgoPPVDHKpvSO2tNf0k-d8f/view?usp=sharing

- Run the flask server

```
	pipenv run python server.py
```

Google Colab [Demo](https://colab.research.google.com/drive/1Alz7NMENYc1S28EqUDwbe7hf1M8HpYSO#scrollTo=vT40VTBxJMlT)

## Running

![alt text](https://raw.githubusercontent.com/arijitx/QnA-Bot/master/running.gif)
