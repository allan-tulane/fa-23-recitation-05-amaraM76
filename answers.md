# CMPS 2200 Recitation 6
## Answers

**Name:**__Amara Midouhas_______________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File        | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt      |  2144               | 826            | 0.385261 
alice29.txt |  1187848            | 676374         | 0.569411 
asyoulik.txt|  1001432            | 606448         | 0.605581 
grammar.lsp |  29768              | 17356          | 0.583042     
fields.c    |  89200              | 56206          | 0.630112     

Huffman coding outperforms fixed-length coding consistently when we are compressing data. Also, the cost of Huffman coding is lower than the fixed-length coding cost because the Huffman vs. Fixed-Length ratios are all smaller than 1. 


- **e.**
If every character has the same frequency, Huffman coding would switch to binary coding. The binary tree would be balanced or closely balanced because each leaf node has the same length as the root node since there is no reason to give shorter codes to certain characters over others. Since Huffman code is based around the frequencies and all characters have the same frequency, the cost is the same for all documents.
