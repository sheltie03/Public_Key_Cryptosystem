# Public_Key_Cryptosystem
Uploaded mainly python scripts of public key cryptosystem...
## RSA-OAEP.py: 
- remark: These functions are for understanding RSA or RSA-OAEP easily, so do not strictly follow the RSA specification.
- 1st func: [RSA Encoding algorithm] 3 variables(m: message, n: public key of RSA which the product 2 prime numbers, e: another public key) -> cipher text
- 2ed func: [WRONG RSA Decoding algorithm] 3 variables(c: cipher text, d: secret key, n: public key) -> message
- 3rd func: hexadecimal -> CharacterCode (for example: 33 -> 3 and so on...)
- 4th func: it changes an integer array to a character string.
- 5th func: Refer to RSA specification or my OAEP.pdf for MGF(masked generation function). 
- 6th func: Refer to RSA specification or my OAEP.pdf for RSA-OAEP Encoding function.
- 7th func: Refer to RSA specification or my OAEP.pdf for RSA-OAEP Decoding function.
- remark: I guess input r of RSA-OAEPDec is wrong, but it is for understanding RSA-OAEP. I think input is not r but hLen.
## paillier.py:
- remark: Refer to my document paillier.pdf which is written in Japanese, but if only you trace a stream of equations in document, you can understand paillier's theory.
- 1st func: LCM is the least common multiple.
- 2ed func: The key generation of Paillier Public Key Cryptosystem
- 3rd func: [Paillier Encoding algorithm] r is a random integer except multiples of p or q.
- 4th func: This function is useless, because the next function should contain it.
- 5th func: [Paillier Decoding algorithm] 
