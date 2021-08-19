# TASK11
## Use A Tron Wallet To Execute A Smart Contract Call

### 1- Screenshot of the accounts you created

<img src="https://github.com/tayfun-yuksel/nervos-gitcoin-hackhathon/blob/master/task11/addresses.jpg"/>


### 2- Link to the Layer 1 address you funded

https://explorer.nervos.org/aggron/address/ckt1qyqg5ppxzjl2mk5sldgnuqv9e8nzufdld4zsp98wg9

### 3- Screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/tayfun-yuksel/nervos-gitcoin-hackhathon/blob/master/task11/deposit.png"/>

### 4- Screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<small>Note: Smart contract makeFolder function called. Before that totalFolderSize(Read call result) was 6. After write call, it became 7.</small>

<img src="https://github.com/tayfun-yuksel/nervos-gitcoin-hackhathon/blob/master/task11/contract.png"/>

### 5- The transaction hash of the "Contract call" from the console output


0x2297b660d078225c4efd0e1debf4acd2c83adef54dcf399a9b04f67ecc9c42a5


### 6- The contract address that you called


0x12208DbFFd6a07F76d4023a8ffDA28353cda4631


### 7- The ABI for contract you made a call on

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

### 8- Your Tron address

TVxZxPvHuvY8bJQCwEcJUfLXbbVPK7L7NL
