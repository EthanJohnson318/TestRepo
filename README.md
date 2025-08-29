## Lab 01

- Name: Ethan Johnson
- Email: johnson.1998@wright.edu

## Part 1 - GitHub Profile

1. [EthanJohnson318's GitHub Profile](FIXTHISURL-https://github.com/EthanJohnson318)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | This command displays a page that defines the command and its functions       |
| Get-Location | pwd    | Prints the current working directory       |
| Get-ChildItem | ls    | Lists the contents of the working directory       |
| mkdir   | mkdir       | Creates a new directory as a child of the working directory       |
| Set-Location | cd     | Changes working directory       |
| New-Item | touch      | Creates a new file in the working directory       |
| Move-Item | mv        | Moves a file from one directory to another       |
| Copy-Item | cp        | Makes a copy of a file into another directory       |
| Remove-Item | rm      | Removes a file from the working directory       |
| notepad.exe | vim     | Opens a text editor       |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [x] Linux
- [] Mac

My Command Line Shell is: Bash

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: /mnt/c/Users/ejohn (Using WSL with Ubuntu)
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir "Dir B"
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd ../"Dir B"
6. Return to your user's home directory: cd .. (cd ~ would unmount me from my home directory in WSL)
7. Create a file named `test.txt`: vim test.txt
8. Move the file named `test.txt` into `DirA`: mv test.txt DirA
9. Contents of `test.txt`:
```
Hello World!
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp test.txt copy.txt
11. View the contents of `DirA`: ls
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp test.txt ../"Dir B"/fodder.txt
13. Delete / remove both `fodder.txt` AND `Dir B`: rm -r ../"Dir B" (Removes directories and their contents recursively, which includes the directory "Dir B" and the fodder.txt file)

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

1. Man Pages - Helped described actions
