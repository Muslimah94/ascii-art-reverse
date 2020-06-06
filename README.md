# ascii-art-reverse
Ascii-reverse consists on reversing the process, converting the graphic representation into a text.
     You will have to create a text file containing a graphic representation of a random string.
     The argument will be a flag, --reverse=&lt;fileName>, in which --reverse is the flag and &lt;fileName> is the file name.
     The program must print this string in normal text.
     
This project will help you learn about :
     Client utilities.
     The Go file system(fs) API.
     Ways to receive data.
     Ways to output data.
     Manipulation of strings.
     Manipulation of structures.
     
Instructions
     Your project must be written in Go.
     The code must respect the good practices.
     It is recommended that the code should present a test file.

Allowed packages
Only the standard go packages are allowed

Usage
student@ubuntu:~/ascii-art$ go build
student@ubuntu:~/ascii-art$ cat file.txt
 _              _   _
| |            | | | |
| |__     ___  | | | |   ___
|  _ \   / _ \ | | | |  / _ \ 
| | | | |  __/ | | | | | (_) | 
|_| |_|  \___| |_| |_|  \___/  

student@ubuntu:~/ascii-art$ ./ascii-art --reverse=file.txt
hello
student@ubuntu:~/ascii-art$
