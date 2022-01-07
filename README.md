# BashCheatSheet
I'm writting my note about the bash command here  
## Used  
Learn Bash Scripting by Building Five Programs From freeCodeCamp  

  
## Notes  
### Basic  
```echo hello world``` => Show hello world to the console  
```echo text >> filename``` => Write inside a file  
```pwd``` => print working directory (print the tree)  
```ls``` => show the elements inside the folder  
```ls <flag>``` => show the elements in a different way  
```ls -l``` => show the elements inside the folder by long list format  
```ls -a || ls --all``` => show all the files inside the folder  
```cd directoryName``` => change directory  
```cd ..``` => go one directory back  
```cd ../..``` => go 2 directory back  
```more fileName``` => see the elements inside the file  
```clear``` => clear the terminal  
```mkdir <folder name>``` => make directory === create a new folder  
```touch <file name>``` => create a file => dont forget the extension  
```command --help``` => show the help for the command to see more about what can do the command  
```cp <file> <destination>``` => copy the file to an other folder  
```cp -R, -r, --recursive <folder name>``` => copy the folder and everything inside  
```rm <file>``` => remove the file  
```mv <filename> <new_filename>``` => change the file name  
```mv <filename> destination``` => we can also use mv to move a file  
```find``` => used to view the file tree of the website folder to see all the files and folders withing it  
```find <folder name>``` => same but can select a folder  
```find -name <file name>``` => look for a filde path  
```mv <file name> ..``` => to move to the upper folder  
```rmdir <folder name>``` => remove a directory/folder  
```rm -r <folder name>``` => remove the folder and all the content inside it . Attention, we can't reverse it !!!  
```exit``` => exit terminal  
```sed -i 'nd' <filename>``` => Delete the n line from a file ex: ```sed -i '1d' questionnaire.sh``` 
```sed -i '$d' <filename>``` => Delete the last line from a file ex: ```sed '$d' questionnaire.sh```  
```sed '7,9d' <filename>``` => Delete line 7 to 9 from a file  
```VARIABLE_NAME=VALUE``` => create a variable with a value. If you need to add a space, you need to add double quote
### Scripting  
```sh```=> stand for shell. Use this extension to write shell script  
```sh questionnaire.sh``` => use this to run the file questionnaire.sh  
```bash questionnaire.sh```=> same as above, it run the file questionnaire.sh  
```which bash```=> find where the bash is located, this is the absolute path to the bash interpreter   
```#!<path_to_interpreter>```=> add a shebang to tell the program to use a certain bash ex: if response to where bash == ```/usr/bin/bash``` the shebang will be ```#!/bin/bash```  
```./<filename>```=> if there is a shebang at the first line, we can run the file directly  
```-rw-r--r--``` => if while doing ls -l we get this, this describe the permissions that differents users have. r => read, w => write, x => execute  
```chmod +x questionnaire.sh```=> give everyone permission to execute script questionnaire.sh 
