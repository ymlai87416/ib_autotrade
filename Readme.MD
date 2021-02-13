# IB Autotrade

Just a simple demo project to kick start my faith in TELSA

## Setup environment

This workspace is depends on 
    * Python 3.7
    * conda
    * Linux

Using 3.7 for better support [3]

```bash
conda create -n ibenv python=3.7
```

Download IB Gateway and install, For instruction please check: https://www.interactivebrokers.com.hk/en/index.php?f=16457 

Follow instruction to install Anaconda: https://www.anaconda.com/products/individual

if conda not found, please add the following line to .bashrc
export PATH=~/anaconda3/bin:$PATH

Download the Python API at here http://interactivebrokers.github.io/index.html#, navigate over to IBJts/source/pythonclient and run python3 setup.py install.


If you want to use ibapi with conda environment, execute the following

```bash
# Windows 啟動虛擬環境
activate python2
# Mac/Linux 啟動虛擬環境
source activate python2
# 安裝 ipykernel
pip install ipykernel
# 將虛擬環境新增至 Jupyter Notebook 的核心清單
python -m ipykernel install --user --name python2 --display-name "Python 2"
```

## Official tutorial



## Account login

Create a new account for the API access
https://ibkr.info/article/1004



## Backtesting demo

There are a lot of backtesting library

zipline?? quantopian shutdown in 2020
The data platform is now shutdown, so don't get a lot of hope

https://github.com/quantopian/zipline/issues/2616



## Strategy implementation

Book for reference

1. 
2. 
3. i chi moku

## Backtest notebook



## The final goal

1. Able to tell me some interesting stock
2. Allow me to run some algo on a stock and backtest them
3. When algo is running, gen report for algo deteriation


## Reference

[1] https://www.quantstart.com/articles/backtesting-systematic-trading-strategies-in-python-considerations-and-open-source-frameworks/ 

[2] https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

[3] https://endoflife.date/python
