.. TradingFlow documentation master file, created by
   sphinx-quickstart on Tue May 22 18:41:04 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to TradingFlow's documentation!
=======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

TradingFlow is an open source trading platform that integrates live-trading, strategy researching and backtesting, and automatic trading. It provides trading API to various brokers and exchanges. You can trade stock, various kinds of derivatives, foreign currency, cryptocurrency, and gold on TradingFlow.

You can fork this project on `GitHub <https://github.com/RockmanZheng/TradingFlow>`_.

Introduction
============

Automated trading system is a computer program that creates orders and automatically submits them to a market center or exchange. The program will automatically generate orders based on predefined set of rules using a trading strategy. TradingFlow contains functions just like this.

The basic idea behind trading is buy at low price and sell it at high price. This may seem absurdly simple. However, determining exactly when to trade and how much to trade so that it's ultimately profitable is still a pretty tricky technique. And needless to say, to maximize the profit would require knowledge and skill set of a PhD. The rules selecting perfect trading time spot, and resonable trading amount would be called as *strategy*.

TradingFlow's goal is to provide you a platform to test your strategy, and let you put it into live-trading and hopefully earn money for you. It accomplish this goal by including the following modules:

* **Event-Driven System**. Almost all elements are treated as events. Quotes from brokers, order submitted by the system, etc. are events so that we can use similar interfaces in live-trading and in backtesting.




Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
