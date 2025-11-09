# Caesar Cipher Decryption in C

This program decrypts text encrypted using the Caesar cipher.  

## Code

```
#include <stdio.h>

int main() {
    char text[100];
    int key;
    int i;

    printf("Enter the key: ");
    scanf("%d", &key);

    printf("Enter the ciphertext: ");
    getchar();
    fgets(text, sizeof(text), stdin);

    for (i = 0; text[i] != '\0'; i++) {
        if (text[i] >= 'A' && text[i] <= 'Z') {
            text[i] -= key;
            if (text[i] < 'A')
                text[i] += 26;
        }
        else if (text[i] >= 'a' && text[i] <= 'z') {
            text[i] -= key;
            if (text[i] < 'a')
                text[i] += 26;
        }
    }

    printf("Decrypted text: %s", text);
    return 0;
}
