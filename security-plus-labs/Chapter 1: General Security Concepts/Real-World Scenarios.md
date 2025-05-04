# Practicing Cybersecurity Principles in Real-World Scenarios

## **Confidentiality - Encryption**
- **Hands-On Labs:** Use tools like OpenSSL to encrypt and decrypt data using AES or RSA.
- **Email Security:** Practice encrypting emails with PGP/GPG.
- **VPN Configuration:** Set up a VPN to understand encryption in transit.

## **Access Controls - RBAC, DAC**
- **IAM in Cloud:** Implement RBAC in AWS, Azure, or GCP, assigning roles to restrict access.
- **Windows/Linux Permissions:** Configure file and directory permissions using `chmod`, `chown`, and NTFS ACLs.
- **SIEM Role-Based Alerts:** Set up role-based access control in Splunk or other security tools.

## **Integrity - Hashing**
- **File Integrity Monitoring:** Use Tripwire or OSSEC to detect unauthorized file changes.
- - **Data Validation:** Hash files and compare hashes before and after transfer (`shasum` or `certutil` in Windows).
- **Password Security:** Implement password hashing in a web app using bcrypt or PBKDF2.

## **Digital Signatures**
- **Signing Documents:** Use tools like OpenSSL to create and verify digital signatures.
- **Code Signing:** Sign software releases to ensure authenticity.
- **TLS Certificates:** Investigate certificate validation using `openssl s_client -connect`.

## **Availability - Redundancy**
- **RAID Setup:** Configure RAID levels on a test server to observe redundancy in action.
- **Backup Strategies:** Automate scheduled backups using `rsync` for Linux or Veeam for Windows.
- **Load Balancing:** Experiment with cloud services like AWS ALB or NGINX to distribute traffic.

## **Disaster Recovery Plans**
- **Tabletop Exercises:** Simulate security incidents and develop response strategies.
- **Failover Systems:** Test cloud failover by deploying replicated instances in multiple regions.
- **BCP & DR Testing:** Create and implement recovery procedures for business continuity.
