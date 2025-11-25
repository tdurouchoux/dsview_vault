---
type: Concept
---

SSH public/private keys are a pair of cryptographic keys used for secure authentication. The public key is used to encrypt data, while the private key is used to decrypt it. They provide a more secure alternative to password-based authentication and are commonly used in SSH for secure remote access to servers. The keys are generated using the ssh-keygen command, and the public key is typically copied to the server's authorized_keys file. The use of Ed25519 keys is recommended for better security and performance.