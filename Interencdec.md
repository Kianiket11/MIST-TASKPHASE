## Interencdec

Can you get the real meaning from this file.
Download the file : YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclgya3lNRFJvYTJvMmZRPT0nCg==


### Solve
**Flag:** `picoCTF{caesar_d3cr9pt3d_b204adc6}`

As given in the challenge, we need to decrypt the given word. Now as i saw "==" at the end i got the idea that its a BASE64 encoding.
So, i used BASE64 decoding in cyberchef and got " b'd3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrX2kyMDRoa2o2fQ==' " now again this was a BASE64 
encoding but onlt the part inside the single quotes. So, after redoing the same proceess i got " wpjvJAM{jhlzhy_k3jy9wa3k_i204hkj6} ".
Now, i was able to see the structure of the flag and was i able to see that its a ceaser ciper. THerefore, in cyberchef i used ROT13 
brutefore and got the flag.


```
ROT13 bruteforce
Amount = 19: picoCTF{caesar_d3cr9pt3d_b204adc6}
```

### New Learnings
Learnt about different types of ciphers and learnt how we can decode and encode data using them. Also learnt more about Cyberchef which 
is very useful for encrytion and decryption.

### References 
None.
