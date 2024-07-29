# Bitcoin Price Model Comparison

This project creates 2 models to predict the price of Bitcoin, see notebooks:
1. Using the sentiment index Fear and Greed (FNG)
2. Using the previous closing prices

## It answers the following questions:

1. Which model has a lower loss?

The closing price model has a significantly lower loss (approx 0.002 vs 0.5)

2. Which model tracks the actual values better over time?

The closing price model tracks the actual values mush better, although the FNG index does generally track directionally correctly.

3. Which window size works best for the model?

A window size of 1 shows a slight improvement over 3 or 10, particularly for the closing model.