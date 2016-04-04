OBJ2PRG allows an interface file to be converted into a program file without
loading it into memory. The only limitations is the the interface file
must contain contiguous memory with no gaps. If the program finds an object
code record out of sequence or out of bounds from what is was expecting,
OBJ2PRG will report the error and exit. The resulting PRG file will contain
a memory image defined up to the break.
