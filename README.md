# HW_1_Matrices
CS344 HW1 - Matrices

### Questions
1. If I create a function to validate the matrix before passing it to one of the operations. In the
 event that the matrix is not valid (i.e. not tab delimited, does not contain at least one element, etc)
 can I output my error message to stderr from that function and exit (with a non-zero value)?
   a. return or exit

2. If using a matrix being entered via stdin. I want to read that input into a temp file that way I can 
 run it through the matrix validator function before passing it to the appropriate operation. Is my 
 logic correct? From within operation, check for number of arguments. If zero, then read input from 
 stdin into a temp file. Next validate temp file or passed file and continue with operation.

 
