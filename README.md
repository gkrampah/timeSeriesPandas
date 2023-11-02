### Time series analysis

Time series is a sequence of data points that are organized in time order. That sequence will capture data at equally spaced points in time, and data collected irregularly is not considered times series.

**_ Standard regression models do not work for `time series models` _**

Features and targets are the same:

- Data is correlated where what happens in the prior period affect future events
- Often non-stationary (hard to model)
- Need a lot of data. The more data you have the better.

When there is a single value at each time step, the term univariate is used to describe them. Time series that have multiple values at each time step. As you might expect, they're called Multivariate/Panel Time Series. Multivariate Time Series charts can be useful ways of understanding the impact of related data.

## Time Series Data with Pandas
