# Converting Decimal Numbers to Other Number Systems

### Decimal To Binary
1. Divide the number by 2.
2. Get the integer quotient for the next iteration.
3. Get the remainder for the binary digit.
4. Repeat the steps until the quotient is equal to 0.

Example: Starting with the decimal number **15**:
|Divide by 2 	 | Quotient	  | Remainder	  | Bit #   |
|-------------|-----------|------------|--------|
|15/2	         | 7          |	1	          | 0       |
|7/2	         | 3	        | 1	          | 1       |
|3/2           |	 1        |	1	          | 2       |
|1/2	         | 0        	| 1           |	3       |

Now, you can look at the remainder and bits column to find your binary number:

| Bit #        | 0      | 1      | 2      | 3      |
|--------------|--------|--------|--------|--------|
| Remainder    | 1      | 1      | 1      | 1      |

Your binary number is **1111**


[Next: Converting Decimal to Hexadecimal](https://github.com/hannahandboba/FinalTutorial/blob/main/Decimal%20to%20Hexadecimal.md)

[Go Back Home](https://github.com/hannahandboba/FinalTutorial)
