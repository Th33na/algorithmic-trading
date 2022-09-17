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

# Baseline
This is the graph of the baseline using SMA of 4 and 100, with 3 months training date from 04/02/2015 - 07/02/2015. It has a precision of 56% and f1 score of 71% for the good trades. The model has a 55% accuracy.

![Baseline](/images/scenario1_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 56% and f1 score of 61% for the good trades. The model has a 52% accuracy. Lower but still more than 50%.


![Baseline LogisticRegression](/images/scenario1_test_plot.png)

# Case 2:

This is the graph using SMA of 4 and 100, with 6 months training date from 04/02/2015 - 10/02/2015. It has a precision of 56% and f1 score of 71% for the good trades. The model has a 56% accuracy.

![Scenario 2 Baseline](/images/scenario2_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 56% and f1 score of 71% for the good trades. The model has a 56% accuracy. Lower but still more than 50%.


![Scenario 2 LogisticRegression](/images/scenario2_test_plot.png)


# Case 3:

This is the graph using SMA of 10 and 100, with 3 months training date from 06/12/2015 - 09/12/2015. It has a precision of 56% and f1 score of 69% for the good trades. The model has a 55% accuracy.

![Scenario 3 Baseline](/images/scenario3_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 53% and f1 score of 12% for the good trades. The model has a 44% accuracy. Very low f1 score and under 50% accuracy, leading this model/strategy unrecommendable.


![Scenario 3 LogisticRegression](/images/scenario3_test_plot.png)

# Case 4:

This is the graph using SMA of 4 and 100, with 6 months training date from 06/12/2015 - 12/12/2015. It has a precision of 56% and f1 score of 66% for the good trades. The model has a 54% accuracy.

![Scenario 4 Baseline](/images/scenario4_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 56% and f1 score of 37% for the good trades. The model has a 47% accuracy. Very low f1 score and under 50% accuracy, leading this model/strategy unrecommendable.


![Scenario 4 LogisticRegression](/images/scenario4_test_ploy.png)

# Case 5:

This is the graph using SMA of 5 and 150, with 3 months training date from 04/15/2015 - 07/15/2015. It has a precision of 56% and f1 score of 72% for the good trades. The model has a 56% accuracy.

![Scenario 5 Baseline](/images/scenario5_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 56% and f1 score of 58% for the good trades. The model has a 51% accuracy.


![Scenario 5 LogisticRegression](/images/scenario5_test_plot.png)

# Case 6:

This is the graph using SMA of 5 and 150, with 6 months training date from 04/15/2015 - 10/15/2015. It has a precision of 56% and f1 score of 72% for the good trades. The model has a 56% accuracy.

![Scenario 6 Baseline](/images/scenario6_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 57% and f1 score of 66% for the good trades. The model has a 54% accuracy.


![Scenario 6 LogisticRegression](/images/scenario6_test_plot.png)

# Case 7:

This is the graph using SMA of 15 and 150, with 3 months training date from 04/15/2015 - 07/15/2015. It has a precision of 56% and f1 score of 72% for the good trades. The model has a 56% accuracy.

![Scenario 7 Baseline](/images/scenario7_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 57% and f1 score of 70% for the good trades. The model has a 55% accuracy.


![Scenario 7 LogisticRegression](/images/scenario7_test_plot.png)

# Case 8:

This is the graph using SMA of 15 and 150, with 6 months training date from 04/15/2015 - 10/15/2015. It has a precision of 56% and f1 score of 72% for the good trades. The model has a 56% accuracy.

![Scenario 8 Baseline](/images/scenario8_plot.png)


This is the graph using LogisticRegression classifier applied. It has a precision of 57% and f1 score of 66% for the good trades. The model has a 55% accuracy.

![Scenario 8 LogisticRegression](/images/scenario8_test_plot.png)

# Conclusion
Looking at graph, case 6 using SMA of 5 and 150, with 6 months training date from 04/15/2015 - 10/15/2015, yielded the better returns. 

It is good to understand that having a well bounded SMA and a larger better timed training sample will yield to a better model/return







