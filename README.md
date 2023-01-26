# BIP39 CHECKSUM WORDS FINDER
## Find out the list of all candidate checksum words of a bip39 seed knowing only 11 or 23 words

A bip39 seed is typically made of 12 words (128 bit) or 24 words (256 bit) .
Despite you can pick whatever words you want, the last one contains a checksum and can't be picked randomly.

This script show you all the possible candidates of the last word for a bip39 seed made of 12 or 24 words. 

It also show the missing bits for each word so that you can pick one of the candidates randomly flipping a coin as many times as the missing bits length is and counting 1 for head and 0 for tail.

## Usage example:
Download the project as a zip, open a terminal in the directory and type:

`python3 main.py`

then follow the script instructions.

## Don't trust, verify!
The code is very minimal and simple so that can be reviewed. In order to avoid that you have to review the bip39 words list, it is in a separate file and you can just delete that one and download it again from https://raw.githubusercontent.com/bitcoin/bips/master/bip-0039/english.txt and save it as english.txt

## Disclaimer:
Use this project at your own risk and only in a safe environment.
I DON'T have any responsability of how you will use it and eventual money loss.
Don't use this project for your actual wallet if you don't know what you are doing!!
