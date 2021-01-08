# PupperCoin
Solidity file for PupperCoin Crowdsale


This is a contract written in Solidity for Ethereum. It is designed to help fund development.

## I. Dependencies
The use of this contract requires the following:
Ganache

Metamask

remix.ethereum.org

MyCrypto

## II. Operation

> Step One - Change the testing timeframe in the solidity file from now+24 weeks to now+5 minutes so your crowdfunding is testable.

![Change Time](Images/TestingTimeframe.png)

> Step Two - Compile the contract and deploy using the PupperCoinSaleDeployer. Enter the name Symbol, wallet and goal information. *Note I used 10 coins as the goal to test the contract.*

![Deploy](Images/Deploy.png)

> Step Three - Confirm Deployment in MetaMask.
![Deploy](Images/MetaDeploy.png)

> Step Four - Locate the Token and Token Sale Addresses.
![Deposit](Images/ContractAddress.png)

> Step Five - Using the token_sale_address, deploy the PupperCoin Sale entering the address in the "At Address" field.

![Sale](Images/SaleAddress.png)

> Step Six - Using the token_address, deploy Puppercoin entering the address in the "At Address" field.

> Step Seven - Enter the number of Ether you want to use to purchase tokens and enter the address next to "buy tokens" in PupperCoin Sale.

![Amount](Images/PC_Sale.png)

    > You will get a MetaMask confirmation when you enter the amount.

>Step Eight - Use the Sale Features to determine how the crowdsale is going! You can see if the goal has been reached, if the sale is open, finalized, etc.
![SaleFeatures](Images/Sale_Details.png)

Use the PupperCoin features to use the minter or determine balances in individual accounts.

![PupperCoinDetails](Images/PupperCoin_Details.png)