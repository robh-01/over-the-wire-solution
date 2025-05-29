#overthewire #bandit #terminal #game
-  **Level 0**:
Login using SSH: 
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
# to get to level 1 replace bandit0 with bandit1 in the above command.
# for n level replace it with banditn
# where n is any no of available level in the game.
```

**Levels with their password and way to find password for the next level:**

- **Level 1 (bandit1):**
Password:
```
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

- **Level 2:**
Password:
```
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

- **Level 3:**
Password:
```
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

- **Level 4:**
Password:
```
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

- **Level 5:**
Password:
```
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
Command to find password for Level 6:
```bash
find -not -executable -size 1033c | xargs cat
```

- **Level 6:**
Password:
```
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```
Command to find password for Level 7:
```bash
find / -user bandit7 -group bandit6 -size 33c 2> /dev/null | xargs cat
```

- **Level 7:**
Password:
```
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```