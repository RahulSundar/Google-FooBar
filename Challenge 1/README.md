Write a function called `solution(data, n)` that takes 
in a list of less than 100 integers and a number `n`, 
and returns that same 
list but with all of the numbers that 
occur more than n times removed entirely. 
The returned list should retain the same ordering 
as the original list - you don't want to mix up those 
carefully-planned shift rotations! For instance, 
if data was `[5, 10, 15, 
10, 7]` and n was 1, `solution(data, n)` would return 
the list `[5, 15, 7]` because 10 occurs twice, and thus 
was removed from the list 
entirely.

Your code will run inside a Python 2.7.13 sandbox. 
All tests will be run by calling the `solution()`
function.

Standard libraries are supported except for bz2, 
`crypt, fcntl, mmap, pwd, pyexpat, select, signal, 
termios, thread, time, 
unicodedata, zipimport, zlib`.

Input/output operations are not allowed.
