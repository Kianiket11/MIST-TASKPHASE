# Guess My Cheese (Part 1)
Try to decrypt the secret cheese password to prove you're not the imposter!
Additional details will be available after launching your challenge instance.

### Solve

In this challenge we have to decrypt the given cheese in order to prove that we are not the imposter.

**Flag:** `picoCTF{ChEeSy1efea9ba}`

In this challenge we have to decrypt the given cheese to prove that we have are not the imposter. Given encrypted cheese "OHHQZKTMW", Now what i did was encrypt mozzarella and got 
"VDIIZCPEEZ" as output. Now when I checked for hints it was written related to linear equations i got that it is an Affine cipher. Now for solving part i took three equations 
(12a+b)mod 26 = 21
(14a + b)mod 26 = 3
(25a+b)mod 26 = 8
As we know in Affine cipher a,b can be anything in between (0,25) and a should be coprime to 26. after solvinf i got the answer as a=23 and b = 23.
now decrypted the text using the formula a^-1 . a(x-b) mod 26 = 1. here i foudn a^-1 as 17 and when i decrypted  "OHHQZKTMW" i got "DOOLINKVJ" and got the flag.

### New Learnings
Learnt about Affine cipher and how to encrypt and decrypt a code using Affine cipher.

### References 
None.
