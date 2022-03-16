# haskellCreditCardValidator
Basic Credit Card Validator 

This is a basic credit card validator routine to sastify the following algorithm:

# BASIC CREDIT CARD ALGORITHM

1. Drop the last digit from the number (call it checkDigit)
2. Reverse the numbers
3. Multiply the digits in odd positions (1,3,5 etc) by 2
4. Subtract 9 to any results higher than 9
5. Add all the numbers together
6. Add the check digit to the sum
7. Check if the total sum can be divided by 10
