
[0-hello_world](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world)
---
* A script that prints `“Hello, World”`, followed by a new line to the standard output.

[1-confused_smiley](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley)
---
* A script that displays a confused smiley `"(Ôo)'`
---
[2-helloflife](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile)
* A script that displays the content of the `/etc/passwd` file.
---
[3-twofiles](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles)
* A script that displays the content of `/etc/passwd` and `/etc/hosts`.
---
[4-lastlines](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines)
* A script that displays the last 10 lines of a file.
---
[5-firstlines](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines)
* A script that displays the first 10 lines of a file
---
[6-third_line](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line)
* A script that displays the third line of a file.
---
[7-file](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file)
* A shell script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text Best School ending by a new line.
---
[8-cwd_state](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state)
* A script that writes into the file `ls_cwd_` content the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.
---
[9-duplicate_last_line](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line)
* A script that duplicates the last line of the file `iacta`
  - The file `iacta` will be in the working directory
---
[10-no_more_js](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js)
* A script that deletes all the regular files (not the directories) with a **.js** extension that are present in the current directory and all its subfolders.
---
[11-directories](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories)
* A script that counts the number of directories and sub-directories in the current directory.
  - The current and parent directories should not be taken into account
  - Hidden directories should be counted
---
[12-newest_files](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files)
* A script that displays the 10 newest files in the current directory.
* Requirements:
  - one file per line
  - Sorted from the newest to the oldest
---
[13-unique](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique)
* A script that takes a list of words as input and prints only words that appear exactly once.
  - Input format: One line, one word
  - Output format: One line, one word
  - Words should be sorted
---
[14-findthatword](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword)
* A script that displays lines containing the pattern “root” from the file `/etc/passwd`
---
[15-countthatword](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/15-countthatword)
* A script that displays the number of lines that contain the pattern “bin” in the file `/etc/passwd`
---
[16-whatsnext](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/16-whatsnext)
* A script that displays lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`.
---
[17-hidethisword](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/17-hidethisword)
* A script that displays all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.
---
[18-lettersonly](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/18-letteronly)
* A script that displays all lines of the file `/etc/ssh/sshd_config` starting with a letter.
---
[19-AZ](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/19-AZ)
* A script that replaces all characters `A` and `c` from input to `Z` and `e` respectively.
---
[20-hiago](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/20-hiago)
* A script that removes all letters `c` and `C` from input.
---
[21-reverse](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/21-reverse)
* A script that reverse its input.
---
[22-users_and_homes](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/22-users_and_homes)
* A script that displays all users and their home directories, sorted by users.
---
[100-empty_casks](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/100-empty_casks)
* Write a command that finds all empty files and directories in the current directory and all sub-directories.
  - Only the names of the files and directories should be displayed (not the entire path)
  - Hidden files should be listed
  - One file name per line
  - The listing should end with a new line
  - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep` 
---
[101-gifs](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/101-gifs)
* A script that lists all the files with a .gif extension in the current directory and all its sub-directories.
---
[102-acrostic](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/102-acrostic)
* A script that decodes acrostics that use the first letter of each line.

  - The ‘decoded’ message has to end with a new line
  - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`
---
[103-the_biggest_fan](https://github.com/SKENGMANE/alx-system_engineering-devops/blob/master/0x02-shell_redirections/103-the_biggest_fan)
* A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
  - Order by number of requests, most active host or IP at the top
  - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`
---
