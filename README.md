# Cryptology
Rough Implementations of some useful and not so useful ciphers, techniques, attacks etc.


# Question - modified_vigenere_cipher:

Define a modified shift cipher where characters occurring at the odd positions are shifted (addition modulo 10) by applying the key character once and  the characters occurring  at the even positions are shifted by applying the key character twice. Implement (encryption and decryption) this cipher in python

Encrypt 10^(16) - 1 using this cipher where key is of 4 digits (the key is repeated after encrypting every 4 character block). The plaintext and ciphertext alphabets are the digits 0,1,2,...,9.  Also show the decryption of the ciphertext obtained.
