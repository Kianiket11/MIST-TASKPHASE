## Hill cipher 

## Encryption:

This is a example of a substituion cipher. It works in the following way:

#step 1:
we select a key matrix square matrix of any order. this matrix is denoted with K.

#step 2:
we convert our plain text to the matrix form according to the key matrix and replace the alphabets with numbers (A-0,....,Z-25).
this matrix is denoted as P.

#step 3:
we use the formula : C = (K * P) mod 26 
using this formula we find the cipher text matrix.

example: let K = 7  8  this a 2x2 matrix.
                 11 11
                 
let out plain text be "short example" : 

s | o | t | x | m | l |            
h | r | e | a | p | e |    

these are 6 2x1 matrices which will be converted to 

 18 | 14 | 19 | 23 | 12 | 11|   
 7  | 17 |  4 |  0 | 16 | 4 |  

now we find the cipher text using  C = (K * P) mod 26 :

1.  [7 8 11 11] (K)  *  [18 7] (P)  =  [182 275] * mod 26 = [0 15]  =  [A P]
                                  
therefore sh becomes ap

following the steps given above we get the cipher text as "APADJTFTWLFJ"

## Decryption:

Decryption is done by reversing the encryption process. We use the inverse key matrix.

step 1:
We already know the key matrix:
K =  [7  8 11 11]
now we have to find k^-1 basically the inverse matrix. K^-1  = adj(K) / |k| 
here adj is adjoint of matrix K which is divided by the determinant of matrix k.

step 2:
we use the formula  P = (K^-1 * C) mod 26 to find the plain text matrix.










     
