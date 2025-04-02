# AituDariga Token (TG) - ERC-20 Smart Contract
## 🔹 Overview  
AituDariga Token (TG) is an ERC-20 compliant smart contract deployed on the Ethereum blockchain.  
It provides fundamental token functionalities, including transaction tracking and metadata retrieval.  

### Token Details  
- **Name:** Tenge  
- **Symbol:** TG  
- **Total Supply:** 2000 TG  
- **Standard:** ERC-20  

![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/ae0f529c-6153-4f83-8378-7366a44e5d93)<br>
### 🔹 Smart Contract Initialization  
The token contract is initialized with a **total supply of 2000 TG**, minted to the contract deployer.  
#### ✅ Constructor Implementation:  
```solidity
constructor() ERC20("Tenge", "TG") {
    _mint(msg.sender, 2000);
}


Function getLatestTransactionTimestamp  
### 🕒 getLatestTransactionTimestamp()  
Returns the **block timestamp** of the latest transaction in a human-readable format (HH:MM:SS).  

#### ✅ Implementation:
```solidity
function getLatestTransactionTimestamp() public view returns (string memory) {
    return block.timestamp; // Convert to readable format
}
![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/9bf00126-05be-4b11-946d-930bb2b28dfe)  
  In the logs, you can observe the human-readable format time (hours: minute: seconds). This function enhances the usability of the blockchain data by providing a more understandable representation of transaction times.
![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/1971ea5e-c7ef-4ce0-b2f2-d1b4ffe37a1c)

Function getAddressTransactionSender
Implement a function to retrieve the address of the transaction sender.
![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/669b1d4b-a441-463e-a4ee-f0340ac309a7)  
In the logs, you'll find the sender's address value under the key "addr." This function offers transparency by exposing the address of the entity initiating the transaction.  
![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/1e73012d-a7fd-4ea5-8f84-14928ab5930a)

Function getTransactionReceiver, 
Develop a function to retrieve the address of the transaction receiver.
![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/e2b0569f-c75f-4ccf-a896-e712942d4ecb)

In the logs, the receiver's address value is logged under the key "addr." This function complements the previous one, providing insights into the recipient's address for each transaction.

![image](https://github.com/darigasekerbek/Blockhain-1/assets/129574982/efb0d4e1-df1e-4850-b2fd-03e9ba922fac)


```markdown
## 📜 Conclusion  
This documentation provides an overview of the AituDariga (TG) ERC-20 smart contract, including **core functions for transaction tracking** and **user-friendly metadata retrieval**.  

For further improvements or contributions, feel free to submit a **pull request** or open an **issue** on GitHub. 🚀  

## 📧 Contact  
- **Author:** Dariga Sekerbek  
- **GitHub:** [@darigasekerbek](https://github.com/darigasekerbek)  
- **Email:** darigasekerbek2@gmail.com


