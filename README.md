# LSTM-Donors-Choose
DonorsChoose.org has funded over 1.1 million classroom requests through the support of 3 million donors, the majority of whom were making their first-ever donation to a public school. If DonorsChoose.org can motivate even a fraction of those donors to make another donation, that could have a huge impact on the number of classroom requests fulfilled.

#### Data Source: https://www.kaggle.com/donorschoose/io

#### Attribute Information:
 - project_id: A unique identifier for the proposed project. Example: p036502 
 - project_titlei: Title of the project.
 - project_grade_category: Grade level of students for which the project is targeted.
 - project_subject_categories: One or more (comma-separated) subject categories for the project.
 - school_state: State where school is located (Two-letter U.S. postal code)
 - project_subject_subcategories: One or more (comma-separated) subject subcategories for the project. 
 - project_resource_summary: An explanation of the resources needed for the project.
 - project_essay_1/2/3/4: Application essay.
 - teacher_id: A unique identifier for the teacher of the proposed project.
 - teacher_prefix: nan, Dr./Mr./Mrs./Ms./Teacher
 - teacher_number_of_previously_posted_projects: Number of project applications previously submitted by the same teacher.
 - project_is_approved: A binary flag indicating whether DonorsChoose approved the project.A value of 0 indicates the project was not approved, and a value of 1 indicates the project was approved.

## Objective:
 The goal is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. 

## Prerequisites
You need to have installed following softwares and libraries before running this project.
1. Python 3: https://www.python.org/downloads/
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy and scipy: https://www.anaconda.com/download/

## Libraries
* __Gensim:__ Gensim is a Python library for topic modelling, document indexing and similarity retrieval with large corpora. Target audience is the natural language processing (NLP) and information retrieval (IR) community.
    * pip install gensim
    * conda install -c conda-forge gensim
* __Keras:__ Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.
    * pip install Keras
    * conda install -c conda-forge kera

* __scikit-learn:__ scikit-learn is a Python module for machine learning built on top of SciPy.
    * pip install scikit-learn
    * conda install -c anaconda scikit-learn

* __nltk:__ The Natural Language Toolkit (NLTK) is a Python package for natural language processing.
    * pip install nltk
    * conda install -c anaconda nltk


## Authors
•       Manish Vishwakarma - Complete work
