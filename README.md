# Blockhain-1. AituDariga Token Smart Contract

Summary
The ERC-20-based AituDariga Token (symbol: TG) is implemented by this Solidity smart contract.                                                                                                                       
The "Tenge" token has a total quantity of 2000 when it is first produced. Retrieving transaction timestamps and details about the sender and recipient of the transaction are also included in the contract.         

Functions
getLatestTransactionTimestamp()
Returns the current timestamp and emits the Timestamp event with the current hour, minute, and second.

Returns:
uint256: Current timestamp.
getAddressTransactionSender()
Returns the address of the transaction sender and emits the Sender event.

Returns:
address: Address of the transaction sender.
getTransactionReceiver()
Returns the address of the transaction receiver and emits the Receiver event.

Returns:
address: Address of the transaction receiver.

Details
Name: Tenge
Symbol: TG
Total Supply: 2000
Standard: ERC-20
Deployment
This contract can be deployed on the Ethereum blockchain using Remix or any other Solidity development environment.

License
This smart contract is licensed under GNU General Public License v3.0

Thank you!
