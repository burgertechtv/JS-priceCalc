# JS-priceCalc
This app is a simple js app that checks to see if you have available funds and purchases a phone and tells you if you can afford the item. 

This js app contains 4 constants: 
- const SPENDING_THRESHOLD
- const TAX_RATE
- const PHONE_PRICE
- const ACCESSORY_PRICE

It also contains two functions, both functions take one attribute
- calculateTax
- formatAmount 

The app checks to see if you have enough money to buy a phone and if you do then it buys the phone and based on how much money you have left over it will continue to buy accessories until you cannot afford any more 
