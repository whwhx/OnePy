Onepy  
===========

##### 2017.09.05
  - version 1.52.1
  - add bar class, combine all feed

##### 2017.09.04
  - verison 1.51.1
  - add more doc
  - add abstractmethod to Base module

##### 2017.09.03
  - version 1.50.1
  - 代码大部分重构，使层级更清晰一些
  - 运用OO思想，新增order模块和dataseries模块
  - 运用pylint和pycharm，对代码进行PEP8规范整理
  - 新增从MongoDB读取数据后进行回测的功能
  - 新增了一些tests

##### 2017.08.06
  - version 1.3.1
  - fix commission computation
  - add commission plot


##### 2017.08.05
  - version 1.2.1
  - fix trailingstop
  - fix the computation of avg_price, unre_profit
  - fix lots of thing in fill.

##### 2017.08.04
  - version 1.1.1
  - fix update_timeindex
  - fix commission bug
  - fix trailstoploss bug
  - change name: limit --> takeprofit， stop --> stoploss
  - fix the position of check_pending_order function
  - fix drawdown

##### 2017.08.01
  - version 1.00.1
  - del utils folder, which copied from backtrader
  - make code more clear
  - change csv.reader to csv.Dictreader in feed
  - fix tlog, before lots of trades with 0 zip are confusing
  - fix computation of tlog bug, before cum_total in tlog is wrong
  - fix bug in strategy.py: when Exitall and other orders
     appeared at the same time, executions
    are confusing, now if Exitall exit, only execute Exitall


##### 2017.07.28
  - version:0.99.1
  - Abandon Python2.x, all code are upgraded to Python3
  - fix feed indexing.
  - fix drawdown computation

##### 2017.07.27
  - version:0.81.1
  - All code are converted to support Python3.6!
  - fix commission computation bug
  - fix limit&stop bug

##### 2017.07.24
  - version: 0.80.1
  - add get_analysis func
  - fix tlog


##### 2017.07.23
  - version: 0.70.1
  - add stock mode
  - fix update_info bug: should update info first
  - add new plot : plotly engine
  - add futures mode
  - clean code of plotter
  - add Futures feed
  - add trade_log
  - clean code of strategy

##### 2017.07.22
  - version: 0.61.1
  - fix indicator bugs
  - fix limit and stop bug! A Huge One.
  - add more detail output_summary
	  - Final_value
	  - Total_return
	  - Max_Drawdown
	  - Duration
	  - Sharpe_Ratio
  - add a new tool: dict_to_table

##### 2017.07.21
  - version: 0.60.1
  - add indicator module
  - add SimpleMovingAverage indicator
  - add pip install

##### 2017.07.20
  - version: 0.30
  - add trailingstop
  - all '==' changed to 'is' to speed up
  - fix bug： check whether cash is enough
  - fix HUGE Bug： the compution of profit (takes me lots of time)
    - unrealized_profit
    - realized_profit
  - add commission
  - fix Exitall Bug
  - add very easy plot module

##### 2017.07.19
  - version: 0.21
  - fixed a Huge Bug: add update_timeindex function
  - fixed the cumpute method of Fill
  - add set_pricetype function
  - fix fill logic
  - add pips and pct method for buy&sell

##### 2017.07.17
  - version: 0.2
  - add limit, stop, 挂单
  - add notify
  - add Exitall


##### 2017.07.16
  - version: 0.1
  - Finally can run!!!!!!!!!!
  - add Buy and Sell
  - Most of modules are completed


##### 2017.07.14
  - version: 0.01
  - add feed module
  - add OnePy--the Main Event Loop

##### 2017.07.11
  - version: 0.00000001
  - add to_MongoDB tool
