# Simplified DES (S-DES) Tool

This tool performs Simplified DES with the following features:
1. Encryption & decryption
2. Multi-block support (8-bit blocks)
3. ECB or CBC (with specified or random IV)
4. Step-by-step display of the process

# Usage:
1. Select e for encryption or d for decryption.
2. Select ECB (Electronic Code Book) or CBC (Cipher Block Chaining)
2.1. If using CBC, optionally enter an 8-bit IV, or let it be randomly generated
3. Enter your 10-bit key (you will then see the subkey generation process)
4. Enter your input in binary (please ensure your input length is a multiple of 8, i.e. your input consists of bytes)
5. Watch two S-DES rounds being applied to each of the blocks.
6. You will get your encrypted ciphertext / decrypted plaintext.
