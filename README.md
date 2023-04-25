# CassavaLeaf-CIS519
Classifying Cassava Leaf Disease with deep learning

# File Purposes
Each Jupyter notebook corresponds to one of the models we examine in our project and can reproduce the results in the report.

# Setup Instructions
Our code relies on Kaggle to download the dataset and wandb.ai to tracking training process and results. To run our code without the dataset. You will need the following:

* A `kaggle.json` file that contains the Kaggle API keys needed to download the dataset. If data already exists, put them in a directory called `Data` in the same directory as the notebooks. If not, place the `kaggle.json` file in the same directory as the notebooks. The dataset will be downloaded at the beginning of script.

* A wandb.ai API key. Needed to login to perform metric logging.

To rerun our code, simply open the notebook and rerun each cell. Follow each cell's prompt to enter any API keys necessary.

All of our experiments are visible on https://wandb.ai/cassava/cassava-leaf
