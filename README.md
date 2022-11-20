# Product Recommendation for NFT eCommerce using Amazon Personalize

This is a PoC demo to give an overview how to collect data, train and get product recommendation from Amazon Personalize.
The PoC includes:
1. How to create product recommendation with Amazon Personalize \[Collect, Train\]
2. Evaluate the result with offline metric and backtesting \[Evaluate\]
3. Using AWS SDK to retrieve recommendation for a user combined with item metadata \[Inference\]

Remarks:
- It is a demo to show the fundamental features and help you get started.
- The result is derived from sample user-item interaction data which is for reference only.
- Demo is built programmatically by using AWS SDK in Sagemaker Notebook. However, the same can also be implemented via AWS Management Console.

## Data source copyright @ Moonstream NFTs dataset 

Here I use a sqlite file to simulate NFT Mall Transcation database. 
SQLite file comes from The Moonstream NFTs dataset (https://github.com/bugout-dev/moonstream/blob/main/datasets/nfts/papers/ethereum-nfts.pdf)

Data source copyright @ https://www.kaggle.com/datasets/simiotic/ethereum-nfts