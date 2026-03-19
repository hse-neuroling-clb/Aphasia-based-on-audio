# Aphasia Classification Based on Patient Speech

## Repository Navigation

* models — Python files containing model classes  
* notebooks — Jupyter notebooks with experiments
* src — helper functions/classes and Streamlit web app  

## Problem Statement

Assistive systems are among the most demanded areas in machine learning.  
Even today, some doctors use artificial intelligence in their daily practice. It helps simplify diagnosis  
and enables personalized treatment for each patient.  
<br><br>  
Our work focuses on building a model to predict the presence of aphasia in a patient. Aphasia is a speech disorder  
that affects speech comprehension. It often occurs after a stroke, traumatic brain injury, or diseases  
related to the central nervous system. This condition can severely impact a person’s ability to communicate,  
especially in elderly individuals. However, if therapy starts early enough, recovery is possible.  
Therefore, having a tool that can detect the first signs of aphasia is crucial.  

## Dataset

The dataset was provided by Center for Language and Brain, HSE University. It includes 253 participants with aphasia  
and 101 without. Each participant has approximately two audio recordings. The participants belong to different age groups.  
The average age of aphasic participants is 58, and the distribution is close to normal. The non-aphasic group’s age  
distribution is more uniform, containing both young and elderly subjects.  
<br>  

Participant-level demographic information (such as aphasia status and age) is collected in the `pwa.demographic.info.csv` file.