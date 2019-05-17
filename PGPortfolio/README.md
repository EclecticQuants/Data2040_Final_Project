This project is based on the original implementation of the paper, A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem ([arXiv:1706.10059](https://arxiv.org/abs/1706.10059)) and this [repo](https://github.com/ZhengyaoJiang/PGPortfolio).

The major work in the DATA2040 project focuses on:

1. Understand the architecture and the models 
2. Modify the downloading data code for database storage and management to avoid possible warnings. The major modification happens in ` pgportfolio/marketdata/globaldatamatrix.py`. 
3. Download the dataset and train the network from starch on the historical data of 8 coins from 2015/07/01 to 2017/07/01 using the `main.py` code. 
4. Modify the configuration file `pgportfolio/net_config.json` to change the dataset and the model structures. Implement experiments accordingly. 
