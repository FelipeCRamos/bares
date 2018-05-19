# BARES Project
Title came from _**B**asic **Ar**ithmetic **E**xpression Evaluator based on **S**tacks_

# Objectives
This project consists on the implementation of a simple expression calculator using concepts of stack and array in a real context application. The program needs to be able to recieve simple arithmetic expressions made of:

+ Numeric constants (-32.768 to 32.767).
+ Operators (`+`, `-`, `/`, `*`, `^`, `%`), with their correspondant priority.
+ Delimiters (`()`, `[]`, `{}` ).

# Dependencies
You need `git` to clone the repository, `make` and `g++` to compile the program. To install these dependencies, you just have to use your package manager, such as a debian based distro:

`sudo apt-get install g++ git make`

# Compile
To compile the project, first you need to clone the repository, enter in directory with

````bash
git clone https://github.com/felipecramos/bares.git; cd bares
````

And then, type `make` on project root.

# Execute
You can execute bares by using `std::cin `or reading and writing expressions with shell streams.

Example on unix based systems:

```bash
./bares < input_file > [output_file]
```
And even execute and type successively expressions ended by `<CR>` and then press `ctrl-d` to stop reading and show the results.

# Authorship
This program was made by [Felipe Ramos](https://github.com/FelipeCRamos) for Programming Language I discipline, on Computer Science Course on [Universidade Federal do Rio Grande do Norte](https://ufrn.br).
