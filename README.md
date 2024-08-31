# Coffee Machine

Welcome to the Coffee Machine project! This is a Python application that simulates a coffee machine where users can select and purchase different types of coffee. The machine checks if sufficient resources are available, processes payments, and serves the coffee.

## Project Overview

This project simulates a coffee machine that can make espresso, latte, and cappuccino. Users can choose their desired drink, insert coins for payment, and receive their coffee if sufficient resources and payment are provided.

## Features

- **Coffee Selection**: Choose between espresso, latte, or cappuccino.
- **Resource Check**: The machine checks if there are enough ingredients to make the selected drink.
- **Payment Processing**: Users can insert coins and the machine will calculate if the payment is sufficient.
- **Resource Management**: The machine deducts the used ingredients from the available resources.
- **Profit Tracking**: The machine keeps track of the profit earned.


## How to Use

1. **Start the Machine**: Run the application using the instructions above.
2. **Select a Drink**: Type 'espresso', 'latte', or 'cappuccino' to choose your drink.
3. **Insert Coins**: Enter the number of quarters, dimes, nickels, and pennies when prompted.
4. **Receive Coffee**: The machine will check if there are enough resources and if your payment is sufficient.
5. **Report and Turn Off**: Type 'report' to view the current resources and profit, or 'off' to turn off the machine.

## Code Description

- **`is_resource_sufficient(order_ingredients)`**: Checks if the machine has enough resources to make the selected drink.
- **`process_coins()`**: Calculates the total amount of money inserted by the user.
- **`is_transaction_successful(money_received, drink_cost)`**: Determines if the payment is sufficient and processes the transaction.
- **`make_coffee(drink_name, order_ingredients)`**: Deducts the ingredients used from the available resources and serves the coffee.

