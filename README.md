# Module 18: Pychain Ledger

This project implements a blockchain ledger that tracks currency transactions between a sender and receiver. The ledger also verifies the integrity of the data.

## Adding a Block
The Streamlit application allows the you to easily enter a transaction into the blockchain by providing a sender, receiver and currency amount. You can also change the block diffculty using the slider in the sidebar. Simply enter the data as shown in the pictures below, and click the "Add Block" button.    
![Screenshot1](https://github.com/rafi-n/module18_pychain_ledger/blob/main/Images/Streamlit_app_screenshot2.png)

## Reviewing Blocks
On the sidebar is the Block Inspector, where you can get detailed information about any transaction selected from the drop-down menu.
![Screenshot2](https://github.com/rafi-n/module18_pychain_ledger/blob/main/Images/Streamlit_app_screenshot1.png)

## Validating the Chain
Click the "Validate Chain" button to check the validity of the blockchain. If your blockchain is valid, it will reply with "True", otherwise "False".