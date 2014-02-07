# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__mv file newfile:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__cp fileToCopy Tothisfile:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---
__rm__ -_remove file and directories_

__rm folder:__
```
```
---
__rmdir__-_remove empty directories_
__rmdir directorietoRemove:__
```
```
---
__ln -s__-_make links between files('-s'make symbolic links instead of hard links)
__ln -s foler1 folder2:__
```
```
---
__scp__-_secure copy (remote file copy program)_
__scp folder newclone:__
```
```
---
__pwd__-_print name of current/working directory_
__pwd:__
```
$pwd
/home/student/habdi
```
---
__ls__-_list_
__ls:__
```
$ls -b
prints out all folders that with 'b'
```
---
__tar__-_The GNU version of the tar archiving utility_
__ :__
```
tar [-] A --catenate --concatenate | c --create | d --diff --compare | --delete | r --append | t --list 
```
---
## File Transfer

__curl__-_transfer a URL_
__curl blank tothisblank__
```
```
---
__wget__The non-interactive network downloader_
__wget blank:__
```
```
---
__scp__-_secure copy (remote file copy program)_
__scp folder newclone:__

```
```
---
__rsync__-_a fast, versatile, remote (and local) file-copying tool_
__rsync folderToCopy newfolder:__
```
```
---
## Pipe tools
```
```
__cat__-_concatenate files and print on the standard output_
__cat fileToPrint:__
```
```
---
__sort__-_sort lines of text files_
__sort fileToSort:__
---
__uniq__-_report or omit repeated lines_
__uniq folder:__
```
```
---
__grep__-_print lines matching a pattern_
__grep b folderTolookIn:__
```
$grep 5 folder1
5565
```
