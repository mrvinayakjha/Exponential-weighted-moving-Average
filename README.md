# Exponential-weighted-moving-Average

The Exponentially Weighted Moving Average (EWMA) is commonly used as a smoothing technique in time series. However, due to several computational advantages (fast, low-memory cost), the EWMA is behind the scenes of many optimization algorithms in deep learning, including Gradient Descent with Momentum, RMSprop, Adam, etc.

In order to compute the EWMA, you must define one parameter β. This parameter decides how important the current observation is in the calculation of the EWMA.

### Lets make an example based on the temperatures of Paris, France, in 2019 ([1]).

![Screenshot 2024-02-18 at 2 27 20 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/9e97b0d2-2d80-4a79-b684-d9411ce98a80)


![Screenshot 2024-02-18 at 2 26 44 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/68a064cb-518c-4f22-b247-497af43fd08b)

