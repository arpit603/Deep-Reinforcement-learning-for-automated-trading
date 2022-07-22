# Deep-Reinforcement-learning-for-automated-trading
An attempt to automate trading and make it much more efficient


## Abstract
Stock trading strategies play a critical role in investment. However, it is challenging to design a profitable strategy in a complex and dynamic stock market. In this paper, a deep ensemble reinforcement learning scheme that automatically learns a stock trading strategy by maximizing investment return. A deep reinforcement learning agent and obtain an ensemble trading strategy using the three actor-critic based algorithms: Proximal Policy Optimization (PPO), Advantage Actor Critic (A2C), and Deep Deterministic Policy Gradient (DDPG). The ensemble strategy inherits and integrates the best features of the three algorithms, thereby robustly adjusting to different market conditions. We have made the protoype for the same model to implement the research paper


## Reference
Hongyang Yang, Xiao-Yang Liu, Shan Zhong, and Anwar Walid. 2020. Deep Reinforcement Learning for Automated Stock Trading: An Ensemble Strategy. In ICAIF ’20: ACM International Conference on AI in Finance, Oct. 15–16, 2020, Manhattan, NY. ACM, New York, NY, USA.

#### Windows 10

To install stable-baselines on Windows, please look at the (https://stable-baselines.readthedocs.io/en/master/guide/install.html#prerequisites).
    
**Create and Activate Virtual Environment (Optional but highly recommended)

Steps :
        cd into this repository
        ```bash
        cd Deep-Reinforcement-Learning-for-Automated-Stock-Trading-Ensemble-Strategy-ICAIF-2020
        ```
        Under folder /Deep-Reinforcement-Learning-for-Automated-Stock-Trading-Ensemble-Strategy-ICAIF-2020, create a virtual environment
        ```bash
        pip install virtualenv
        ```
        Virtualenvs are essentially folders that have copies of python executable and all python packages. 

        Create a virtualenv **venv** under folder /Deep-Reinforcement-Learning-for-Automated-Stock-Trading-Ensemble-Strategy-ICAIF-2020
        ```bash
        virtualenv -p python3 venv
        ```
        To activate a virtualenv:
        ```
        source venv/bin/activate
        ```
## Dependencies
pip install -r requirements.txt

## Run DRL Ensemble Strategy
```shell
python run_DRL.py
```
## Backtesting

Use Quantopian's [pyfolio package](https://github.com/quantopian/pyfolio) to do the backtesting.

[Backtesting script](backtesting.ipynb)
