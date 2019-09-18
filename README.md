We call a string S a correct bracket sequence if it consists only of the characters '{', '}', '[', ']', '(', ')' and at least one of the following three conditions is true:

1 S is an empty string;
2 S can be represented as S = S1 + S2 + S3 + ... + SN (N> 1), where Si are nonempty regular bracket sequences, and the “+” sign indicates the concatenation (attribution) of strings;
3 S can be represented as S = '{' + C + '}' or S = '[' + C + ']' or S = '(' + C + ')', where C is the correct bracket sequence.
Given a string consisting only of the characters '{', '}', '[', ']', '(', ')'. It is required to determine the minimum number of characters that must be inserted in this line in order for it to become the correct bracket sequence.

Input data
The first line of the input file INPUT.TXT contains a line consisting only of the characters '{', '}', '[', ']', '(', ')'. The line length does not exceed 100 characters.



2 solutions.
Dynamic programming and recursion.
