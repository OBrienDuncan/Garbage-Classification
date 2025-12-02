# Garbage-Classification
This is a school project for my DS3000 course

Download the respective models and datasets here: https://uwoca-my.sharepoint.com/:f:/g/personal/dobrie25_uwo_ca/IgDX7Q0KWqEOSoJ6k7BaC7pwAc87mqphifV5rUMFFefvR6k?e=8S9fBV

Make sure every file is in the same directory to replicate exactly how the notebook was executed

The main code with models, results, tables, and graphs is found DS3000ProjectFinal.ipynb in the main branch 

To get reproducibility in the notebook, observe 'howfilesshouldbeplaced' in the main branch

Group members:

Duncan O'Brien - 251317636

Alexander Katsoris - 251356451


Dataset:

Combination of two datasets:
Garbage dataset classification: https://www.kaggle.com/datasets/zlatan599/garbage-dataset-classification
Our own dataset of photos of types of waste found around my house


Problem:

Many individuals struggle to identify the different types of garbage when sorting through their waste, especially when items have similar shapes and appearances. This project is designed to be used as a computer vision-based accessibility aid to help those individuals who may struggle with sorting their garbage. It enables a person to use their smartphone to scan a piece of garbage and instantly receive the classification of the waste type. The core of the system will either be a supervised learning (SVMs) or deep learning (CNNs) model trained to recognize different classes of waste. For example: paper, plastic, glass, metal, and cardboard using images. A machine learning approach is suitable because waste items vary significantly with color, shape, size, texture, and lighting conditions, making rule-based classification unreliable. By learning visual patterns directly, the model can better classify across real world scenarios, including variations in camera quality and environmental conditions. This model will ensure proper sorting of waste items, which plays a crucial impact on the environment in many ways such as the following: It helps reduce the consumption of raw materials, water and energy; It reduces greenhouse gas emissions as less waste ends up in landfills or being incinerated; It helps limit soil and water pollution, as waste incinerated or sent to landfills release toxic substance such as heavy metals, dioxin, and furans that are harmful for biodiversity and human health. Companies can also use this technology to automatically sort waste efficiently in large scale operations.
