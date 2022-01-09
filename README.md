# AssociateProfitSplitter 

The motivation for this contract is to distribute salary to equal recipients, assuming each has an address for HR (sender) to pay into. Illustrating the functionality of the contract as follows:

The following depicts a solidity contract deployed with three different address (recipients) from addresses created out of Ganache,

- address index 0 is HR (starting balance of 96.99ETH)
- address index 3, index 4, index 5 are the recipients (balance all at 101ETH equally)
<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/GanacheOutput.PNG">
</p>

<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/remixDeploy.PNG">
</p>



Evidence of the deployment of the contract successfully:

<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/remixOutputTxn.PNG">
</p>


Moving 15ETH from HR to recipients:

<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/remixOutputTxn2.PNG">
</p>

Balance shown in Ganache, all 3 recipients received a equal distribution of 5 ETH:

<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/GanacheOutputTxn2.PNG">
</p>


Moving 10ETH from HR to recipients:

<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/remixOutputTxn3.PNG">
</p>


Balance shown in Ganache, all 3 recipients received a equal distribution of 3.33 ETH:

<p align="center">
  <img width="460" height="300" src="https://github.com/jayxcao/week20-homework/blob/main/Images/GanacheOutputTxn3.PNG">
</p>

Please feel free to use the local testnet to interact with the contract at HTTP://127.0.0.1:8545 with NETWORK ID as 5777.