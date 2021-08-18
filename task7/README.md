# TASK7
## Folder Management Dapp

- This Dapp is created using Nervos Godwoken blockchain testnet. You can connect via metamask 
- You can create new folders and see old folders that were created

### Screenshot-Video

- Please take look at <a href="https://youtu.be/6TU1IzW70uY">PROJECT VIDEO</a> to see how it works.

<img src=""/>
<hr/>
<img src=""/>

### Project Source Code

- <a href="">GITHUB REPOSITORY</a>

<hr/>

### Transaction hash, deployed contract address and ABI

Transaction hash: 0x8665effe36a772d13594650951c377fa20688ce091bbc146b9a4ba198e788d26

Deployed Contract Address: 0x12208DbFFd6a07F76d4023a8ffDA28353cda4631

ABI:

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "folders",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "folderId",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_name",
          "type": "string"
        }
      ],
      "name": "makeNewFolder",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getTotalFolder",
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
  ]
```



