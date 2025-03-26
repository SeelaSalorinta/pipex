# 🔗 pipex – The Magic of Pipes

 For my fifth project at Hive Helsinki, I built pipex, a program that mimics the shell’s piping behavior. 🚰 It takes four arguments:

    file1 (input file)

    cmd1 (first command)

    cmd2 (second command)

    file2 (output file)

It works just like this shell command:

< file1 cmd1 | cmd2 > file2

For example:

./pipex infile "ls -l" "wc -l" outfile

should behave like:

< infile ls -l | wc -l > outfile

This project was an awesome hands-on way to understand file descriptors, pipes, and process management in C. ⚡
