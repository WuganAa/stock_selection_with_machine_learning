# stock_selection_with_machine_learning
Stock selection with machine learning 

* code:
  the code of the project

  * run.py 
    running all four models in model dictionary

  * factors:
    all indicators is get from [tushare](https://tushare.pro/) and calculated with [talib](https://github.com/mrjbq7/ta-lib)
    * finIndicatormd.md: finincial indicators lists
    * technical_index.py: technical indicators lists

  * model:
    all model class dictionary
    * base.py: abstract model class
    * \_\_init\_\_.py: import model

  * portfolio.py
    calculate the equity when we have the weight of portfolio and plot the equity

  * genetic_algorithm.py
    Genatic Algorithm using in factors selection

  * dataview.py
    load and process data from [jaqs](https://github.com/quantOS-org/JAQS)

  * data_generate.py
    generate dataview data into the format using in training model

  * blacklitterman.py

    the Black Litterman Model 

* results:
  the results of the processes

  * 20181003-135120:
    training: 20050701-20141231
    testing: 20141231-20180701

  * 20181004-214808
    training: 20050701-20121231
    testing: 20121231-20180701