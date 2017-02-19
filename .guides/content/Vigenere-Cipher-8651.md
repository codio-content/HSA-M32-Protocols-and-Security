Due to weaknesses in the Caesar Cipher, more complex ciphers have been created.  One example is the Vigenere Cipher.  Like the Caesar Cipher, the Vigenere Cipher shifts a letter up the alphabet but unlike Caesar, the key does not remain the same for each shift.  Since the shifts are different, the Vigenere cipher is not as vulnerable to a brute force attack nor a letter frequency analysis.

The Vigenere Cipher works by taking in a message to encrypt and a passphrase.  The encryption key shifts across the passphrase in a repeating pattern.

Imagine we have the message "Attack at dawn" with a passphrase "tango".  Rather than using a static key, we will find the location of the letter 't' in the alphabet and that is our first shift key.  For the next letter in the message, we will use the shift 'a'.  When all the letters of our passphase have been used, we repeat the phrase until we reach the end of the message.
