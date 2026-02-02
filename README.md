# linux-commands
### basic commands:
```
pwd->print working directory
```
```
mkdir->make directory     (creating only one directory)
```
```
 mkdir -vp a/b/c    (creating more than one directory at once)
```
```
ls->list
```
```
cd->change directory
```
```
 cd .. ->will move to the parent directory
```
```
cd -  -> will move you to the previous directory
```
```
touch ->touch command will create a new file or change time stamp of an existing file(updation).
```
```
dir -> is used to list directory contents.( dir is equivalent to ls -C -b)
```
```
clear-> terminal screen is cleared!!!
```
```
echo -> echo simply displays the text on the screen (syntax: echo "hello")
```
```
echo "hello" >> hello.txt-> create a hello.txt file and puts the text hello inside the file.
```
### cat
##### cat for reaing a file
```
cat filename.txt -> reads the file content
```
##### cat for combining two files:
```
cat file1.txt file2.txt > combined.txt
```
##### cat for creating a new file
```
cat > new.txt (press ctrl+d to save it)
```
 Reverse operation :

 displays the lines in reverse order.
 ```
tac hello.txt
```
###### bat
can  scroll automatically , shows syntax , clean and systematic..
```
bat hello.txt
```
##### head
head by default displays first 10 lines in a file
```
head hello.txt
```
if you want to print only first 2 lines : 
```
head -2 hello.txt
```
##### tail
tail  by default prints the last 10 lines in the file 
```
tail hello.txt
```
if you want to print the last 2 lines of the file :
```
tail -2 hello.txt
```
##### stat
shows the whole info about the file 
```
stat hello.txt
```
 to check the whole info about the directory :
 ```
stat dir1
```





