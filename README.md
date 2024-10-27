# A-simple-way-to-check-if-a-number-is-a-polindrom-in-c-
So first of all we need to check if the number is negative(if so return false because it wont be a polindrom).
1. We convert the number in to a string (by using ToString)
2. in the same line we convert that string to be an array of chars (so we can revers it easily)(ToCharArray)
3. now we return the result of the check - is the reversed array(using Reverse) is equal to the array (to check the contents and not the reference equality we use SequenceEqual)
