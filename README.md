ZX Spectrum disassembler ver 1.0.0
I was interested on how Spectrum is programmed, both in Basic and assembler.
After a long search on the web, I found few apps that can show what's hiding in an ROM image of ZX Spectrum software. And most of them are old, even working by command line.
So, I decided to write a Windows application.
The program can open Z80 files, a standard developed in 3 version, covering all the Sinclair's pc (Spectrum 16, 48 and 128k) and other console the use the same processor Zilog Z80.
In this application i focused on the 48k Spectrum, hoping to estend it to 16k and 128k soon, even most of Z80 files are referred to the 48k version.
Z80 files contain all the bytes from the display ($4000) to the top of RAM ($FFFF).
By disassembling such a file, we can view the display image, the BASIC lines and, eventually, the disassembled machine code.
Through the listing we can navigate across the CALL statements in order to follow the assembly flow.
I'm italian, but the user can switch between italian and english Language of the interface.
Hoping to have helped most of you.

Gennaro Cifariello. Livorno, Tuscany Italy.
