# entropy2bip39.py
Simple python script that takes arbitrary input and outputs a valid BIP39 mnemonic

This program takes an arbitrary input of entropy and converts it into a BIP39 mnemonic.
This entropy can be dice rolls, a card deck, random input, coin flips etc.
Be aware, that if your source of entropy is not truly random and contains too few bits of entropy, the resulting mnemonic is not secure!
It is generally not a good idea to use this program!
