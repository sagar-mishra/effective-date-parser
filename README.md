# effective-date-parser

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Directory Structure](#directory-structure)

## General info
Effective Date parser is a natural languaage processing based project. In this project we need to extract effective date from contracts. To solve this problem I have used QuestionAnsweringModel of Simple Transformers https://simpletransformers.ai/

## Technologies
* Python
* PyTorch

## Setup

### Installation 
* pip install requirements.txt

## Directory Structure
* config.py : contains all the configurations, you need to change directory paths and model_name and model_type if you wants to.
* util :
*   * data_creator.py : Create train, eval and test data which can be passed to simple transformers QuestionAnsweringModel
*   * model_output_post_processing.py : post process model prediction to get final output values
* notebooks :
*   * training.ipynb : I have trained model over google colab, you can use same notebook just some directory structure needs to be changed.

