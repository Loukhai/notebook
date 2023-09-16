# HEX
Hexadecimal (often abbreviated as "hex") is a base-16 numbering system used in mathematics and computer science.
It provides a convenient way to represent and work with binary data more compactly and human-readable than pure binary representation.
In the hexadecimal system, numbers are represented using 16 distinct symbols: 0-9 and A-F (or a-f).

- Prefix: hex values may be prefixed with '0x' e.g:"0x2a3"
- base-16 system: hex is a base-16 numbering system using 16 symbols:
  - 0-9: to represent the values from 0 to 9.
  - a-f: `` `` `` `` `` from 10 to 15.
- Compact Representation: Each hexadecimal digit represents 4 bits (half a byte) and is used to efficiently represent binary data.
- Common Usage: Hexadecimal is commonly used in computing for memory addresses, binary data, and colors in graphics.
- Conversion: Easily converted to binary and decimal; each digit corresponds to 4 bits.
  - For example, the hexadecimal value 2A3 is equivalent to:
  - Binary: 0010 1010 0011 (4 bits per hexadecimal digit)
  - Decimal: 675 (2 * 16^2 + 10 * 16^1 + 3 * 16^0)


🫡😮 Here's a breakdown of the expression:

"2A3" is a hexadecimal number, where:
- "2" represents the digit in the 256's place (16^2).
- "A" represents the digit in the 16's place (16^1).
- "3" represents the digit in the 1's place (16^0).

To convert this hexadecimal number to decimal, you calculate each digit's contribution to the final value:
- The digit "2" in the 256's place contributes 2 * 16^2 to the value.
- The digit "A" in the 16's place represents the decimal value 10, so it contributes 10 * 16^1.
- The digit "3" in the 1's place represents the decimal value 3, so it contributes 3 * 16^0.

You then add up these contributions to get the final decimal value:
- 2 * 16^2 = 2 * 256 = 512
- 10 * 16^1 = 10 * 16 = 160
- 3 * 16^0 = 3 * 1 = 3

Finally, you add these contributions together:
- 512 + 160 + 3 = 675
  
So, "2A3" in hexadecimal is equivalent to "675" in decimal.
