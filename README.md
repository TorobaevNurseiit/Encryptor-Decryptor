# Run-Length Encoding (RLE) Compressor and Decompressor in C++

This repository contains two simple C++ programs for **Run-Length Encoding (RLE)**:
- **Encoder**: Compresses plain text files using RLE.
- **Decoder**: Decompresses RLE-encoded files back to their original form.

---

## What is RLE?

**Run-Length Encoding** is a basic form of lossless data compression where runs of the same character are stored as a single character and count.

For example:  
`AAABBBCCDAA` → `A3B3C2D1A2`

---

##  Features

- **File-based**: Reads and writes files (`input.txt`, `output.txt`, `decompressed.txt`)
- **Easy to use**: Just compile and run!
- **Console Output**: Shows compressed and decompressed text in the terminal as well

---
## File structure
.
├── encoder.cpp        # Compressor code
├── decoder.cpp        # Decompressor code
├── input.txt          # Your plain text input (create this!)
├── output.txt         # Compressed output (created by encoder)
├── decompressed.txt   # Decompressed output (created by decoder)



