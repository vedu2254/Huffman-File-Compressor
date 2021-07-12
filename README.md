# Huffman-File-Compressor
**Implementation of Huffman Coding algorithm for lossless text compression.**

I have explained the working of my program in a great detail in my blog [here](https://vedu2254.medium.com/implementation-of-huffman-coding-for-lossless-text-file-compression-46c6be795121).

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

|         Text File	       | Original Size	| Compressed Size| Compression Ratio |
| ------------------------ |--------------| --------------| ---------------- |
| sample-2mb-text-file.txt | 2167737 Bytes  |   1.14552e+06  |  52.8442%    |
| sample-text-file.txt      | 448 Bytes      |   235.25 Bytes | 52.5112% |
| sample.txt | 1182 Bytes      |    705.625 Bytes | 59.6975%  |
| big.txt| 6488666 Bytes| 3.68309e+06 Bytes| 56.762%|


It works best on large text files. Very small text files sometimes get larger after compression using this technique because there is overhead. On average every text file get compressed to about **50%** of the total size.
