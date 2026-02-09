Security Explanation – CIA Triad, Entropy, and Key Generation
How this solution supports Confidentiality, Integrity, and Availability

This program demonstrates all three parts of the CIA triad through its design and functionality.

Confidentiality

Confidentiality is maintained by encrypting user messages using a Caesar cipher. When a message is encrypted, it is transformed into a format that cannot be easily read without knowing how the cipher works. This prevents unauthorized users from understanding the contents of the message. The login system also contributes to confidentiality by restricting access to only approved users based on role.

Integrity

Integrity is supported through the use of SHA-256 hashing. When a user enters a message, the program generates a SHA-256 hash of the original message. After the message is encrypted and then decrypted, the program generates a second SHA-256 hash. These two hashes are compared. If they match, the program confirms that the message was not altered during processing. This ensures the data remains accurate and unchanged.

Availability

Availability is maintained through the program’s menu-driven structure and role-based access system. Users are able to log in, access encryption tools, and use hashing functions whenever needed. The system is simple and stable, allowing authorized users to access the features without unnecessary barriers or downtime.

Role of Entropy and Key Generation

Entropy refers to randomness and unpredictability in cryptographic systems. Strong encryption typically relies on randomly generated keys so that attackers cannot easily guess them.

In this implementation, a Caesar cipher is used as a basic symmetric encryption method. Instead of generating a random key, the cipher uses a fixed shift value to transform the message. While this is not considered strong encryption in real-world security systems, it demonstrates the concept of key-based encryption and decryption.

Key generation in this program is represented by the shift value used in the Caesar cipher. This value controls how the message is encrypted and decrypted. In more advanced encryption systems such as AES, keys would be generated using secure random number generators to provide high entropy and stronger protection.

This project illustrates the foundational concept of encryption keys and entropy, even though it uses a simplified method for educational purposes.
