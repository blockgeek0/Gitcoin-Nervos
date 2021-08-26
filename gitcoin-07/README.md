## Gitcoin: 7) Port An Existing Ethereum DApp To Polyjuice

### 1- Screenshot&Video

<a href="https://youtu.be/HBqwfPo-KdY"> WATCH VIDEO </a>
<img src="https://github.com/blockgeek0/Gitcoin-Nervos/blob/master/gitcoin-07/1.png"/>
<br/>
<hr/>
<br/>
<img src="https://github.com/blockgeek0/Gitcoin-Nervos/blob/master/gitcoin-07/2.png"/>


### 2- Project Repo
<a href="https://github.com/blockgeek0/Nervos-Dapp-Art"> Project Github Link </a>

### 3- Contract Details

Transaction hash:

```bash
0xa0fbefee8fa45e85476deda86926a8b2edb8834e4563681f6c5eb3d532b801f9
```

Deployed Contract Address:

```bash
0x21949551655Ac8D4e166D05D4bf971495988824F
```

ABI of the contract:

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
