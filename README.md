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
