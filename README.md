<h1 align="center">Stock Price Prediction </h1>

<div align= "center">
  <h4>We build a stock price prediction using LSTM neutral network. Then we build a dask board using Plotly dask for display our analysis </h4>
</div>
<img src="https://github.com/quangtruong9/Stock_price_prediction/blob/master/demo.gif"/>

## :warning: TechStack/framework used
- LSTM
- ARIMA
- [Plotly Dash](https://plotly.com/dash/)

## :star: LSTM (Long Short Term Memory)
LSTMs are very powerful in sequence prediction problems because they’re able to store past information. This is important in our case because the previous price of a stock is crucial in predicting its future price.

<img src="https://github.com/quangtruong9/Stock_price_prediction/blob/master/readme_img/lstm.png">

LSTM were create as the solution to short-term memory. They have internal mechanisms called gates that can regulate the flow of information. These gates can learn which data in a sequence is important to keep or throw away. By doing that, it can pass relevant information down the long chain of sequences to make predictions. Almost all state of the art results based on recurrent neural networks are achieved with these two networks.

## :star: ARIMA (AutoRegressive Integrated Moving Average)
<ul>
  <li> <strong>AR: < Auto Regressive ></strong> means that the model uses the dependent relationship between an observation and some predefined number of lagged observations (also known as “time lag” or “lag”).
 </li>
  <li> <strong>I:< Integrated ></strong> means that the model employs differencing of raw observations (e.g. it subtracts an observation from an observation at the previous time step) in order to make the time-series stationary.MA:
  </li>
  <li><strong>MA: < Moving Average ></strong>means that the model exploits the relationship between the residual error and the observations.</li>
</ul>

## 🚀&nbsp; Installation
1. Clone the repo
```
https://github.com/quangtruong9/Stock_price_prediction.git
```
2. Install Plotly Dash
```
pip3 install dash
pip3 install dash-html-components
pip3 install dash-core-components
```
3. On terminal run this command:
```
python3 stock_app.py
```
to run app.

4. Open browser at 127.0.0.1:8050.
