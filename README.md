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

Jupyter notebook and some libraries you can saw in the import of `Stocker.py` and `finance.ipynb`

# To run the file :

Clone this repository, install the libraries that may be missing and select `finance.ipynb`.
