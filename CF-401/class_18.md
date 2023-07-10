# Cryptography

## Questions

- What is the basic principle behind the Caesar Cipher, and how was it used historically?

The Caesar Cipher is a basic encryption technique that involves shifting each letter in the plaintext by a fixed number of positions in the alphabet. For example, if we use a shift of 3, "A" becomes "D," "B" becomes "E," and so on. This cipher was named after Julius Caesar, who allegedly used it to send secret messages during wartime. The principle behind the Caesar Cipher is quite simple: it substitutes letters in the plaintext with other letters from the alphabet. The recipient of the message would then use the same fixed shift value to decipher it by shifting the letters back to their original positions.

- What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?

Symmetric and asymmetric encryption are two fundamental types of encryption. In symmetric encryption, the same key is used for both the encryption and decryption processes. It is like having a shared secret between two parties. On the other hand, asymmetric encryption uses a pair of mathematically related keys: a public key for encryption and a private key for decryption. The public key can be freely shared, while the private key must be kept secret. Asymmetric encryption is widely used in secure communication today because it provides a more secure method for exchanging sensitive information. It allows for secure key exchange, digital signatures, and the establishment of secure communication channels over untrusted networks.

- How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.

Computers generate random numbers using algorithms called random number generators (RNGs). True Random Number Generators (TRNGs) generate numbers based on physical processes that are inherently random, such as atmospheric noise or radioactive decay. TRNGs provide truly random numbers but may be slower and require specific hardware. Pseudo-Random Number Generators (PRNGs), on the other hand, use deterministic algorithms to generate seemingly random numbers. PRNGs start with an initial value called a seed and then apply mathematical formulas to generate a sequence of numbers. While PRNGs are faster and easier to implement, their output is deterministic and predictable if the seed is known. TRNGs are preferred in cryptographic applications where true randomness is crucial, while PRNGs are commonly used for non-cryptographic purposes or when speed and efficiency are important.

- What’s the difference between encryption and decryption? Explain with an analogy.

Encryption and decryption are two processes used in cryptography. Encryption is the process of converting plaintext into ciphertext, making the original message unreadable to unauthorized individuals. It's like putting a message inside a locked box. The encryption algorithm takes the plaintext and a key as input, and through a series of mathematical operations, transforms the plaintext into ciphertext. Decryption, on the other hand, is the reverse process of encryption. It's like opening the locked box to retrieve the original message. The decryption algorithm takes the ciphertext and the correct key as input, and it reverses the operations performed during encryption to recover the original plaintext. Encryption protects sensitive information by ensuring that even if intercepted, the message remains secure unless the recipient has the correct key to decrypt it.

## Reading and links

[Encryption, decryption, and cracking](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

[Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

[Cryptography: Crash Course Computer Science #33](https://www.youtube.com/watch?v=jhXCTbFnK8o)

[Introduction to Cryptography](https://thebestvpn.com/cryptography/)

[How Computers Generate Random Numbers](howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)
