# Multi Horizon Forecasting for Limit Order Books
In this work I implemented the models (DeepLOB-Seq2Seq and DeepLOB-Attention) proposed in [Multi-Horizon Forecasting for Limit Order Books: Novel Deep Learning Approaches and Hardware Acceleration using Intelligent Processing Units](https://arxiv.org/pdf/2105.10430.pdf) by Zihao Zhang and Stefan Zohren. 

In every notebooks is proposed all the machine learning pipeline, starting from the loading of the dataset, passing from the labeling method, creation of the datasets and dataloaders, ending with the train, validation and test.

I reached the same results of the original paper.

# Usage

To run the code you just have to download the [FI-2010 dataset](https://etsin.fairdata.fi/dataset/73eb48d7-4dbc-4a10-a52a-da745b47a649/data) and change the data path, then the notebook will do the rest, including the training and testing.
