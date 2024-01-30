# Forecasting Net Prophet

You’re a growth analyst at [MercadoLibre](http://investor.mercadolibre.com/investor-relations). With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

Instructions

This section divides the instructions for this Challenge into four steps and an optional fifth step, as follows:

* Step 1: Find unusual patterns in hourly Google search traffic

**Question:** Did the Google search traffic increase during the month that MercadoLibre released its financial results?

**Answer:** Yes, May's search trend was higher than the average of searches of every other month

* Step 2: Mine the search traffic data for seasonality

**Question:** Does any day-of-week effect that you observe concentrate in just a few hours of that day?

**Answer:** Yes slightly, days 1-4 seem to get a little more traffic. It is easy to tell that most traffic is coming in late a night into the early morning hours

**Question:** Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?

**Answer:** # Yes, it does. By week 41 things are really taking off

* Step 3: Relate the search traffic to stock price patterns

**Question:** Do both time series indicate a common trend that’s consistent with this narrative?

**Answer:** Yes, you can tell that right before March, the search trends died out until mid March. The close price of MercadoLibre Stock also dipped and came back up following the the google trends.

* Step 4: Create a time series model with Prophet

**Question:**  How's the near-term forecast for the popularity of MercadoLibre?

**Answer:** High

**Question:** What time of day exhibits the greatest popularity?

**Answer:** Late at night

**Question:** Which day of week gets the most search traffic?
   
**Answer:** Tuesday

**Question:** What's the lowest point for search traffic in the calendar year?

**Answer:** Mid- October 

* Step 5 (optional): Forecast revenue by using time series models

### Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.

**Answer:** After analizing the data it seems that we have 3 projected outcomes that could play out. The worst case senario is that the projected sales will be $887 Million. The Best case senario is roughly 1.05 Billion for the next quarter. The most likely senario is $969 Million for the next quarter.

