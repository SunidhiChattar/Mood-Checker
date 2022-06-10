# Mood-Checker
A Mood checker DApp where you can set your mood and by clicking on get mood the DApp will give an alert of the mood you just set.

# How to ?
Make an HTML file having a mood setter and a getter button and an input text box which will provide a space to write something, make your DApp look appealing by adding CSS in it.
Write a Smart contract in Remix IDE, compile and deploy it with "Injected Web3" in the ENVIRONMENT, the metamask or any wallet provider will popup, by providing the password it will get connected (assuming that the browser already have a Metamask extension and the wallet have some ether in it). We are using Ropsten testnet for this project.
Our FrontEnd and BackEnd are ready, we will then connect our deployed contract with the html file. Ether.js will help us to do that.
We will connect it by providing our html file the deployed contract's address, contract's ABI, a wallet provider and the setter and getter functions.
Our DApp is ready to Go!!
