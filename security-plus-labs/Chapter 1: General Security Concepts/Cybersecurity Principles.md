# Cybersecurity Principles

## **Confidentiality - Encryption (e.g., AES, RSA)**
Confidentiality ensures that sensitive information is protected from unauthorized access. Encryption plays a key role by converting data into a coded format that only authorized parties can decrypt using cryptographic keys.

- **AES (Advanced Encryption Standard):** A symmetric encryption algorithm widely used for securing data at rest and in transit. AES supports key sizes of 128, 192, and 256 bits, offering strong security.
- **RSA (Rivest-Shamir-Adleman):** An asymmetric encryption algorithm that uses a pair of public and private keys for secure data exchange. It’s commonly used for secure email communication, digital signatures, and SSL/TLS encryption.

## **Access Controls - RBAC, DAC**
Access control mechanisms determine who can access specific resources and what actions they can perform.

- **RBAC (Role-Based Access Control):** Permissions are assigned based on roles rather than individuals. For example, a database administrator role might have full access, while a regular user role might have read-only access.
- **DAC (Discretionary Access Control):** The resource owner decides who has access and at what level. It’s more flexible but can be riskier if not managed properly.

## **Integrity - Hashing (e.g., SHA-256, MD5)**
Integrity ensures that data remains unaltered during transmission or storage.

- **SHA-256 (Secure Hash Algorithm 256-bit):** A strong cryptographic hashing function used in blockchain and security applications. It produces a unique 256-bit hash for any given input.
- **MD5 (Message-Digest Algorithm 5):** An older hashing algorithm that produces a 128-bit hash. Though widely used historically, it's now considered insecure due to vulnerabilities in collision attacks.

## **Digital Signatures**
Digital signatures provide authentication, integrity, and non-repudiation for digital documents and messages.

- They use asymmetric cryptography, where a sender signs a document with their private key, and the recipient verifies it using the sender’s public key.
- **Common algorithms:** RSA, ECDSA (Elliptic Curve Digital Signature Algorithm).
- Widely used in electronic contracts, email verification, and secure software distribution.

## **Availability - Redundancy (e.g., RAID, backups)**
Availability ensures that systems and data remain accessible despite failures.

- **RAID (Redundant Array of Independent Disks):** A technique that uses multiple hard drives to enhance performance and fault tolerance.
  - **RAID 1 (mirroring):** Duplicates data across disks for redundancy.
  - **RAID 5 (striping with parity):** Provides fault tolerance while balancing performance.
- **Backups:** Regular copies of data stored in different locations (on-site, off-site, cloud) to protect against system failures or cyberattacks.

## **Disaster Recovery Plans (DRP)**
A **Disaster Recovery Plan** outlines strategies for restoring operations after cyberattacks, natural disasters, or system failures.

- **Key elements:**
  - **Risk Assessment:** Identifies potential threats to business continuity.
  - **Recovery Time Objective (RTO):** Maximum acceptable downtime before recovery.
  - **Recovery Point Objective (RPO):** Acceptable data loss threshold.
  - **Backup Strategy:** Ensures critical data can be restored quickly.
  - **Failover Systems:** Includes secondary systems that take over when primary systems fail.
