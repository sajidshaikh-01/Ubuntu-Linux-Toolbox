
command: > /path/file name


Command: ls -li


3.To create your own named pipe, use the mkfifo command as follows:
$ mkfifo mypipe
$ ls -l mypipe




$ ls -l Files and directories in current directory
$ ls -la Includes files/directories beginning with dot (.)
$ ls -lt Orders files by time recently changed
$ ls -lu Orders files by time recently accessed
$ ls -lS Orders files by size
$ ls -li Lists the inode associated with each file
$ ls -ln List numeric user/group IDs, instead of names
$ ls -lh List file sizes in human-readable form (K, M, etc.)
$ ls -lR List files recursively, from current directory and subdirectories


$ joe memo.txt Open memo.txt for editing
$ joe -wordwrap memo.txt Turn on wordwrap while editing
$ joe -lmargin 5 -tab 5 memo.txt Set left margin to 5 and tab to 5
$ joe +25 memo.txt Begin editing on line 25


$ cat myfile.txt Send entire file to the screen
$ cat myfile.txt > copy.txt Direct file contents to another file
$ cat myfile.txt >> myotherfile.txt Append file contents to another file
$ cat -s myfile.txt Display consecutive blank lines as one
$ cat -n myfile.txt Show line numbers with output
$ cat -b myfile.txt Show line numbers only on non-blank lines

<img width="438" height="504" alt="image" src="https://github.com/user-attachments/assets/5942b561-e762-4f37-9038-cb0f2d8463ec" />

