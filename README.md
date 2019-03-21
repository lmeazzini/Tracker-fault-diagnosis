# Vehicle Tracker fault diagnosis

In this repository is presented some of my work developing some FDI (Fault Detection and Identification) models.

All the code is in Jupyter notebook files, and the data is private.

Each file does the following:
- Retirada de dados: Collect de data from a mongoDB instance;
- Tratamento de dados vetoriais: handmade feature extration, drastically reducion the dataset dimension;
- Análise e preprocessamento - especialista: Pre-processing and data analysis of the new features;
- Classificadores B1: Four Classifiers (RF, NB, SVM, MLP) to detect if there is a fault in the tracker;
- Classificadores B2: Four Classifiers (RF, NB, SVM, MLP) to detect and identify if there is, and what is the fault in the tracker;
- Tratamento para dados crus: Raw data pre-processing, without any manual feature extration;
- Dataset split: Spliting the raw dataset (Train/Test split);
- CNN 2D - FD: A CNN model to detect faults from raw data (model based on VGG-16);
- CNN 2D - FDI: A CNN model to detect and identify faults from raw data (model based on VGG-16)
