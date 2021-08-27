### Gitcoin-11 - Use A Tron Wallet To Execute A Smart Contract Call 


### 1-) A screenshot of the accounts you created

<img src="https://github.com/blockgeek0/Gitcoin-Nervos/blob/master/gitcoin-11/accounts.png" />


### 2-) A link to the Layer 1 address you funded on the Testnet Explorer

<a href="https://explorer.nervos.org/aggron/address/ckt1qyqxk287xwghh8rdk2gwcgtentntqpcxejgslvyr90" > Explorer link </a>

### 3-) A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

- Check out the explorer link to see that transaction was confirmed. I executed command twice but both gave the same result.
<img src="https://github.com/blockgeek0/Gitcoin-Nervos/blob/master/gitcoin-11/depo.png" />

### 4-) A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/blockgeek0/Gitcoin-Nervos/blob/master/gitcoin-11/contr.png" />

### 5) The transaction hash of the "Contract call" from the console output

```bash
0x8723753d1ed33ecc5e157c3fdf6afe9600823f030f10d501a7462466919fabc4
```
### 6) The contract address that you called

```bash
0x21949551655Ac8D4e166D05D4bf971495988824F
```

### 7) The ABI for contract you made a call on

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
      "name": "arts",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "artId",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "votes",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_artId",
          "type": "uint256"
        }
      ],
      "name": "sendVote",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```

### 8) Your Tron address

```bash
TXQJSuSWDsBVwG1R3vA7K5CF4hbX6JAdph
```
