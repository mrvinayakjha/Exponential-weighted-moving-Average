# Exponential-weighted-moving-Average

The Exponentially Weighted Moving Average (EWMA) is commonly used as a smoothing technique in time series. However, due to several computational advantages (fast, low-memory cost), the EWMA is behind the scenes of many optimization algorithms in deep learning, including Gradient Descent with Momentum, RMSprop, Adam, etc.

In order to compute the EWMA, you must define one parameter β. This parameter decides how important the current observation is in the calculation of the EWMA.

### Lets make an example based on the temperatures of Paris, France, in 2019 ([1]).

![Screenshot 2024-02-18 at 2 27 20 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/9e97b0d2-2d80-4a79-b684-d9411ce98a80)


![Screenshot 2024-02-18 at 2 26 44 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/68a064cb-518c-4f22-b247-497af43fd08b)


![Screenshot 2024-02-18 at 2 30 09 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/67f74e62-5af2-4e97-b726-3e3f85994637)


![Screenshot 2024-02-18 at 2 30 39 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/e97b4dcc-5a19-4690-a60f-113659fae8cf)


![Screenshot 2024-02-18 at 2 31 03 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/c0756a9a-2fb3-4840-8373-5a5db3b58ba0)


![Screenshot 2024-02-18 at 2 31 37 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/ecec6fa3-80ef-452c-b854-c0b4947f64cd)


![Screenshot 2024-02-18 at 2 32 10 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/0a9bbf3f-0532-4957-8532-4da1405ccbd6)

![Screenshot 2024-02-18 at 2 33 43 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/a69003ea-310d-4f22-9c53-8b6a017f919a)

![Screenshot 2024-02-18 at 2 34 06 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/cc0ea363-b868-4f93-8c93-ac4f232965c6)

![Screenshot 2024-02-18 at 2 34 27 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/56af26e6-412c-4f39-beb8-5fbfc3b4a78d)

![Screenshot 2024-02-18 at 2 34 51 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/dbdee6ff-5b07-4091-90c1-15d7eadf8976)


![Screenshot 2024-02-18 at 2 35 41 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/06c38622-7dfe-4e40-868e-16a6a0e39f88)

![Screenshot 2024-02-18 at 2 36 01 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/8d87c577-4af8-467a-8c20-79aff9664fc7)

![Screenshot 2024-02-18 at 2 36 27 PM](https://github.com/mrvinayakjha/Exponential-weighted-moving-Average/assets/100670889/2bdc7912-2feb-49ea-ab47-bb23cf7333c7)

Credit : https://medium.com/mlearning-ai/exponentially-weighted-average-5eed00181a09
















