Confidentiality

Confidentiality in this program is maintained by encrypting user messages using a Caesar cipher. When a message is encrypted, it is transformed into a format that cannot be easily read without knowing how the cipher works. This prevents unauthorized users from understanding the contents of the message. The login system also contributes to confidentiality by restricting access to only approved users based on role.

Integrity

Integrity in this program is supported through the use of SHA-256 hashing. When a user enters a message, the program generates a SHA-256 hash of the original message. After the message is encrypted and then decrypted, the program generates a second SHA-256 hash. These two hashes are compared. If they match, the program confirms that the message was not altered during processing. This ensures the data remains accurate and unchanged.

Availability

Availability in this program is maintained through the menu system. Users are able to log in, access encryption tools, and use hashing functions.


