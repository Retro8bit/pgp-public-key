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

owFtVn1sFNcRPwJVk0MhEDUJFqA+jAC7tc9YtBEhAgxHYh92E8u2is1HnHd77+4e
t7tv2X3r81HTms/mQ6GENJUdC6gjUIoaaNqQEAqFQIlAVeu2UYNLG4OKSpEVp3Ij
ZBK1mM683fVxDv/4/L5m5vebmd/s7vsnhsITLv7v7I+M/uNvTTgc3hOfkuIy7cZt
ZomIbJcJY+v5OaSBSVu0LopzOd8h9dX1pN6N61wjtSwXDs+ZA0vbEg4LL9d1kXWI
wYgUxOEpk3DDErakpiTUNIVrasxgpnRIBXGtBJXMITFi0AwjWXBLjByxbN4G+yTD
cmXEEUSmqYQ/jNuEuvBrSq5xmSMaNUmckTZm8yRnCRLP4S1iM41bXLlwHW6m1KYm
bJs5ljATuGN5sYODCGlKc0f5dzBSZjvCpBIvAQRhE0lxE9dBeJowDNfkGtwSpkOy
NEfS1E4wO0Ji4FPnAIUq6FS6NiNxV5I41TJehAYFK9RMkIbG5YSZmp2z0E5Ekbga
kXLF7zISXkqK620mAWm1EAlSj7RoOVICp6V4C+DnDQBrImVTw2MLFm08AZDUMR5Y
aQBs+SbQ/xiVCgdJAlbIBi2EF1Gp5sgkhI93EBewUTbmGv9HewkWrIlk7dKBG+UG
5Tr8k+Q6g58Eh9RIYXNc4JNsWugMtp0MsagtuUconkDtcLDPqMNU+hymuTbmXCR9
s+PSAIGmYXMNNwxmG1BoEE8b04UFYSsIJql87LHKSDEJl5O1q3mGwwmnpJzcheL1
JWkpLWdxRQUzI9ngbkTYqQpcVXhPWvFJq/+kVOWvRmRJQmAlSZIVdmYZbPpZjcFB
OEaygIJhFRnMcWiKYWCWTrmJnHm1I7EgAXoCChCZIznhzreZ2kJ2bZ5KS2KKLNQb
khN0mCIqbwt+BDpC9EFtlIA3ZV5DYmNXO7sNv0eqTbe+ulRx7ycWMXhnhS2JHcPu
3PAQm0KSFJPEgV4AzlWzUDMnTEaY7rAyIkw9BwGnaRu0h6YBfJVl6dnzncJLaGcH
CxIyjYDGeHI8rA5DIdGFmXKgwMdh9t/mVQOoUzIBxQIVpq4b6FZpRq5ATlQH+snC
Z5CuFvWTNXVBE56nMd0gSVsYHpfVXNa4cYJyqfjzs8H9FIAtuyAJAExLC64xUhJD
sYI6ZvAMMgB9HSHoVCH1G0o5ztMT8JGXtjvF7GlQ1wLa0tQBjcxbY4myu5ECcTiu
LgPSg16GNEgxjuPAMhxoaaZlCE+qcgdHhkh4SoxlZlPTwew28iAmVQFAGcStSLmD
TQwnwIsh+U6cO4DfdToEUGAMaAyGjKpv1W1KCdEnQ5kBJecpblIdIsjaQhaQFGgv
sFQBlxn4zwpXT3jpjTMlfqDHddidMeJQ7iFU3Kuph/okVeFBh3Nd9x4hUEx8MAih
HUD+N4CIFg5C2MjPyAC5P5g0FQiYg8cedarwQBpgZOGS+ia1NDW9rKRBhAC/ZTFq
I+ccKCiJ4rHfzAbS5B/AdgIkRhnNj3g009zevJIZwmxt1GmO2bAsUwOAtcNE1Flp
GVJlBrOb3gUZKQgLMwHlpTIoNgBfMARwvo41I/JZMN/hNiUmy6JcgFEZ+CqJeeSD
wJsyyDdqjy7UlBWu9D3B0LCVXvgGMH5vPupUwsIohORLQItfVKzdgjBV+hhTmcQ0
5nvQCUQA+BP42aPyoXPQVicMkyXP59gK/3nS5qpYypuVt6aC5xYTEAnUIQwbavJN
/keGoTTfZpCKLwUBTQpQ4yxN9SQMtzpmm1hIJQ3eKK0RbrwU9tFP5aMrILn11IZJ
glUraRKfRHWs4VhDHQCCD6eEEw6XjBd5VdYmUG5jNY5TeV83wIgXf4TAZ+CXAlUm
/EaULChknJykiTme0CmhzOsCNuPs8PP3LJwUmhAOzXp49qSenpETE19816058+yf
g6/Wr9yD36ih8H1Tg53tux8Ynbdref+eKRV/uxVdcrmXfO/4fqv3xsHBaffv+LRD
DrxhfP5F7sPk6IHf9C/o2zRzaNeMz0+fu3Wr80j3vE8O7a4cmblz283/rHit6ifL
B+Pli7Z8tGK7NlzVXXTe2rF3VdHxTMeNuqqbFx88/cS5yre3PnV16nt9nx3pH2gc
fe65XR8XXTv7646r/9qwzpnbtGdJ3TusZ7rz+vMjrxyjm8+NjE7rerrukeKp/QeH
boRmvDJy4IW60J8eKCtd3Jvs3Dzyx8a9wz0vb/r4te3dMxp2Xgh9Fts7vfP2vvPf
r3r/yrPXGL30wqqHt734cuvJaydrojfWfDK8c6jn2FE+mHni9Jna6/NKtjQN/3uR
OHvJbXw/3vPqQFHxqWNf7/7VgmlXGk7d+8HGfQutUOXRpSv7zsl+uu6vxuNPrh79
aenmlsTI8YtrLo/2LZz9wdT5H/4yWrHd+Ms3z5z66qELh6rXl/72B0e/mPTRz6a8
teH6QyM3pyyo6RusGhpe9tTvN/dFt7U++swk0TIYndtZf732h/o7R4cOfWunm/nv
Nxq21S5NFb/XnGteV7T/xOLq0HD97FWvRrsmV3acWR8/sOPWiVlHom/2ruVNvd9t
uZ2a3PXSkuG1iyevWfnM469v+d3hvV2hAafj4ttXpg/OufSPlzoeemPp/oUnHzn4
i3/2DPx91soff/ru3D/Ubu1avX9m5ufOjMyFr12e2J+5r1HsK3qzWn778Mbv3I5v
/D8=
=yt0m
-----END PGP MESSAGE-----
```
