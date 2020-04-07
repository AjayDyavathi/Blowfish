# Blowfish
Blowfish algorithm from scratch in python3

This is a symmetric key block cipher encryption algorithm developed by Bruce Schneier in 1993. It has good encryption rates and there's no significant cryptanalysis found yet!

The key size can be varied from 32 to 448 bits.
Block size is 64 bits.

This program is an implementation of blowfish cipher from scratch in python3.
This will encrypt strings of any length.
I will upgrade it to encrypt files soon.

Any enhancements to this file are encouraged.
Do not use this code in serious productions, because I wrote this without concerning any memory management and optimisations.
Purely for understanding and educational purposes.

USAGE: 

 ```
 #ENCRYPTION
 python3 blowfish.py -m e -k my_awesome_key -s THIS_IS_SO_CONFIDENTIAL_INFORMATION
 
 #DECRYPTION
 python3 blowfish.py -m d -k my_awesome_key -s """hex cipher"""
 
 
