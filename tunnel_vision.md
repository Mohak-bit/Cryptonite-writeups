# Picoctf

## Tunnel vision

### Solution

I opened the file and it was a bunch of random symbols, but the first 2 letters were BM, after looking it up, I found out that this is a BMP file and opened it in an hex editor. After reading about BMP files for a little bit, I tried to figure out what everything means, but in the end I brute forced my way and compared it to another BMP file. In the end I just increased the images height to get the flag.

### References

[1] [Wikipedia page for BMP files](https://en.wikipedia.org/wiki/BMP_file_format)              
[2] [Hex editor](https://hexed.it/)

flag: `picoCTF{qu1t3_a_v13w_2020}`
