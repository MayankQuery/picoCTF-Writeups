# picoCTF Challenge: Obedient Cat

**Category:** General Skills  
**Points:** 10  
**Status:** Solved  
**Level:** Beginner  

---

## Challenge Description:

> This file has a flag hidden inside it. Can you read it?

---

## Tools/Skills Used:
- Linux Terminal
- `cat` command (used to display contents of a file)

---

## Step-by-Step Solution:

1. Downloaded the file from the picoCTF problem: `flag.txt` 
2. Open the terminal
3. Run the commands:
   ```bash
   whoami
   pwd
   ls
   cat flag

# Output:
picoCTF{s4n1ty_v3r1f13d_4a2b35fd}
