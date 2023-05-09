---
date: "2023-01-18"
external_link: ""
image:
  caption: ''
  focal_point: ''
  preview_only: no

links:
- icon: fas fa-link
  icon_pack: fas
  name: App
  url: https://cygeismar.shinyapps.io/TickerTales/


summary: A R package and Shiny Web App to visualise, retrieve and analyse headlines for a Ticker name at any given time.

tags:
- Other

title: Learn about a stock's history with TickerTales.
---

<br>

<div style="text-align: justify">

# What?

`TickerTales` is a R package available on [Github](https://github.com/CyGei/TickerTales). The `Shiny App` produces a reactive time series chart of a stock where the user can click on any time point on the chart to retrieve the top news for that stock around that day.

# Why?

Stocks go up and down, before investing you might want to check the company's history to reveal why its share price fluctuated at certain times. Sometimes that's just the market gods, other times that's because there was a new product launch or a mass layoff . Find out with `TickerTales` what were the top headlines at the time your stock went up or down.

# How?

`TickerTales` retrieves top headlines for a given ticker name at any time point. It has a few wrappers from [`tidytext`](https://github.com/juliasilge/tidytext) to obtain the sentiment score or the key topics using sentiment analysis & topic modelling. You will need to register at [newsapi.org](newsapi.org) to obtain an API key. Interact with the `Shiny App` to explore the data and use the `R` package to analyse the sentiment per headlines over time.

<br>

<div style="text-align: center">

🔗 <https://cygeismar.shinyapps.io/TickerTales/>
