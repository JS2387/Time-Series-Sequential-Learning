# Time Series & Sequential Learning

This repo contains my solutions for the laborations for the course Time Series and Sequential Learning offered at LiU during the autumn semester

## Lab1: Autoregressive Models

In this lab we build autoregressive models for a data set corresponding to the Global Mean Sea Level (GMSL) over the past few decades. The data is taken from https://climate.nasa.gov/vital-signs/sea-level/ 

## Lab2: Structural model, Kalman filtering and EM

We will continue to work with the Global Mean Sea Level (GMSL) data that we got acquainted with in lab 1. In this lab we will analyse this data using a structural time series model. We will first set up a model and implement a Kalman filter to infer the latet states of the model, as well doing long-term prediction. We will then implement a disturbance smoother and an expectation maximization algorithm to tune the parameters of the model.

## Lab 3: Nonlinear state space models and Sequential Monte Carlo

In this lab we make use of a non-linear state space model for analyzing the dynamics of SARS-CoV-2, the virus causing covid-19. We use an epidemiological model referred to as a Susceptible-Exposed-Infectious-Recovered (SEIR) model. It is a stochastic adaptation of the model used by the The Public Health Agency of Sweden for predicting the spread of covid-19 in the Stockholm region early in the pandemic, see Estimates of the peak-day and the number of infected individuals during the covid-19 outbreak in the Stockholm region, Sweden February – April 2020.

## Lab 4: Recurrent Neural Networks

In this lab we will explore different RNN models and training procedures for a problem in time series prediction. We will build a model for predicting the number of sunspots. We work with a data set that has been published on Kaggle, with the description:

_"Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are regions of reduced surface temperature caused by concentrations of magnetic field flux that inhibit convection. Sunspots usually appear in pairs of opposite magnetic polarity. Their number varies according to the approximately 11-year solar cycle."
_
The data consists of the monthly mean total sunspot number, from 1749-01-01 to 2017-08-31.
