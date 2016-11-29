# Stock-Market-Forecasting
Individual investors have more investment options than they often realize. Options like” stock options” allow us to make money if the stock market is going up and it also causes loss if the stock market is going down. As the name suggests, options give you the option to buy or sell a security (stocks, extra-traded funds, indices, commodities etc.) at some point in the future. Our team has decided to forecast the stock market for the investors (our users) to make a wise decision. It is said that regardless of any technique, accurately forecasting stock market performance is more a matter of luck than technique. However, our team has decided to forecast the stock price using “Random walk” forecasting model.
•	Call Options: It provide the holder the right to purchase an underlying asset at a specified price for a certain period of time. If the stock fails to meet the strike price before the expiration date, the option expires and becomes worthless. Investors buy calls when they think the share price of the underlying security will rise or sell a call if they think it will fall. Selling an option is also referred to as ''writing'' an option.
•	Put options: It give the holder the right to sell an underlying asset at a specified price (the strike price). The seller (or writer) of the put option is obligated to buy the stock at the strike price. Put options can be exercised at any time before the option expires. Investors buy puts if they think the share price of the underlying stock will fall, or sell one if they think it will rise.

Random walk is a stock market theory that states that the past movement or direction of the price of a stock or overall market cannot be used to predict its future movement. Originally examined by Maurice Kendall in 1953, the theory states that stock price fluctuations are independent of each other and have the same probability distribution, but that over a period of time, prices maintain an upward trend. In short, random walk says that stocks take a random and unpredictable path. The chance of a stock's future price going up is the same as it going down. A follower of random walk believes it is impossible to outperform the market without assuming additional risk.

![alt tag](https://cloud.githubusercontent.com/assets/23565353/20692816/4fa00ad8-b5a8-11e6-945b-e65d92d062fc.PNG)

## Type of Options :
Call Option :  It provides the holder the right to purchase a stock at a specific price(strike price), for a certain period.
Eg :Shares of Nike are selling for $130 on July 18, 2018 (recall the stock is at $117 today, 10/28/2016), and it will cost us $12 to buy an option today. 
If on July 18, 2018, the price is $150, we would have $20-12=$8 of profit
If on July 18, 2018, the price is $125, the option has zero value
Puts are the opposite of Calls. If you buy a Put, it gives you the right to sell at a particular price.

## Project Objective
The objective of the project is not only to predict the future outcome but also to make it available to the public in order for them to understand future market. So, the first part of the project is to forecast the stock price and second part of the project is to create a application to make forecasts available to the user along with some stock markets insights 

### Code for stock price foercast 


### Application Landing Page
![alt tag](https://cloud.githubusercontent.com/assets/19517513/20689286/a379a97c-b592-11e6-8032-5d8b485082f8.png)

## Application Functionality
 Landing Page And Menu 1 In The Application

1.1 Landing page has forecasts for 10 different stocks which are manually fed into the code, you can input the stocks you want by downloading and changing the code, these forecasts gives the price difference compared to current price to the forecasted price from today to the next one year.

1.2 You can select the stock name in enter manually drop down and switch to selection tab and feed Option value, Option target and click on submit button.

1.3 the forecasts obtained will be from today to the next one year increase or decrease in the stock price( change in stock price), by default using 1 year date for forecast date, and when you give 0 in option price we will use current price as the option target. This will give increase stock price fro current price.

1.4 The price increase graph shows the change in the stock price from the option target price, this determines if it is wise to invest in the call option or not.

1.5 second density graph shows the distribution of number of times you will make profit on the forecasted date,, when you mouse iver on this plot you can also observe the ratio of profit to call option value you are investing.

1.6 The other ui element is data table consisting of the forecasted increase from the option target price from today until the given forecasted date. You can search for the particular date get the mean earnings to the option target.

## Recommendation
1.	A simple but powerful tool for evaluating the financial options before investing, we can easily find the options which are undervalued and invest into them.
2.	We can effectively manage our options investments in wide variety of sector’s and industries using this application, this will potentially reduce the risk involved.
3.	Model is updated in every instance which makes it more desirable than a model which is pre-built and implemented in real-time.
4.	Mostly a simulation of the trend, which makes the number of assumptions in the stock prices to be minimal.

