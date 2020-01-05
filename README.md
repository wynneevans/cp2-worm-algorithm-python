# CP(2) Worm Algorithm in Python

I am using the C++ implementation I wrote during my postdoc, found [here], as the starting point of a personal Python project. The goal is to write Python code that reproduces C++ results, but also demonstrates much better software development practices.

## Software Development Mistakes in the C++ Code

In no particular order:

1) No testing
2) All function and main code in same file
3) Not developed using version control
4) No documentation
5) No proper error handling, just print statements.
6) Horrible list of arguments to Lattice class, surely inheritance could be used to make things more elegant.
7) Program arguments explained crudely. perhaps have settings/inputs file.
8) Beta and Nt paramters are not locked according formula, an example of leaving unnecessary room for user error.



   [here]: <https://github.com/wynneevans/CP2-Worm-Algorithm-CPP>
