# Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![alt text](1.png)

2. The transaction hash from the console output (in text format).

   ```
   0x52c3b930d3645a57f2ef82079a29512fed66f57968ab7d1d17526eacfdbe1923
   ```

3. The contract address that you called (in text format).

   ```
   0x6B33330448bF1D39f800fDD5E6c317c3bD93f1c7
   ```

4. The ABI for contract you made a call on (in text format)

```
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
