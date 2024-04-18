# :hot_pepper: Black Pepper Team

This is an organization containing source files for our project. 

This project introduces a novel way to manage your account through biometrics. 
Based on _Iden3_ technology and advanced _Deep Learning_ algorithms, we accomplished to create unique identities based on three types of biometrics: 
Face, Voice, and Passport Data, although the system is easily extended to more types of biometrical data. 
Additionally, we extend the protocol to include the functionality of transferring funds solely based on the person's photo 
as long as he is registered in the protocol.

<p align="center">
  <img width="317" alt="Mobile App Screenshot" src="https://github.com/Black-Pepper-Team/.github/assets/29094239/245d7335-6ee7-4d1e-adee-97e4e3268c75">
</p>

# Acknowledgements

The Smart-Contracts were deployed on [Q Testnet](https://q.org/). The addresses are specified in the table below:

| Contract Name | Address | Description |
| --- | --- | --- |
| **Account Implementation** | [`0x883A3f5Ac2b94bE3026ddDFC6Db53A900Aad510D`](https://explorer.qtestnet.org/address/0x883A3f5Ac2b94bE3026ddDFC6Db53A900Aad510D) | Contract supporting operations like setting a threshold for trusted issuers, transferring assets, and making arbitrary calls. |
| **Account Factory** | [`0xdf8D167190287B9B97749360093E879539EA3429`](https://explorer.qtestnet.org/address/0xdf8D167190287B9B97749360093E879539EA3429) | Facilitates the creation of `Account` contracts. |
| **Bio Registry** | [`0xdecBc08607b58e44C5b3133435aF8dDc16224dC1`](https://explorer.qtestnet.org/address/0xdecBc08607b58e44C5b3133435aF8dDc16224dC1) | Stores and manages users' biometric data. |

For more details about the contract functionality, see [`eface-contracts`](https://github.com/Black-Pepper-Team/eface-contracts) repository
