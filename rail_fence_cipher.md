## Rail Fence cipher

# Encryption 
#Encryption : This is a example of a Transportaion cipher. It works in the following way: 
step 1: 
We select the number of rails or also called depth for the encryption. for example we take the depth as 3 

step 2: 
Now we will make a matrix more like a chess board of size depth x no. of letters in the plain text. Now we fill the 
text in zig-zag manner.
for example we take plain text as "defend the east wall" our depth is 3.
it will be filled like this. we use xx as blank space just to fill the matrix.

<img width="687" height="112" alt="image" src="https://github.com/user-attachments/assets/4d179fae-7645-49e4-af10-4153c9d7d319" />

step 3:
Now we take the letter of each row and get out cipher text 
therefore out cipher text is : DNETLEEDHESWLXFTAAX

# Decryption 
step 1
As we know the depth of cipher we now decrypt by filling the the matrix by leaving out the diagonal elemets like this :

<img width="860" height="124" alt="image" src="https://github.com/user-attachments/assets/87cff304-a7ef-4cd9-9246-386bde6db4dd" />
this is just an example after filling the first row we fill out the second row and finnaly we get the plain text
