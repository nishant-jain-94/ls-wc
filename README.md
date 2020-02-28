# ls

In computing, `ls` is a command to list computer files in Unix and Unix-like operating systems. When invoked without any arguments, `ls` lists the files in the current working directory. In other environments, such as DOS, OS/2 and Microsoft Windows, similar functionality is provided by the `dir` command.

## Exercise
1. Implement a `ls` command in **python** without using the `ls` command. Name this tool to be called as `lspy`. To be more precise it should be able to do the following things:
    - Just like how `ls` command lists all the files and directories in the current working directory. `lspy` should also be able to retrieve all the files and the directories in the current working directory.
    - Just like how `ls /directory` lists all the files and directories in this directory, `lspy /directory` should also be able to list all the files in this directory.

# wc

In computing, `wc` (short for **w**ord **c**ount) is a command in Unix and Unix-like operating systems. The program reads either standard input or a list of files and generates one or more of the following statistics: **newline count, word count, and byte count.** If a list of files is provided, both individual file and total statistics follow.

## Exercise
1. Implement a `wc` command in **python** without using the `wc` command. Name this tool to be called as `wcpy`. To be more precise it should be able to do the following things:
    - Just like how `wc -l <name_of_the_file>` returns number of lines in the file. `wcpy -l <name_of_file>` should be able to list all lines in the file.
    - Just like how `wc -m <name_of_the_file>` returns number of characters in the file. `wcpy -m <name_of_the_file>` should be able to print the character counts in the file.


# Unix Philosophy

1. Make each program **do one thing well**. To do a new job, build afresh rather than complicate old programs by adding new "features".
2. Expect the **output of every program to become the input to another**, as yet unknown, program. Don't clutter output with extraneous information. Avoid stringently columnar or binary input formats. Don't insist on interactive input.
3. Design and build software, even operating systems, to be tried early, ideally within weeks. Don't hesitate to throw away the clumsy parts and rebuild them.
4. Use tools in preference to unskilled help to lighten a programming task, even if you have to detour to build the tools and expect to throw some of them out after you've finished using them.