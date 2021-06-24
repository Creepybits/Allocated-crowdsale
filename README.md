# Allocated-crowdsale
Post deployment crowdsale

How to sell tokens from an aldready existing contract at a new crowdsale contract.

<h3>The contracts used are taken from OpenZeppelin</h3>

<h4>Crowdsale contract: @openzeppelin-contracts/v2.5.0/contracts/crowdsale/Crowdsale.sol</h4>

<h4>Token contract: @openzeppelin-contracts/v4.1.0/contracts/token/ERC20/ERC20.sol</h4>

Both contracts were compiled in Remix and flattened with Remix built-in flattener. 

*Note: the remix flattener doesn't always put the different parts of the contract in the right order when flattening
so you might have to manually move them around until they are positioned correctly*

Deploy your crowdsale contract at the contract address of the token you wish to sell.
![image](https://user-images.githubusercontent.com/60452756/123291580-84daee00-d512-11eb-806c-ebf41ed2a35c.png)

I didn't manage to get the crowdsale contract verified. 

However, if you copy the ABI then you can interact with the contract at https://app.mycrypto.com/interact-with-contracts

Just put the address in and paste the ABI, and save the contract in case you need to interact with it at a later date.

![image](https://user-images.githubusercontent.com/60452756/123292236-24987c00-d513-11eb-8da4-9809d41d1bbf.png)


Now you should have the tokens either in your wallet or at the contract address which you have access to. All that is left is to 
transfer the amount of tokens you wish to sell to the newly deployed crowdsale contract.

Token contract at Testnet: https://testnet.bscscan.com/address/0x59a4587b57311b3aca8ce6f1645bbf46b9bf06d7

Crowdsale contract at testnet: https://testnet.bscscan.com/address/0x72a35fb82406cb48684680e7ab7bbaeaa69f9e10

