# nervosTask7

Screenshots or video of your application running on Godwoken.

![image](https://user-images.githubusercontent.com/5809685/129424128-9e537089-d956-4289-97c3-a67948b27a0b.png)

![image](https://user-images.githubusercontent.com/5809685/129424395-3c206b53-3603-4096-8a13-4314a712fb5b.png)


Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.


If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

Deployed contract address: 0xFE9E542Bd998c053c0b731Afe6F1C12eDbEfcDbA
Deploy transaction hash: 0x5b1dd2c9e21b73dc1a037085a9e2c15c695e652a718e51ad3cb8dfc666feec24

```
 "abi": [
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": true,
          "internalType": "address",
          "name": "sender",
          "type": "address"
        },
        {
          "indexed": false,
          "internalType": "string",
          "name": "message",
          "type": "string"
        }
      ],
      "name": "Message",
      "type": "event"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "newMessage",
          "type": "string"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getTotalMessage",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ],
  
```
