# UNIX CLI Cheatsheet

## Navigating

- `cd` = "change directory"
- `cd ~` = "change directory to my home directory"
- `cd ~/Desktop` = "change directory to my Desktop"
- `pwd` = "print working directory"
- `ls` = "list files in the current directory"

## Moving and Renaming

- `cp fileA.txt fileB.txt` = "make a copy of `fileA.txt` named `fileB.txt`"
- `mv fileA.txt fileB.txt` = "move (i.e. rename) `fileA.txt` to `fileB.txt`"

## GREP

Search for all marginal notes in the file `WoN_1.html`, output to a new file names `margins.txt` (The `-o` means "don't give me the whole line where you found this, just ('Only') the thing I identified."):

> `grep -o '<span class="type-margin"><span>[^<]\+</span></span>' WoN_1.html > margins.txt`

## Piping and Redirecting

- Instead of dumping output to the screen, write to a file with `… > [filename.txt]`
- For better feedback, get fancy with: `… | tee [filename]`

## Git Commands

Basic cycle:

- `git pull`
- (do some work; save it)
- `git add <filename>`
- `git commit -m "Describe what you did, briefly."
- `git push`

## Markdown

[Link to Markdown on Wikipedia](https://en.wikipedia.org/wiki/Markdown)
