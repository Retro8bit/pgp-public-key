# Retro_8bit's PGP Public Key

## Purpose
Allows me to sign important announcements / updates I make with my private key, so that their authenticity can be verified by the recipients using the corresponding public key. This makes impersonating me or tampering with my communications way harder. Its like a signature but backed by math and RSA encryption.

## What is PGP? 
> "Pretty Good Privacy (PGP) is an encryption program that provides cryptographic privacy and authentication for data communication. PGP is used for signing, encrypting, and decrypting texts, e-mails, files, directories, and whole disk partitions and to increase the security of e-mail communications. Phil Zimmermann developed PGP in 1991." 
- [Wikipedia - Pretty Good Privacy](https://en.wikipedia.org/wiki/Pretty_Good_Privacy)

## How does it work?
### What I do
I write my message in plaintext like this readme file you're reading right now. I then encrypt it using my private key. The private key does not get shared with anyone else, only I have access to it. The encrypted version of the message is then sent alongside the plaintext version, so that you can compare them to verify authenticity.

### What you do
You download the public key from this GitHub repo and import it into your PGP program of choice (I recommend GnuGP). You then decrypt the encrypted message using the public key. Once the message has been decrypted, you can compare the result of the decryption to the plaintext message to check if it was modified in transit. Since the only thing your public key can decrypt are messages encrypted with my private key, you can be certain that I am the one who originally wrote the message.

# Test the PGP public key here!

```
-----BEGIN PGP MESSAGE-----

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
asmO/ZndmC7+0bebj8qn79v1mwem/v5UbK3/fw==
=HMxr
-----END PGP MESSAGE-----
```
