# Retro_8bit's PGP Public Key

## Purpose
Allows me to sign important announcements / updates I make with my private key, so that their authenticity can be verified by the recipients using the corresponding public key. This makes impersonating me or tampering with my communications way harder. Its like a signature but backed by math and RSA encryption.

## What is PGP? 
> "Pretty Good Privacy (PGP) is an encryption program that provides cryptographic privacy and authentication for data communication. PGP is used for signing, encrypting, and decrypting texts, e-mails, files, directories, and whole disk partitions and to increase the security of e-mail communications. Phil Zimmermann developed PGP in 1991." 
- [Wikipedia - Pretty Good Privacy](https://en.wikipedia.org/wiki/Pretty_Good_Privacy)

## How does it work?
### What I do
I write my message in plaintext like this readme file you're reading right now. I then import the plaintext into my PGP program (in this case I’m using GnuPG) and encrypt it using my private key. The private key does not get shared with anyone else, only I have access to it. The encrypted version of the message is sent alongside the plaintext version, so that you can compare them to verify authenticity.

### What you do
You download the public key from this GitHub repo and import it into your PGP program of choice. You then decrypt the encrypted message using the public key in your PGP program. You can then compare the result of the decryption to the plaintext message to check if it was modified in transit. Since the only thing your public key can decrypt are messages encrypted with my private key, you can be certain that I am the one who originally wrote the message. 

## When / where would this be used? 
Like I said in the purpose section, I will be using PGP to sign any major announcements or important messages. This could be anything from me making a major change to how I appear online (Changing my main online handle from Retro_8bit to XxXDemon_SlayerXxX, for example), when I make a major announcement or change to one of my projects, or to verify the authenticity of a new account I make (In the event that I get locked out of my current account for that platform, for example).

### You can expect to see PGP signed messages from the following aliases
 - Retro_8bit
 - Retro
 - Friction-X
### The following people / organizations might relay signed messages on my behalf
- Lernant (Rs and Houb)
- The 16Bit Paradise staff
- Close IRL friends

(The private key will never be shared with any of these people. All signed messages will originate from me)

# Test the PGP public key here!
```
-----BEGIN PGP MESSAGE-----

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
=CHCL
-----END PGP MESSAGE-----
```
