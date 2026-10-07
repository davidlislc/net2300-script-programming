# net2300 sed cut

**1. What does the 'sed' utility stand for?**

- A) Series editor
- B) Stream editor
- C) Script editor
- D) System editor

**2. Which command is used to replace only the first occurrence of 'old' with 'new' in each line?**

- A) sed 's/old/new/g' file
- B) sed 'r/old/new/' file
- C) sed 's/old/new/' file
- D) sed 'replace/old/new/' file

**3. In the command sed 's/old/new/g' file, what does the 'g' represent?**

- A) Generate
- B) Global replacement
- C) Group search
- D) Gap

**4. Which sed command correctly deletes the second line of a file?**

- A) sed 'd2' file
- B) sed 'line2d' file
- C) sed '2d' file
- D) sed 'delete 2' file

**5. What is the purpose of the -n option in the command: sed -n '3p' file?**

- A) It numbers the lines
- B) It suppresses the default output
- C) It names the file
- D) It creates a new line

**6. Which command allows you to insert a line BEFORE line 2?**

- A) sed '2a\...'
- B) sed '2i\...'
- C) sed '2b\...'
- D) sed '2s\...'

**7. To append a line AFTER line 2, which command should be used?**

- A) sed '2a\...'
- B) sed '2i\...'
- C) sed '2p\...'
- D) sed '2d\...'

**8. What does the command sed '/pattern/d' file do?**

- A) Deletes only the word 'pattern'
- B) Deletes lines matching a specific pattern
- C) Duplicates lines matching a pattern
- D) Displays lines matching a pattern

**9. Which command replaces 'old' with 'new' only in lines containing 'pattern'?**

- A) sed 's/old/new/pattern'
- B) sed 'replace/old/new/if/pattern'
- C) sed '/pattern/s/old/new/' file
- D) sed 'pattern s/old/new/g' file

**10. What does the regex '\buser\b' specifically match?**

- A) Any word starting with 'user'
- B) Any word ending with 'user'
- C) The exact word 'user' using word boundaries
- D) The word 'username'

**11. Which utility is designed to extract sections, columns, or fields from lines of input?**

- A) sed
- B) cut
- C) shift
- D) echo

**12. In the cut command, which option is used to select characters by position?**

- A) -b
- B) -f
- C) -d
- D) -c

**13. What does the command cut -d ',' -f 2 filename.csv do?**

- A) Deletes the second comma in a file
- B) Extracts the second field using a comma as a delimiter
- C) Finds two commas in the second line
- D) Creates a second CSV file

**14. If you want to extract the 1st and 3rd fields from a colon-separated file, which command is correct?**

- A) cut -c 1,3 file
- B) cut -d ':' -f 1,3 /etc/passwd
- C) cut -b 1,3 file
- D) cut -f 1-3 -d ':' file

**15. What is the purpose of the 'shift' command in Bash scripting?**

- A) To move a file to a new directory
- B) To change the script's permissions
- C) To manipulate positional parameters by shifting them to the left
- D) To exit the current loop

**16. By default, how many positions does the 'shift' command move parameters?**

- A) 0
- B) 1
- C) 2
- D) All parameters

**17. If a script is run as './script.sh apple banana' and 'shift' is called, what does $1 become?**

- A) apple
- B) banana
- C) script.sh
- D) null

**18. Which 'cut' option allows you to select bytes by position?**

- A) -c
- B) -d
- C) -b
- D) -f

**19. In the command 'shift [n]', what does 'n' represent?**

- A) The name of the parameter
- B) The number of positions to shift
- C) The new value of the parameter
- D) The script version

**20. Which command is used to specify a delimiter for fields when using cut?**

- A) -d
- B) -f
- C) -s
- D) -b

