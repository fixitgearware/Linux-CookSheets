# TO FIND PATHS OF FILES AND EXECUTABLES USE THESE COMMANDS BELOW:

find . <br>
find /path -type f <br>
find /path -type d <br>
find . -maxdepth 1 <br>
find . -name "*.log" <br>
find . -iname "*.txt" <br>
find . -size +200M ------> This will find files greater than 200MB <br>
find . -mtime -1 --------> locate files modified in the last 24-hrs <br>
find / -type f 2>/dev/null <br>
find . -type l<br>
find . -perm /4000<br>
