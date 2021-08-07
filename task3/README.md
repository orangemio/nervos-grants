## Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

#### 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![image.png](https://i.loli.net/2021/08/07/cK6PTr3feR1DVi2.png)
#### 2. The transaction hash from the console output (in text format).
0xe7e2084c56efc0162a463c7da9f2ba19aa214159fc12cd4cab3209b1950d99f2
#### 3. The contract address that you called (in text format).
0xA388961e6eF11E16D22b8b11ADb3250a8d27B760
#### 4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
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
