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
![image](https://github.com/user-attachments/assets/2ddf281e-b51b-4f8b-82e1-8c8253deae28)

  In the logs, you can observe the human-readable format time (hours: minute: seconds). This function enhances the usability of the blockchain data by providing a more understandable representation of transaction times.
![image](https://github.com/user-attachments/assets/4c297dfd-8965-475b-be53-d65de05d44ae)


Function getAddressTransactionSender
Implement a function to retrieve the address of the transaction sender.
![image](https://github.com/user-attachments/assets/c22b2be3-0057-46c0-91d8-dcdac6f73d79)

In the logs, you'll find the sender's address value under the key "addr." This function offers transparency by exposing the address of the entity initiating the transaction.  
![image](https://github.com/user-attachments/assets/6ea38f4e-7637-4059-a528-8ed00ea0b75f)


Function getTransactionReceiver, 
Develop a function to retrieve the address of the transaction receiver.
![image](https://github.com/user-attachments/assets/1a6e3d03-0a9d-4ac3-9ffc-adc50cb32e42)


In the logs, the receiver's address value is logged under the key "addr." This function complements the previous one, providing insights into the recipient's address for each transaction.

![image](https://github.com/user-attachments/assets/4819f646-a886-46f4-8868-719bd9fcc283)



```markdown
## 📜 Conclusion  
This documentation provides an overview of the AituDariga (TG) ERC-20 smart contract, including **core functions for transaction tracking** and **user-friendly metadata retrieval**.  

For further improvements or contributions, feel free to submit a **pull request** or open an **issue** on GitHub. 🚀  

## 📧 Contact  
- **Author:** Dariga Sekerbek  
- **GitHub:** [@darigasekerbek](https://github.com/darigasekerbek)  
- **Email:** darigasekerbek2@gmail.com


