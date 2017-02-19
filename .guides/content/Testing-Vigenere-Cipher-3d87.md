![Vigenere Square](https://pifflelab.files.wordpress.com/2012/05/vigenere-table1.png)

To encrypt a message using the Vigenere square, find the first letter in the message you wish to encrypt and the corresponding row from the left column.  Then find the first letter in your passphrase in the top row, this will give you the column.  Where the two intersect, you can find your first encrypted letter.

Repeat this process with the second, third, etc. letters.  Remember to repeat the passphrase once all the letters have been used.

{Test Vigenere Cipher}(python Encryption/VigenereTest.py)
