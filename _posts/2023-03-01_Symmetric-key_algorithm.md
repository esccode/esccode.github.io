---
title: Symmetric-key algorithm
categories:
- cyber
feature_text: |
#
---

## Symmetric-key algorithms

Are algorithms for cryptography that use the same cryptographic keys for both the encryption of plaintext and the decryption of ciphertext. The keys may be identical, or there may be a simple transformation to go between the two keys. The keys, in practice, represent a shared secret between two or more parties that can be used to maintain a private information link. The requirement that both parties have access to the secret key is one of the main drawbacks of symmetric-key encryption, in comparison to public-key encryption (also known as asymmetric-key encryption). However, symmetric-key encryption algorithms are usually better for bulk encryption. With exception of the one-time pad they have a smaller key size, which means less storage space and faster transmission. Due to this, asymmetric-key encryption is offen used to exchange the secret key for symmetric-key encryption.

## Implementations

Examples of popular symmetric-key algorithms include Twofish, Serpent, AES(Rijndael), Cammelia, Salsa20, ChaCha20, Blowfish, CAST5, Kuznyechik, RC4, DES, 3DES, Skipjack, Safer, and IDEA.

## Use as a cryptographic primitive

Symmetric ciphers are commonly used to achieve other cryptographic primitives than just encryption.  
Encrypting a message does not guarantee that it will remain unchanged while encrypted. Hence, often a message authentication code is added to a ciphertext to ensure that changes to the ciphertext will be noted by thethentication codes can be constructed from an AEAD cipher (e.g. AES-GCM).  
However, symmetric ciphers cannot be used for non-repudiation purposes except by involving additional parties. See the ISO/IEC 13888-2 standard. Another application is to build hash functions from block ciphers. See one-way compression function for descriptions of several such methods.

## References

[wiki link](https://en.wikipedia.org/wiki/BMC_Software) by wikipedia.

## External Link

[BMC ](https://www.bmc.com/).