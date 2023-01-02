#### What exactly is a Smart Contract

A smart contract is like a computer program that can automatically carry out certain actions when certain conditions are met.

For example, let's say you want to play a game with your friend where you each have to put in a dollar.

If you win, you get to keep the money. If you lose, your friend gets to keep the money.

A smart contract can help you play this game fairly, without having to trust each other.

You can both put your dollars into the smart contract, and it will automatically give the money to the winner when the game is over.

Smart contracts can be used in a variety of contexts, including financial transactions, supply chain management, and even voting systems.

They are often implemented using blockchain technology, which enables the creation of a secure and transparent record of transactions.

Solidity programming language is commonly used for writing smart contracts on the Ethereum blockchain.

Here’s the very basic smart contract.

![](https://pbs.twimg.com/media/FkpgibVUoAAxryw?format=jpg&name=large)

This simple contract has a balance that can be increased by calling the `addFunds` function and decreased by calling the `withdrawFunds` function.

The `withdrawFunds` function includes a `require` statement that checks if the requested withdrawal amount is less than or equal to the current balance, and if not, it throws an error message.

This is just a very basic example of what a smart contract might look like.

Writing a Smart Contract is not a rocket science. It’s just the game of building logics with the code.

In a real-world contract, you would likely include additional logic and functionality to meet the needs of the specific application.
