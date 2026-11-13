13 November 2026:
Tools - 1)ffmpeg - ffmpeg is a universal media converter, it can read a variety of inputs 2)qrencode - It encodes input data in a QR code and can save as an PNG image
ffmpeg -i MSN.mov  -frames:v 1 MSN.jpg
qrencode -o file1.jpg "Hello SNAI Class"
BREAK:
1)I changed the file extension to xyz and it showed "Unable to choose output format for MSN.xyz"
2)I removed the flag -o and it showed "no output filename is given"

