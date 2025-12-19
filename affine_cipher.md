## Affine Cipher 

# Encryption
#step 1:
To encrypt we use the formula (a*x + b) mod 26.
some rules we have to follow are 
1. a and b are between 0-25
2. a must co-prime with 26

#step 2:
We change the aplhabets of the plaint text to number.
for example:
MATH ---> 12  0   19   7

now i took a = 3 and b = 7.

now we use : (3x+7) mod 26 .
1. x = 12
   (3*12+7) mod 26 =   43 mod 26 =  17 ---> R
   
similarly we take the different values of x and find the cipher text
therefore cipher text for MATH is "RHMC"

# Decryprtion 

For decryption we use the formula a^-1(x-b) mod 26 

here we find a^-1 using :  (a * a^-1) mod 26 = 1

for our example as a = 3, the value of a^-1 must be 9 to get 27 mod 26 which is 1.

Cipher text RHMC --->  18 7 12 2 

we use the formula 9(x-b) mod 26

1. 9(17-7) mod 26 =  90 mod 26 = 12 ---> M
   
   similarly we find the remaing text which is MATH




