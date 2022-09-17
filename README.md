# algorithmic-trading

This app analyzes the pricing data of stocks and make decisions about when to buy and sell shares.

## Technologies

This project uses python 3.9 with the following:

* [jupyter](https://jupyter.org/)

* [pandas](https://pandas.pydata.org/)

* [NumPy](https://numpy.org/)

* [hvPlot](https://hvplot.holoviz.org/)

* [scikit-learn](https://scikit-learn.org/)


## Usage

Ensure that all dependencies are installed
```
pip install -U scikit-learn
conda install -c pyviz hvplot
```

Clone the repository and run jupiter notebook:
```
machine_learning_trading_bot.ipynb 
```


## Contributors

Contributed by [Theena Dang](maria.cristina.dang@gmail.com)

---

## License

[MIT](LICENSE)


## Evaluation Report

This is the graph of the baseline.

![Baseline](/images/scenario1_plot.png)


This is the graph using LogisticRegression classifier

![Baseline LogisticRegression](/images/scenario1_test_plot.png)