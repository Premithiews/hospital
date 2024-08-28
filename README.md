# hospital

# HospitalRecords Smart Contract 

![Screenshot 2024-08-28 092814](https://github.com/user-attachments/assets/07e86a54-20da-4e23-af95-8ff3e06b6ce1)


## Vision

The **HospitalRecords** smart contract aims to modernize and secure the management of healthcare records. By leveraging blockchain technology, the system ensures that sensitive patient and doctor information is stored securely, transparently, and immutably. This contract allows for decentralized access to medical records, enabling better coordination among healthcare providers while maintaining the privacy and integrity of patient data.

## Flowchart

```plaintext
+-----------------+
| Add Doctor/     |
| Add Patient     |
+--------+--------+
         |
         v
+-----------------+
| Data Stored in  |
| Mappings        |
+--------+--------+
         |
         v
+-----------------+           +-------------------+
| Get Doctor Info | <-------  | Update Patient     |
+-----------------+           | Medical History    |
         |                    +-------------------+
         v
+-----------------+
| Get Patient Info|
+-----------------+
```

## Contract Address

*Deployed on Ethereum Network:*  
`0x2d2dca0b3fa01c1a22070e177fcdd7373dbffdc0f56234ba5c10b7bfc6659041`  
![Screenshot (212)](https://github.com/user-attachments/assets/0cd905f9-9acc-4ebe-96c1-1a9cf3965dcd)


*Network:* `<Network Name Here>` (e.g., Rinkeby, Mainnet, etc.)

## Features

1. **Doctor Management**:  
   - Add new doctors with details like name, specialization, and address.
   - Retrieve doctor details using their unique ID.

2. **Patient Management**:  
   - Add new patients with details like name, age, medical history, and address.
   - Retrieve patient details using their unique ID.
   - Update a patient’s medical history.

## Future Scope

- **Role-Based Access Control**: Implement role-based permissions to restrict who can add or modify records (e.g., only authorized healthcare providers).
- **Integration with Decentralized Identity**: Link records to decentralized identity systems to provide patients with full control over their data.
- **Interoperability with Other Healthcare Systems**: Integrate the contract with other healthcare platforms to create a comprehensive and unified patient care ecosystem.
- **Patient Consent Management**: Implement consent mechanisms to allow patients to control who can view or modify their medical records.

## Contact Information

For more information or to contribute to the project, please contact:

**Premithiews Barman**  
*Email*: premithiewsk@gmail.com
GitHub: [https://github.com/Premithiews]
