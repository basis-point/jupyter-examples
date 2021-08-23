<img width="25%" src="https://uploads-ssl.webflow.com/5fe3e7bd2382b0d5adcf9755/5fe45f175b0aa8f5fde8da09_basispoint_jade.png">

# Zero coupon swaps example

Valuation and risk analysis examples of zero coupon swaps.

## Overview

This directory contains examples demonstrating how to build, value and analyse the risks of zero coupon swaps using the open source library [QuantLib](https://www.quantlib.org/).

We are looking into various options of constructing interest rate swap term structures, under different interpolation schemes.
We show the impact that interpolation may have on the valuation of derivatives, zero coupon swaps in this case.

![](graphs/forward_curves.png)

Interpolation may introduce some artifacts into the distribution of sensitivities. It is important to understand what kind of effects can be expected and how to mitigate them.

![](graphs/sensitivities.png)

In case of questions or feedback contact us [via email](mailto:info@basispoint.io) or visit [our website](https://basispoint.io).

[![Contact](https://img.shields.io/badge/Contact-Email-lightgrey?style=flat-square)](mailto:info@basispoint.io)
![GitHub](https://img.shields.io/github/license/basis-point/jupyter-examples?style=flat-square)

## Run Jupyter notebook

Click on the button below to run this notebook online.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/basis-point/jupyter-examples/master?filepath=%2Fnotebooks%2Fzero_coupon_swaps%2Fzero_coupon_swaps_example.ipynb)

## Used data

* Financial data ICE Benchmark Administration Limited (IBA), ICE Swap Rates, 12:00 P.M. (London Time), Based on Euros, retrieved from FRED, [Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org/);
* [EMMI](https://www.emmi-benchmarks.eu/euribor-org/euribor-rates.html) interest rate benchmark fixings.