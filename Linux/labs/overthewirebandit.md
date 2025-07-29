# 🧪 OverTheWire Bandit Walkthrough (Levels 0-20)

This document covers my walkthrough of the OverTheWire Bandit wargame from Level 0 to Level 20.

---

## 🎮 What is Bandit?

[Bandit](https://overthewire.org/wargames/bandit/) is a Linux-based wargame designed to teach and test command-line skills. Each level requires using shell commands to uncover a password hidden in the file system. The goal is to retrieve the password for the next level by solving practical, real-world style challenges.

This walkthrough includes all levels from 0 to 20, with the exact commands I used and brief insights into what I learned at each step.

---

## ✨ My Journey with OverTheWire Bandit

> As part of strengthening my Linux foundation, I explored the OverTheWire Bandit wargame — an incredibly effective and hands-on way to improve real-world command-line skills. The game presents challenges that gradually increase in complexity, each one reinforcing core Linux concepts through practical problem-solving.

For those new to it, Bandit is designed to boost your confidence in the terminal. You’re tasked with navigating file systems, decoding obscure files, working with permissions, and using essential shell commands to find hidden passwords and advance through levels. It’s not just a learning experience — it’s a puzzle-based journey into the Linux CLI.

---

## Level 0

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
---

## Level 0 → Level 1

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
copy password
ssh bandit1@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Learned to SSH into a remote server using a specific port.

---

## Level 1 → Level 2

```bash
ls
cat./-
copy password
ssh bandit2@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Understood how to read a file named with a special character.

---

## Level 2 → Level 3

```bash
ls
cat "spaces in this filename"
copy password
ssh bandit3@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Handled filenames with spaces using quotes.

---

## Level 3 → Level 4

```bash
ls
cd inhere
ls -a
cat -hidden
copy password
ssh bandit4@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Used 'ls -a' to list hidden files and access dotfiles.

---

## Level 4 → Level 5

```bash
ls
cd inhere
file./*
cat ./-file07
copy password
ssh bandit5@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Identified human-readable files using the 'file' command.
---

## Level 5 → Level 6

```bash
ls
cd inhere
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
copy password
ssh bandit6@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Filtered files by size and type using the 'find' command.

---

## Level 6 → Level 7

```bash
find / -user bandit7 -group bandit6 -size 3c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
copy password
ssh bandit7@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Worked with file permissions and owners.

---

## Level 7 → Level 8

```bash
ls
grep "millionth" data.txt
copy password
ssh bandit8@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Extracted data from a file with specific formatting.

---

## Level 8 → Level 9

```bash
ls
sort data.txt
sort data.txt | uniq -u
copy password
ssh bandit9@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: 

---

## Level 9 → Level 10

```bash
ls
strings data.txt
strings data.txt | grep '='
copy password
ssh bandit10@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Used 'strings' and 'grep' to find values in binary files.

---

## Level 10 → Level 11

```bash
cat data.txt
base64 -d data.txt
copy password
ssh bandit11@bandit.labs.overthewire.org -p 2220
paste password
```

> ✅ Learned: Decoded base64-encoded files.
---

## Level 11 → Level 12

```bash
# Commands for level 11 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 11

---

## Level 12 → Level 13

```bash
# Commands for level 12 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 12

---

## Level 13 → Level 14

```bash
# Commands for level 13 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 13

---

## Level 14 → Level 15

```bash
# Commands for level 14 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 14

---

## Level 15 → Level 16

```bash
# Commands for level 15 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 15

---

## Level 16 → Level 17

```bash
# Commands for level 16 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 16

---

## Level 17 → Level 18

```bash
# Commands for level 17 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 17

---

## Level 18 → Level 19

```bash
# Commands for level 18 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 18

---

## Level 19 → Level 20

```bash
# Commands for level 19 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 19

---

## Level 20 → Level 21

```bash
# Commands for level 20 go here
# Replace with actual commands used
```

> ✅ Learned: Key concept or command from level 20
