# Machine-Learning-Training-Bot
This code creates signals to assist with when to buy and sell a stock.  Parameters can easily be adjusted to create an accurate model of expected returns.  A logistic regression model is also created for comparison purposes.

## Technologies
In order to run this code you will need to install Pandas, NumPy, hvPlot, Matplotlib, and scikit-learn.

## Installation Guide
### Importing Libraries and Dependencies
<img width="371" alt="Screen Shot 2022-01-03 at 4 41 55 PM" src="https://user-images.githubusercontent.com/89439442/147995110-082efca8-9f05-42eb-9a36-ef54eaa23ad1.png">

## Usage
### Cumulative Product of Actual Returns vs. Strategy Returns (Baseline)
<img width="348" alt="Screen Shot 2022-01-03 at 3 21 06 PM" src="https://user-images.githubusercontent.com/89439442/147990772-0e614736-9318-4acc-852e-4e59423416ad.png">

### Increased Training Window from 3 Months to 5 Months
<img width="351" alt="Screen Shot 2022-01-03 at 5 00 07 PM" src="https://user-images.githubusercontent.com/89439442/147996101-6bf6c658-4f47-4495-9062-dc9fc62bc49b.png">
What impact resulted from increasing or decreasing the training window?
After adding 2 months worth of data to the original training window of 3 months, it is apparent that mid-way through 2018 the plots differ the most.  The Strategy Returns went a little over a year of lower return than that of the baseline plot.

### Increased Long Window from 100 to 150 (Most Accurate)
<img width="351" alt="Screen Shot 2022-01-03 at 5 31 07 PM" src="https://user-images.githubusercontent.com/89439442/147997915-e35751b4-5a8c-4e33-b71e-90b6a9b25cc7.png">
What impact resulted from increasing or decreasing either or both of the SMA windows?
After increasing the long window by 50 the new plot shows that it follows closely to that of the actual returns.

The baseline trading algorithm has the greatest return out of the three created and it out performs the actual returns.

### Linear Regression Model
<img width="349" alt="Screen Shot 2022-01-09 at 10 11 24 PM" src="https://user-images.githubusercontent.com/89439442/148724562-f3bc321e-1da0-45b1-8d9c-ea4d1cdc976f.png">
Did this new model perform better or worse than the provided baseline model?
This new model performed better up until 2021.

Did this new model perform better or worse than your tuned trading algorithm?
This new model performed better than both of the tuned trading algorithms.

## Contributors
Tristen Pulido
