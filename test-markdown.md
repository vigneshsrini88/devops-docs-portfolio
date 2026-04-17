# Linux CLI Quick Reference
The ***Linux Command Line Interface*** (*CLI*) is a text-based environment used to interact with the computer's operating system (OS) by entering specific commands.  
It is highly efficient for automation, remote server management, and technical troubleshooting.
-----
## Basic Linux commands

- `cd {space} {folder name}` - This command opens the folder.
- `cd {space} ~` - This command opens the home page.
- `pwd` - This command displays the path.
------
| Command | Flag | Purpose |
|:-------:|:----:|:--------|
|`chmod`|`777`|Provide full permission to all - `rwxrwxrwx` - owner (7 - means full permission to read, writer, and execute), group (7), and other (7) |
|`chmod`|`764`|Provide permission to partial - `rwxrw-r--` - owner= rwx (7), group = rw- (6), other = r-- (4)|
--------
## Code block
```bash
cat ~/.bashrc
ls ~/projects | grep -i "linux"
```
--------
## Inline Code
`chmod 644`
----
## Blockquote
> To find a file and write it inside the file use the `>`. This will add the content inside the file. If you want to add the text to the end of the content inside the file, use `>>`.
----
## Link

[Linux](https://labex.io/linuxjourney)
-----
## Task List

- [x] - Test Done
- [x] - week1 -day3
- [ ] - Learning Complete
- [ ] - week1-day4

-----



