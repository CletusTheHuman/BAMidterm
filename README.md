Confidentiality

Confidentiality in this program is maintained by encrypting user messages using a Caesar cipher. When a message is encrypted, it is transformed into a format that cannot be easily read without knowing how the cipher works. This prevents unauthorized users from understanding the contents of the message. The login system also contributes to confidentiality by restricting access to only approved users based on role.

Integrity

Integrity in this program is supported through the use of SHA-256 hashing. When a user enters a message, the program generates a SHA-256 hash of the original message. After the message is encrypted and then decrypted, the program generates a second SHA-256 hash. These two hashes are compared. If they match, the program confirms that the message was not altered during processing. This ensures the data remains accurate and unchanged.

Availability

Availability in this program is maintained through the menu system. Users are able to log in, access encryption tools, and use hashing functions.

Entropy & Key generation

In this program, the Caesar cipher uses a shift value as the key to encrypt and decrypt messages. This shift tells the program how many letters to move forward or backward in the alphabet. Even though this key is simple and not randomly generated, it still shows how encryption depends on a key to work.

This project does not use advanced key generation like real encryption systems. In stronger systems like AES, keys are created using random number generators so they have high entropy and are difficult to predict. In this program, the fixed shift value is used just to demonstrate the basic idea of how keys control encryption and decryption.


