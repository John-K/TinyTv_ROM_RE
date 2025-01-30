Using [GitHub - danishcake/marked-annotated-hexdump: A markedjs extension for creating annotated hex dumps](https://github.com/danishcake/marked-annotated-hexdump)
[Live Editor](https://danishcake.github.io/marked-annotated-hexdump/marked/)
```annotated-hexdump
47 50 5F 53 50 49 46 49 01 01 00 00 00 00 00 00
00 00 00 00 00 00 00 02 00 3E 21 07 00 00 00 00
78 00 2F 00 43 4C 41 53 53 49 43 00 00 00 00 00
4A 55 52 41 53 53 49 43 20 50 41 52 4B 20 56 34
04 00 00 00 01 00 00 00 02 00 00 00 03 00 00 00
04 00 00 00 FF FF FF FF FF FF FF FF FF FF FF FF
/decode
/decode_gap 4
/highlight [0:7] /0
/note /0 General Plus SPI Flash Interface magic number
/highlight [16:17] /1
/note /1 version?
/highlight [18:1b] /2
/note /2 data size
/highlight [20:23] /3
/note /3 unknown
/highlight [24:2F] /4
/note /4 Product Name
/highlight [30:3F] /5
/note /5 Product Variant
/highlight [40:43] /6
/note /6 Number of tables
/highlight [44:47,48:4b,4c:4f,50:53] /7
/note /7 Page address of table n (512 byte pages)
```