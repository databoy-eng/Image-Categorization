# Image-Categorization
## Project Overview
Our goal, as a product owner is to build a product that helps doctors quickly identify cases of pneumonia in children. You'll want to build a classification system that

1) Can help flag serious cases
2) Quickly identify healthy cases
3) And, generally, act as a diagnostic aid for doctors

As such, this project is designed to test your ability to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images; this can be used by ML engineers later on down the line to build a classification product. The main task will be to create a data labeling job using Figure Eight's platform. If you have not yet, you'll need to create a Figure Eight account and login to complete this project.

If you intend to purchase any services through Figure Eight, you'll want to use a valid business email so you can receive notifications. But for the project, if you do not have a business email, you can use the above workaround in the meantime.

# The Data
The dataset is a modified version of this Kaggle chest x-ray dataset, with most labels removed. Every piece of data is a chest x-ray image. You may see images taken that are slightly different in size and taken under slightly different exposure times. A typical, labeled image is shown below.

A labeled, healthy, chest x-ray image. Pay close attention to the two lungs and diaphragm (below the lungs).

# What Does Pneumonia Look Like?
This is a challenging task because it is not always clear when pneumonia symptoms are present or not in an image. As such, your system is not meant to be a replacement for a doctor, only to aid in quickly identifying healthy patients and surfacing potential cases of pneumonia.

You should design a data annotation job, such that a non-expert can identify more noticeable cases of pneumonia. Since you are designing for a non-expert annotator, you should design for failure; this means including some way to capture uncertainty in your data labels and test questions.

So, what indicates pneumonia and what kind of advice and examples can we give potential annotators?

There are a few different visual symptoms that indicate pneumonia. The most important areas to have annotators pay attention to are the lungs and the diaphragm.

a) A normal, healthy image will depict clear lungs without any areas of abnormal cloudiness/opacity; there may be structured, web-like vasculature in the lungs but otherwise that area should be clear. In healthy images, you are also more likely to see a diaphragm shadow.
b) A pneumonia image may include a few things: areas of cloudiness/opacity in several concentrated areas or one large area. You may also see a general pattern of opacity that obscures the structure of the lungs, heart and diaphragm.

Designing a Data Labeling Job
One of your biggest tasks will be to design an appropriate data labeling job using Figure Eight's platform. You will need to submit an HTML file of a complete job Preview, which includes: 1. Instructions for annotation and 2. Example test questions. You will also need to submit a Proposal document that discusses the design of the job and steps you'll take for quality assurance.

