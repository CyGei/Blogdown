---
date: "2023-01-18"
external_link: ""
image:
  caption: ''
  focal_point: ''
  preview_only: no

summary: A R package and Shiny Web App to visualise and retrive headlines for a stock at any given time.

tags:
- Other

title: Learn about a stock's history with `stocktracker`
---

<br>

<div style="text-align: justify">

# What?

`stocktracker` is a R package available on Github. It produces a reactive time series chart of a stock where the user can click on any time point of the chart to retrieve the top news for that stock around that day.

# Why?

Stocks go up and down, before investing you might want to check the company's history to reveal why its stock fluctuated at certain times. Sometimes that's just the market gods other times that's because there was a new product launch or a mass layoff . Find out with `stocktracker` what were the top headlines at the time your stock went up or down.

# How?

`stocktracker` retrieves top headlines related to your stock when you click on a specific point on the chart. You will need to register at [newsapi.org](newsapi.org) to obtain an API key (for now).

If the app doesn't fit this webpage well, check out the [`stocktracker`](https://cygeismar.shinyapps.io/stocktracker/)'s website instead.

<iframe src="https://cygeismar.shinyapps.io/stocktracker" width="100%" height="500">

</iframe>
