# LPCC-Assignments
Now, let’s understand lexical analysis in programming languages like C++. The compilation is spread across many stages. A compiler does not immediately convert a high-level language into binary – it takes time to complete! During the compilation process, the first step that is undertaken is called lexical analysis. During this process, the program typed by the user is shredded to pieces and every token that is a part of it is extracted and stored separately (tokens are the smallest indivisible parts of a program). These tokens need to be classified into particular types before the compilation process can begin.

There are several types of token which are associated with any language. The naming given by the user for several parts of the program like functions and variables is called identifiers. They are called as such because they “identify” a named storage location in the memory. Then comes keywords: a number of words used by the language for some of its functionality (In C++, these include words like cout, cin, if, else, for, break, continue, and so on). Punctuators are used for the construction of expressions and statements. They are useful only when used in conjunction with identifiers or keywords in a statement. Operators are used for performing actual operations with the data (like arithmetic, logical, and shift operations). Literals are constant data that the programs need to deal with, like numbers or alphabets (or a combination of both).

What does a lexical analyzer do? 
Separation of a program into its tokens and classification of the tokens is the main responsibility of the lexical analyzer.

What is a Compiler?

Before moving to lexical analysis in C++, we need to have a basic understanding of a compiler.

Most of the programs we type in are in English (or some other language). A computer cannot understand English; it can interpret only a stream of 1’s and 0’s. In other words, binary is the only language comprehensible to a computer. Hence, it is necessary to convert these “high-level” language programs to binary before the computer can understand the instructions. That is exactly what a compiler and an interpreter are used for. They make our programs comprehensible to the computer.

Despite performing the same functions, compilers and interpreters are slightly different by nature. A compiler is normally quite huge in size, while an interpreter is considerably smaller and occupies fewer system resources. A compiler converts the entire program to binary codes at once and then executes it. If there is an error in any part of the code, the program won’t give any output. However, an interpreter converts the program to binary line-by-line while executing each line it has converted. This ensures that some output is always given before it comes across an error. As is already evident, a compiler is much faster than an interpreter. There are some more differences between them.

Most programming languages use either a compiler or an interpreter under the hood for conversion to binary code (also called “machine language”). C++ uses a compiler, while Python uses an interpreter. Some languages like Java use both. You can also check our online compiler for your programming needs.
