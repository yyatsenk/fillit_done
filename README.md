
Program displays the smallest assembled square on the standard output. To
identify each Tetrimino in the square solution, you will assign a capital letter to each
Tetrimino, starting with ’A’ and increasing for each new Tetrimino.
If the file contains at least one error, your program must display error on the standard
output followed by a newline and have to exit properly.

Example :

$> cat sample.fillit | cat -e

....$

##..$

.#..$

.#..$

$

....$

####$

....$

....$

$
#...$

###.$

....$

....$

$
....$

##..$

.##.$

....$

$> ./fillit sample.fillit | cat -e

DDAA$

CDDA$

CCCA$

BBBB$

$>

Another example :

$> cat sample.fillit | cat -e

....$

....$

####$

....$

$

....$

...$

..##$

..##$

$> ./fillit sample.fillit | cat -e

error$

$>
