# Trading-Machine-Blueprint
Trading Machine

A trading machine using a pre-existing brokerage API to automate the trading process.

# GOALS:



1. Fully auomate the trading process
2. Make a scalable profit
3. Accept different trading techniques
4. Mitigate trading risk
5. Scale automated trading process


## ELEMENTS:



### PORTFOLIO


A. Manages positions

B. Reports on stock value, boolean metric for profitability, etc




### INDICATORS


A. Receive, set, and compare trade indicators

B. Track Movement

C. Use various trading technique to assess risk

D.Collect indicateor information cohesively

E. Create and respond to Buy & Sell indicator signals**

F. Use statistical formulas

G. Use stock technique to mitigate risk


### TRADE


A. Differ trade types

B. Process trade instruction

C. Assign unique identification to each trade (for tracking and machine optimization)




### MACHINE (Back-end)

A. Communicates with API

B. Creates & manages sessions

C. Checks if market is open or closed

D. Conducts trades and other orders



### MACHINE (Front-end)

A. Tracks orders 

B. Adds all orders to a dataframe

C. Reports funds available

D. Fetches positions of user stocks

E. Parse positions to a dataframe

F. Return stock details on request




### OPERATIONS

A. Code orders for machine to follow

B. Analyze results of trades

C. Adjust machine hyperparameters if major loss occurs

D. Mitigate loss and maximize gain


### EXECUTION

A. Sign into brokerage API

B. Add funds to account (under $200)

C. Write a script to conduct trades

D. Document trade results

E. Prove/Disprove effective automated strategies

F. Create interface to easily conduct automated trades

G. (Optional) Create & Deploy UI for more appealing use.

### THREATS

A. Overfitting

B. Well-trained model with bad long-term performance where stakes are significantly higher

C. False positives

D. Repeatability
