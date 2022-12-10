# Converting Decimal Numbers to Other Number Systems

### Decimal To Hexadecimal
1. Divide the decimal number by 16. Treat the division as an integer division (get a full number as your remainder).
2. Write down the remainder.
3. Divide the result again by 16. Treat the division as an integer division.  
4. Repeat step 2 and 3 until result is 0.
5. The hex value is the digit sequence of the remainders from the **last to first**.

Example: Starting with the decimal number **256**:
| DIVISION | RESULT | REMAINDER (in HEX) |
|----------|--------|--------------------|
| 256 / 16 | 16     | 0                  |
| 16 / 16  | 1      | 0                  |
| 1 / 16   | 0      | 1                  |
|          |        |                    |
| ANSWER   |        | 100                |
 
Your hexadecimal number is **100**

---

[Next: Converting Decimal to Octal](https://github.com/hannahandboba/FinalTutorial/blob/main/Decimal%20to%20Octal.md)

[Go Back Home](https://github.com/hannahandboba/FinalTutorial)

