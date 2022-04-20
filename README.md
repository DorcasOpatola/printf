<h1> printf </h1>
This is a printf team project developed by Anuoluwa Akinsola and Dorcas Opatola for ALX software engineering school.

<h1> Welcome </h1>  
Rebuild of the standard printf function in C. Our project required a function capable of printing with the %d, %c, %s, and %% specifiers to standard output. printf returns the number of characters printed (excluding the null byte at the end of strings). We were not asked to handle flag characters, field width, precision, or length.

<h1> Format </h1>
Our team chose to add %x ,%X, %b, %o, %u, %r, %R, and %p formatting. We relied on the library we have been building at Alx as well as new concepts gathered during this project.

<h1> Supported Format Types </h1>
TYPE - OUTPUT

c - Single character

s - String of character

r - String in reverse

R - String in rot13

d - Integer in decimal

i - integer

% - Percent sign

x - Lowercase hex(loervase)

X - Uppercase hex (unsigned)

b - signed binary

o - signed octal

u - unsigned integer

p - pointer address

<h1> Examples </h1>
Character: printf("%c", A);    Output: A

String: printf("%s", This is a string.);   Output: This is a string.

Integer: printf("%i", 5);   Output: 5

<h1> File Functions </h1>
<h2> _printf.c </h2>
Own printf function that performs formatted output conversions and prints data.

<h2> main.h </h2>
Header file were all prototyped and saved.

<h1> Authors </h1>
Anuoluwa Akinsola and Dorcas Opatola
