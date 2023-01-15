Write a JavaScript program to validate a credit card number. You can indicate the credit card type you are validating ex. Visa, Mastercard etc.

PS: Kindly drop a brief description that explains the regex pattern you came up with

‘ ^ ‘ is representing the starting of the Pattern.

‘ 5[1-5]{1} ‘ is representing that the First letter must be 5 and the second letter can be within 1 to 5.

‘ [0-9]{2}[\s]?[0-9]{4}[\s]?[0-9]{4}[\s]?[0-9]{4} ‘

Above represents the rest of the number can be within 0-9.

‘$’ represents the end of the pattern.
