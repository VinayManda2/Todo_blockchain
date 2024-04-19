# Todo_blockchain

to do list using block chain

requirements :
install node and ganache metamask to connect and interact

project setup:

tuffle init - to create all the essential files

now create package.json

create a smart contract in contracts folder

to connect to block chain :
update truffle-config.js - with solidity version and development details

create migration file in migradions folder for the contract

truffle compile
truffle migrate - command to migrate
truffle migrate --reset - incase you have already pushed contract earlier

TO check the migration :
go to truffle console -
truffle console - command

> todolist = await TodoList.deployed()
> todolist - prints all details
> todolist.address
> taskCount = await todolist.taskCount()
> taskCount.toNumber()
> .exit - to exit from console
