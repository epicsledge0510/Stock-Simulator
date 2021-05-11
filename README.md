# Stock-Simulator
A small game to simulate buying and selling shares of a stock

The primary focus of this project is to show people how buying stocks can be and give the user a hands on experience to learn about this process.

The majority of the functions is held in main.js.

Primary functions are those tied to addDataPoint, updateDataPoint, buyButton, sellButton, and jumpButton.
Pressing the addDataPoint button pushes the stock price forward one point and allows you to hold your stocks in the hope for a better price.
Pressing the updateDataPoint button updates the current point on the graph without pushing the chart forward any points, this can be used to force a simulation of a sudden drop or spike if that is desired.
Pressing the buyButton button buys one share of the stock as well as pushes the price forward one point. 
Buying the stock will allow the user to see the price of that share as well as any previous shares that they own. This also subtracts the price from the players money count and adds one share to their count of owned shares
Pressing the sellButton button sells one share of the stock as well as pushes the price forward one point.
Selling the stock will cause the display to show the user to see the profit that they made off of that sale as well as the total amount of profit that has been made while removing this share from the list of owned shares. This also adds whatever money was made to the players wallet and subtracts their share count.
Pressing the jumpButton button simulates the same thing as the buyButton, except this runs the same function 30 times to simulate a fowards jump of a month.
