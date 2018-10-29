---
title: Bash grep
---

## Bash grep

`grep` is a command on Unix-like operating systems for searching plain-text data sets for lines that match a regular expression.

### Usage

```bash
grep [options] PATTERN [file_path]
```
You can search a file in any directory without even entering the directory. Consider you are in a directory with folders- Test1,Test2. You're in the parent directory you can list all files in Test1 as follows-
`ls Test1`

Most used options:

* '-i': Ignore uppercase vs. lowercase.
* '-v': Invert match.
* '-c': Output count of matching lines only.
* '-l': Output matching files only.

### Example:

Display lines with the word 'root' in file '/etc/passwd'

$ grep root /etc/passwd
root:x:0:0:root:/root:/bin/bash
operator:x:11:0:operator:/root:/sbin/nologin

#### More Information:

* [Wikipedia](https://en.wikipedia.org/wiki/Grep)
