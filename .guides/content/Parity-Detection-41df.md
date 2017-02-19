While data is in transit, it is important to ensure that the data received is the same as the data sent.  To ensure that extra bits are not added nor are bits lost in transmission, a parity bit is often used to make sure that the data received is correct.

Different standards are used but the principle is similar, in an even parity check a 7 bits of our data are grouped and sent with an eighth parity bit being added to the front of the number.

For example:
0111001 is even because it has four 1s.  Therefore a leading 0 is added for a number 00111001.

{Test Even Parity}(python CIA/TestEven.py)
