**Room:** Introduction to CryptOps



**Theory:**

* Key Management Lifecycle = critical stages in effective management of cryptographic keys

  * Generation -> Distribution -> Storage -> Usage -> Backup \& Recovery -> Rotation -> Revocation -> Destruction
* *Hardware Security Module* = physical device offering robust protection mechanisms
* *Cloud-Based Key Management Service* = AWS KMS / Azure KMS / Google Cloud KMS



Key Gen BPs:

1. strong random number/character generators
2. adhere to industry standards and algorithms
3. secure the key gen environment
4. validate key generation parameters



Key Distribution BPs:

1. secure transmission channels (TLS)
2. public key infrastructure (PKI)
3. trusted delivery methods (signature)
4. robust auth mechanisms (identity)
5. secure key storage solutions



Access Control Mechanisms:

* *RBAC* = Role-Based Access Control
* *ABAC* = Attribute-Based Access Control

Authentication:

* *MFA* = Multi-Factor Authentication
* *CRL* = Certificate Revocation List
* *OCSP* = Online Certificate Status Protocol



* *Bastion hosts* = cloud used for secure key generation
* *Secure storage solutions* = secure vaults environment for key generation
* *Symmetric encryption* = single shared key for encryption/decryption
* *Asymmetric encryption* = public + private keys for separate encryption/decryption
* *KDS* = Key Distribution Center (Kerberos)
* *PSK* = Pre-Shared Key (VPNs, wireless networks)
* *Cryptoperiod* = lifespan of a key before rotation



**Vault Configuration:**



1. Integration with the CI/CD pipeline

nmap -sV -p- <target-ip>



port 8080 = Jenkinks

ports 80/443/3000 = Git

