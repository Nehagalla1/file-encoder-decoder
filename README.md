# file-encoder-decoder
Lempel-Ziv-Welch(LZW) data compression algorithm

Project Description:-
LZW is used to compress data without any loss.

The Encoding algorithm reads the sequence of characters from the input ".txt" file and converts them to ASCII code. If the character is already there, the following character is appended, creating a new string for which a new ASCII code is issued.The ASCII codes are then transformed to 16 bit binary representation and stored as a file with the extension ".lzw".


The Decoding algorithm reads the binary format from the ".lzw" file and changes it to decimal format to obtain the appropriate string.
This code works for text files only but may fail for other files.

The programming language used here 'Java' and  compiler version is 19.0.2

Encoder:
It is compiled as- javac Encoder.java 
for executing command is - java Encoder.java input1.txt 12 or java Encoder.java input2.txt 12
 • output is written into .lzw file

Decoder:
It is compiled as- javac Decoder.java 
for executing command is - java Decoder.java input1.lzw 12 or java Decoder.java input2.lzw 12
 • output is written in .txt file
