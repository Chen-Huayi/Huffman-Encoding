# Huffman Encoding Implementation
### Part1
Set up some data structures, including **Dictionary** and **Hashtable**, run unit tests:
```shell
node TestPart1.js
```
### Part2&3
Using these data structures from Part1 to build Huffman tree, then applies Huffman 
encoding algorithm on input file. 
The current input file is official test file `hamlet.txt` by running command:  
```shell
node HuffEncoding.js hamlet.txt
```
If user want to test other files, please **HARDCODE** the another input file name <`filename`> with command:  
`node HuffEncoding.js <filename>`  
And then, you will see some details of input file's characters (weight, huffman code). 
Also, the file `output.txt` will be written to a Huffman code by appending.
