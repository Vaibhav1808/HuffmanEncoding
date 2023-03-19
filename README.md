# HuffmanEncoding
Designed a technique for encrypting data using C++ with the help of Huffman’s 
Algorithm. Reads the data from file in system and Command Line Interface displays the 
encoded strings. It takes your text file as input.

# Huffman Encoding?
Huffman encoding is a lossless data compression algorithm that assigns variable-length codes to characters in a message based on their frequency of occurrence.The basic idea behind Huffman encoding is to use shorter codes for more frequently occurring characters and longer codes for less frequently occurring characters. This can result in significant compression of the original data.

# Technique
In Huffman encoding, the complete set of codes can be represented as a
binary tree, known as a Huffman tree. This Huffman tree is also a
enoding tree i.e. a full binary tree in which each leaf is an encoded symbol
and the path from the root to a leaf is its code word. By convention, bit ‘0'
represents following the left child and bit '1' represents following the
right child. One code bit represents each level.

