
0	| 1	| 2	| 3	| 4	| 5	| 6	| 7	| 8	| 9	| a	| b	| c	| d	| e	| f
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15

10 | 11	| 12 | 13 | 14 | 15 | 16 | 17	| 18 | 19	| 1a | 1b	| 1c | 1d	| 1e | 1f
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31

20 | 21	| 22 | 23	| 24 | 25 | 26 | 27	| 28 | 29	| 2a | 2b	| 2c | 2d	| 2e | 2f
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
32 | 33 | 34 | 35 | 36 | 37 | 38 | 39 | 40 | 41 | 42 | 43 | 44 | 45 | 46 | 47

## [Official Documentation](http://www.warmplace.ru/wiki/doku.php?id=sunvox:manual_en)
A few words about hex numbers. Memory locations and software in today's computers use the hexadecimal (hex) number system which comprises sixteen distinct symbols, digits 0 - 9 and letters A, B, C, D, E, F (or a - f) where the letters represent the numbers 10 - 15. For more detail on the hexadecimal system please visit: http://en.wikipedia.org/wiki/Hexadecimal

Examples of hexadecimal numbers and its decimal (dec) equivalents:

00 = 0;
01 = 1;
…
09 = 9;
0A = 10;
0B = 11;
0C = 12;
0D = 13;
0E = 14;
0F = 15;
10 = 16;
11 = 17;
…
FF = 255

## [The Complete Guide to Sunvox](https://sunvox-guide.readthedocs.io/en/latest/beginner/hex-intro.html)
Introduction to hex notation
Hex notation is just another way of writing numbers.

In normal decimal notation (what you’re probably used to) you have:

0	1	2	3	4	5	6	7	8	9
10	11	12	13	14	15	16	17	18	19
20	21	22	23	24	25	26	27	28	…
In hexadecimal (or hex, for short) this becomes:

0	1	2	3	4	5	6	7	8	9
a	b	c	d	e	f	10	11	12	13
14	15	16	17	18	19	1a	1b	1c	…
The way this works is that instead of running from 0 through 9, digits run from 0 through 15. However, since we don’t have digits for 10, 11, 12, 13, 14 or 15, we use letters. So, a means 10, b means 11 and so on.

This change also extends to the positions of digits. In regular decimal notation, if you have two digits the first one counts tens. If you have three digits, the first one counts hundreds, the second counts tens and so on.

For example, if we have the number 14 in decimal, that can also be shown mathematically as:

1×10+4×1=14
In hexadecimal, you don’t need a special position to count tens, because you can simply write “a” and have the same as 10 in decimal. Instead, you have a digit that counts by 16, or 161. The next digit up from that counts by 256, or 162. Next comes the digit that counts by 4096, or 163.

This is why 14 in hexadecimal corresponds to 20 in decimal:

1×16+4×1=20
When we rearrange our hex table above based on what we just learned, it looks like this:
0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
0	| 1	| 2	| 3	| 4	| 5	| 6	| 7	| 8	| 9	| a	| b	| c	| d	| e	| f
10 | 11	| 12 | 13 | 14 | 15 | 16 | 17	| 18 | 19	| 1a | 1b	| 1c | 1d	| 1e | 1f
20 | 21	| 22 | 23	| 24 | 25 | 26 | 27	| 28 | 29	| 2a | 2b	| 2c | 2d	| 2e | 2f

Why do we use hex notation while tracking?
People use hex notation in tracking software for technical and historic reasons. This differs from many other types of DAW software, which often use decimal.

Electronic computers use the binary system of counting, to indicate on/off or +/-. The only two digits available are 0 and 1, which leads to long numbers like 11001 (which is 25 in decimal). Hexadecimal is a way to show those numbers very concisely, while keeping a mathematical relationship to the number 2.

The first tracking apps from the 1980s ran on computers far slower than today’s, with limited screen space. Today, SunVox aims to support low-resolution screens and slower processors.

Hex gives you two advantages here:

You can show the full range of numbers of a “byte” using two digits (00-ff) instead of three with decimal (0-255).
You can work more directly with what’s in the computer’s memory, which can lead to smaller and more efficient code.
Interestingly, it also happens to fit well with the quarter note rhythms typical of music! After understanding, then practice, it will be familiar and comfortable for you to use.
