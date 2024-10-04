# Option Pricing Model with Python (Binomial Tree and Black - Scholes)
**1. Introduction**  
In this project, I focused on option pricing using two models: the Binomial Tree and the Black-Scholes model. The underlying asset chosen for this analysis is AMD stock. I conducted a comparative study to demonstrate that the option price calculated using the Binomial Tree model approaches the Black-Scholes price as the number of steps 
𝑁
N increases towards infinity. This exploration provides insights into the effectiveness of the Binomial Tree model in approximating the values predicted by the Black-Scholes model for option pricing.  

**2. Implementation**  
First, I downloaded the AMD stock data from yfinance library, with start date = '2025 - 01 - 01'. Below is the AMD stock values over time: 
![Alt text](https://drive.google.com/uc?export=view&id=1h8XbS85apdjRCSSSpfVBovWVFPDEnLQ-)  

Then I'm going to calculate the daily log returns on this stock. However, we would like to have the annual log returns so we just simply multiply the daily log return with 252 - which is the number of trading days in a year.




