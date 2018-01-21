# Sudoku
An implementation of solving Sudoku using "Pencil-and-Paper Algorithm for Solving Sudoku Puzzles by J. F. Crook"


To design and implement a program that will read a sudoku grid whose representation is stored in
a filename.txt and create a Sudoku object, with a number of methods:
 a method preassess() that prints out to standard output whether the representation is correct
and has no digit that occurs twice on the same row, on the same column or in the same box;
 a method bare_tex_output() that outputs some Latex code to a le, filename_bare.tex, that
can be compiled by pd
atex to produce a pictorial representation of the grid;
 a method forced_tex_output() that outputs some Latex code to a le, filename_forced.tex,
that can be compiled by pd
atex to produce a pictorial representation of the grid to which the
forced digits technique has been applied;
 a method marked_tex_output() that outputs some Latex code to a le, filename_marked.tex,
that can be compiled by pd
atex to produce a pictorial representation of the grid to which the
forced digits technique has been applied and that has been marked;
 a method worked_tex_output() that outputs some Latex code to a le, filename_worked.tex,
that can be compiled by pd
atex to produce a pictorial representation of the grid to which the
forced digits technique has been applied, that has been marked, and to which the preemptive set
technique has been applied.
The input is expected to consist of 9 lines of digits, with possibly lines consisting of spaces only that will
be ignored and with possibly spaces anywhere on the lines with digits. If the input is incorrect, that is,
does not satisfy the conditions just spelled out, then the program should generate a SudokuError with
Incorrect input as message.
