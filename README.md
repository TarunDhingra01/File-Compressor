File-Compressor
A File Compression software that helps zip/Unzip files using these 2 algorihtms:

1) Huffmans Code
2) Lempel-Ziv-Wells algorithm

1) Huffmans Code
The Huffmans algo creates a 1-1 mapping for each byte of the input file and replaces each byte with the mapped bit sequence. For this you need to store a dictionary that describes each 1-1 mapping of input byte and binary sequence.(which needs extraspace)

2) Lempel-Ziv-Wells algorithm 
Unlike Huffmans code LZW dont need an extra dictionary to be saved. Also LZW does not create a mapping to byte to bin sequence. It creates mapping of multiple byte to binary sequence.
