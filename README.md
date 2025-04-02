# AituDariga Token (TG) - ERC-20 Smart Contract

## 🔹 Overview  
AituDariga Token (TG) is an ERC-20 compliant smart contract deployed on the Ethereum blockchain.  
It provides fundamental token functionalities, including transaction tracking and metadata retrieval.  

### Token Details  
- **Name:** Tenge  
- **Symbol:** TG  
- **Total Supply:** 2000 TG  
- **Standard:** ERC-20  

### 🔹 Smart Contract Initialization  
The token contract is initialized with a **total supply of 2000 TG**, minted to the contract deployer.  

#### ✅ Constructor Implementation:  
```solidity
constructor() ERC20("Tenge", "TG") {
    _mint(msg.sender, 2000);
}
```

---

### 🕒 getLatestTransactionTimestamp()  
Returns the **block timestamp** of the latest transaction in a human-readable format (HH:MM:SS).  

#### ✅ Implementation:  
```solidity
function getLatestTransactionTimestamp() public view returns (string memory) {
    return block.timestamp; // Convert to readable format
}
```

![Transaction Timestamp](https://raw.githubusercontent.com/darigasekerbek/Blockhain-1/main/assets/transaction-timestamp.png)  

In the logs, you can observe the human-readable format time (hours: minutes: seconds). This function enhances the usability of the blockchain data by providing a more understandable representation of transaction times.  

![Timestamp Logs](https://raw.githubusercontent.com/darigasekerbek/Blockhain-1/main/assets/timestamp-logs.png)  

---

### 📍 getAddressTransactionSender()  
Retrieves the address of the transaction sender.  

#### ✅ Implementation:  
```solidity
function getAddressTransactionSender() public view returns (address) {
    return msg.sender;
}
```

![Transaction Sender](https://raw.githubusercontent.com/darigasekerbek/Blockhain-1/main/assets/transaction-sender.png)  

In the logs, you'll find the sender's address value under the key **"addr"**. This function offers transparency by exposing the address of the entity initiating the transaction.  

![Sender Logs](https://raw.githubusercontent.com/darigasekerbek/Blockhain-1/main/assets/sender-logs.png)  

---

### 📩 getTransactionReceiver()  
Retrieves the address of the transaction receiver.  

#### ✅ Implementation:  
```solidity
function getTransactionReceiver(address recipient) public pure returns (address) {
    return recipient;
}
```

![Transaction Receiver](https://raw.githubusercontent.com/darigasekerbek/Blockhain-1/main/assets/transaction-receiver.png)  

In the logs, the receiver's address value is logged under the key **"addr"**. This function complements the previous one, providing insights into the recipient's address for each transaction.  

![Receiver Logs](https://raw.githubusercontent.com/darigasekerbek/Blockhain-1/main/assets/receiver-logs.png)  

---

## 📜 Conclusion  
This documentation provides an overview of the AituDariga (TG) ERC-20 smart contract, including **core functions for transaction tracking** and **user-friendly metadata retrieval**.  

For further improvements or contributions, feel free to submit a **pull request** or open an **issue** on GitHub. 🚀  

## 📧 Contact  
- **Author:** Dariga Sekerbek  
- **GitHub:** [@darigasekerbek](https://github.com/darigasekerbek)  
- **Email:** darigasekerbek2@gmail.com  
