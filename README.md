# entropy2bip39.py
Simple python script that takes arbitrary input and outputs a valid BIP39 mnemonic

This program takes an arbitrary input of entropy and converts it into a BIP39 mnemonic.
This entropy can be dice rolls, a card deck, random input, coin flips etc.
Be aware, that if your source of entropy is not truly random and contains too few bits of entropy, the resulting mnemonic is not secure!
It is generally not a good idea to use this program!

Simply save the entropy2bip39.py file, make it executeable and run it in the terminal. The focus of this script is to be as simple and self-contained as possible. Should run on only live-linux installation that has python3 preinstalled. The idea is to do it on a permanently airgapped computer.
