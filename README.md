# Stock-Prediction-using-Radial-Basis-Function-Neural-Network

1.	INTRODUCTION


1.1 About RBF 

About RBF stands for Radial Basis Function, and an RBF network consists of three layers, namely the input, hidden and output layer(or summation layer) is a feed forward neural network. Each neuron in the hidden layer uses RBF activation function(Eg: Gaussian function, Multiquadric function, inverse multiquadric function).The fundamental characteristic of an RBF is that the output value depends on the distance from the central point, known as the center. This distance-dependence allow RBFs to respond differently to inputs based on their proximity to the center, enabling them to capture complex, nonlinear relationships within data.

RBF is used for tasks like interpolation, patten recognition, signal processing, data clustering etc. The network operates by transforming the input data through RBFs into a higher-dimensional space where the relationship between data points can be linearly approximated. Training an RBF network involves determining the optimal centers and spread(how quickly the response is diminished with distance) of the RBFs, as well as the weights for combining their outputs, to minimize the error in predictions. This is often achieved using optimization techniques like gradient descent.

1.2 About the dataset 

The dataset has around 60 features which includes features extracted from OHLC (Open-high-low-close chart), other index prices such as QQQ(Nasdaq-100 ETF) & S&P 500, technical Indicators such as Bollinger bands, EMA(Exponential Moving Averages, Stochastic %K oscillator, RSI etc.).Lagged features from previous day price data have been created, as it is known that previous day prices affect the future stock prices. The data has date features which specify, whether it is  a leap year, or if it is  start or end of a month, Quarter start or end, etc.
All of these features have something to offer for forecasting. Some tells us about the trend, some gives us a signal if the stock is overbought or oversold, some portrays the strength of the price trend.


2. LITERATURE REVIEW

i.	Hongzheng Li and Shaohang Huang[2021] Research on the Prediction Method of Stock Price Based on RBF Neural Network Optimization Algorithm. In this paper integration of Radial Basis function neural network with K-means has been recognized as a promising approach to enhance prediction. By use of optimization function as K-means clustering  the neurons in the hidden is decreased due to this the training is faster and lowered the computational costs. There are some challenges which include selection of clusters, there is of overfitting. Thus, the integration of RBF Neural Networks with K-means clustering is presented as a compelling approach for stock price prediction, with improvements in accuracy, efficiency, and robustness being offered.
ii.	Minakhi Rout, et al [2012] Stock Indices Prediction Using Radial Basis Function Neural Network. In this paper the performance of the different models like Radial Basis Function Neural Network(RBFNN) with Multilayer  Layer  Neural Network  (MLANN)  and  Functional  Link  Artificial  Neural Network  (FLANN) to predict currency exchange between 1US$ to Indian Rupees and Japanese Yen. At the end, higher prediction accuracy and efficiency are offered by neural network models like RBFNNs, in comparison to MLANN and FLANN.
iii.	Bailin Lv and Yizhang Jiang[2021]Prediction of Short-Term Stock Price Trend Based on Multiview RBF Neural Network. The enhancement of stock price prediction accuracy through the use of Radial Basis Function (RBF) neural networks, which are augmented with multiview collaborative learning. Faced by traditional models are challenges due to the complex and nonlinear nature of stock data. Through the integration of multiview learning, the leveraging of diverse data aspects aims to improve prediction accuracy. By utilizing RBF networks strengths in handling nonlinearities and collaborative learning's enhancement of generalization across data views, traditional model limitations are overcome. Hence, multiview RBF neural networks to provide more accurate and reliable forecasts, signifying a notable advancement in financial market prediction technologies. 



3. RESULTS


![image](https://github.com/Sinchana-SH/Stock-Prediction-using-Radial-Basis-Function-Neural-Network/assets/116704673/9f40067c-133e-4981-89bb-7e4205b00729)

![image](https://github.com/Sinchana-SH/Stock-Prediction-using-Radial-Basis-Function-Neural-Network/assets/116704673/e7667a16-192c-43d0-9608-b58078292d52)

4. CONCLUSION


The study focuses on the utilization of Radial Basis Function (RBF) networks for predicting stock prices, presenting a comprehensive methodology that includes data acquisition, preprocessing, model creation, evaluation, and validation. RBF networks have proven to be successful in capturing complex nonlinear relationships within stock market data. The framework developed for RBF networks includes important features and performance evaluation using standard regression measures like Mean Absolute Error (MAE) and Mean Squared Error (MSE). When compared to traditional models, RBF networks demonstrate superior accuracy and robustness across a variety of datasets and validation techniques. They are particularly adept at identifying localized patterns and outliers, providing advantages over other methods such as MLP regression and SVR. RBF networks are highlighted as a valuable tool for predicting stock prices, offering flexibility, accuracy, and effectiveness in modeling the dynamic nature of financial markets. Overall, their adoption can help stakeholders better understand market trends and make informed investment decisions.


6. Reference
•	Hongzheng Li and Shaohang Huang[2021] “Research on the Prediction Method of Stock Price Based on RBF Neural Network Optimization Algorithm”
•	Minakhi Rout, et al [2012] “Stock Indices Prediction Using Radial Basis Function Neural Network”
•	Bailin Lv and Yizhang Jiang[2021]”Prediction of Short-Term Stock Price Trend Based on Multiview RBF Neural Network
