<h1 align="center">Stocker</h1> 
<div align="center">
  <strong>Simple prediction tool on stocks</strong>
</div>


This project use Will Koershen's [Stocker](https://github.com/WillKoehrsen/Data-Analysis/tree/master/stocker) to give the trend of a given stock. It uses a modified version of Stocker to get any source data and clean it to create a time series. Then it uses [Facebook Prophet model](https://facebook.github.io/prophet/) which aims at 

> *forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.*

For instance :

<div align="center">
<img src=https://cdn.pbrd.co/images/I0duLoT.png alt="Paris" class="center">
</div>



# Requirements :

Python 3.6 and the following packages are required:

	quandl 3.3.0
	matplotlib 2.1.1
	numpy 1.14.0
	fbprophet 0.2.1
	pystan 2.17.0.0
	pandas 0.22.0
	pytrends 4.3.0

These can be installed with pip from the command line
(some of these might require running the command prompt as 
administrator). 

`pip install -U quandl numpy pandas fbprophet matplotlib pytrends pystan`

If pip does not work and you have the Anaconda 
distribution, try installing with conda:

`conda install quandl numpy pandas matplotlib pystan`

`conda update quandl numpy pandas matplotlib pystan`

pytrends and fbprophet can only be installed with pip. If you run into 
any other errors installing packages, check out [Stack Overflow](https://stackoverflow.com/)

# To run the file :

Clone this repository, install the libraries that may be missing and select `finance.ipynb`.
