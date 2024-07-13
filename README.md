Name: AKSHAT ADITYA

Company: CODTECH IT SOLUTIONS

Domain: BLOCKCHAIN TECHNOLOGY

Intern ID:CT6WDS286

Duration:10 June to 22 July

Overview of the project:-

Project:TOKEN CREATION ON ETHEREUM

Objective:-
Ethereum network’s launch in 2015 created a lot of buzz in the developer community and sprouted a lot of tokens on the network. Initially, there weren’t any templates or guidelines for token development. This resulted in a variety of tokens quite different from each other. To bring this diversity to order, the community came up with an ERC-20 standard to make all tokens more or less uniform.

What You Will Do:-

Learn about ERC-20 tokens and their use cases
Create and deploy an ERC-20 token using Remix.IDE


What You Will Need:-

A web3 wallet (e.g., MetaMask, Coinbase Wallet, Phantom, or a WalletConnect-compatible wallet)
Test ETH (You can get some at the Multi-Chain QuickNode Faucet)
A modern web browser (e.g., Chrome)



KEY POINTS ABOUT ERC-20 TOKEN:-

Standardized Functions: ERC-20 tokens follow a specific set of standards, which means they have a common list of rules and functions. This includes how the tokens can be transferred, how transactions are approved, how users can access data about a token, and the total supply of tokens.

Smart Contracts and DeFi: The use of smart contracts in ERC-20 tokens enables the automation and enforcement of complex financial operations. This is crucial for DeFi platforms, where these tokens can represent various financial instruments, like loans or stakes in a liquidity pool.

Interoperability: Since ERC-20 tokens follow the same standard, they are easily interchangeable and can work seamlessly with other ERC-20-compliant tokens and applications on the Ethereum network. This standardization simplifies the process of creating new tokens and makes them instantly compatible with existing wallets, exchanges, and other services.

Use Cases: ERC-20 tokens can represent a wide range of assets or utilities. For example, ERC-20 tokens can serve various roles, such as collateral for loans, interest-bearing assets in yield farming, and governance tokens granting voting rights in decentralized autonomous organizations (DAOs).

Transferability and Exchange: These tokens can be transferred from one account to another as payment, similar to cryptocurrencies like Bitcoin, and can be traded on various cryptocurrency exchanges.

ERC-20 is a standard or guideline for creating new tokens. The standard defines six mandatory functions that a smart contract should implement and three optional ones.

The mandatory functions are listed below with explanations.


totalSupply: A method that defines the total supply of your tokens; when this limit is reached, the smart contract will refuse to create new tokens.
balanceOf: A method that returns the number of tokens a wallet address has.
transfer: A method that takes a certain amount of tokens from the total supply and gives it to a user.
transferFrom: Another type of transfer method that is used to transfer tokens between users.
approve: This method verifies whether a smart contract is allowed to allocate a certain amount of tokens to a user, considering the total supply.
allowance: This method is exactly the same as the approved method except that it checks if one user has enough balance to send a certain amount of tokens to another.
Besides the mandatory functions listed below, functions are optional, but they improve the token's usability.


name: A method that returns the name of the token.
symbol: A method that returns the symbol of the token.
decimals: A method that returns the number of decimals the token uses. It is used to define the smallest unit of the token. For example, if an ERC-20 token has a decimals value of 6, this means that the token can be divided up to six decimal places.
If you know something about object-oriented programming, you can compare ERC-20 to an Interface. If you want your token to be an ERC-20 token, you have to implement the ERC-20 interface, and that forces you to implement these 6 methods.
