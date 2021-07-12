# Huffman-File-Compressor
**Implementation of Huffman Coding algorithm for lossless text compression.**

I have explained the working of my program in detail [here](https://vedu2254.medium.com/implementation-of-huffman-coding-for-lossless-text-file-compression-46c6be795121).

For Compression -<br/>
1.Run myCompressor.exe or compile source code<br/>
2.Enter name of file (with extention) to compress

The code-mapping file will be saved as Dictionary.txt and the Compressed File generated after compression will be with .cmp extension having same filename.

For Decompression -<br/>
1.Run myDecompressor.exe or compile source code<br/>
2.Enter the name of the Dictionary file (gets saved as Dictionary.txt by default)<br/>
3.Enter same file name with .cmp extension e.g. - sample.cmp<br/>
4.Decompressed file will be generated with name Decompressed.txt

Result -<br/>
It works best on large text files. Very small text files sometimes get larger after compression using this technique because there is overhead. On average every text file get compressed more than **50%** of the total size.
