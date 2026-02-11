# TO CHECK FOR TIME OF FILE MODIFICATIONS, DIFFERENCE BETWEEN FILES, AND COMPARISON OF FILES THESE COMMANDS ARE FOR YOU:

ls -lt <br>
ls -lu<br>
ls -lc <br>
stat <file_name><br>
file <file_name> <br>
diff <file_name1> <file_name2> <br>
sdiff <file_name1> <file_name2><br>
cmp <file_name1> <file_name2><br>
vimdiff <file_name1> <file_name2><br>
watch -n 1 ls -l -----> Watch file changes in realtime, "CTRL + C" to end the process. <br>
watch stat <file_name> -----> Watch a specific file change in real-time <br>
