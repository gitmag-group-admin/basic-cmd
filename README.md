
## Command Line
**Operating system**

 - Graphical User Interface (GUI)
 - Command Line Interface (CLI)

**Commands**

 - Internal commands
 - External commands

Show help
```properties
$ cd /?
```
Navigate to `<directory>`
```properties
$ cd Desktop
```
Navigate to parent directory
```properties
$ cd ..
```
Navigate to drive 
```properties
$ cd /d <drive name>:
```
Lists all files and directories in the present working directory
```properties
$ dir
```
Lists all files and directories in `<directory>`
```properties
$ dir <directory>
```
List all with hidden files
```properties
$ dir /a
```
List all files by wildcard
```properties
$ dir *.jpg
```
Copy `<file>` to `<destination>`
```properties
$ copy <file> <destination>
```
Copy with wildcard
```properties
$ copy Desktop\*.jpg Desktop\pictures
```
Copy `<directory>`
```properties
$ xcopy /e .\picture\1 .\Desktop
```
Delete `<file>`
```properties
$ del <file>
```
Delete file by wildcard
```properties
$ del Desktop\*.jpg
```
Delete `<directory>`
```properties
$ rd Desktop\pictures
```
Delete `<directory>` with sub directories
```properties
$ rd /s Desktop\pictures
```
Make directory `<directory>` 
```properties
$ md <directory>
```
Move `<file/directory>`
```properties
$ move 1.jpg D:
```
Clear stdout
```properties
$ cls
```
Rename `<file/directory>`
```properties
$ rename 1.jpg 2.jpg
```
Shutdown computer
```properties
$ shutdown /s
```
Restart computer 
```properties
$ shutdown /r
```
Logoff computer
``````properties
$ shutdown /l
```
**System information**
```properties
$ systeminfo
```

