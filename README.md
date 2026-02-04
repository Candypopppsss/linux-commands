# linux-commands
### basic commands:

#### pwd 
it is print working directory
```
pwd
```
#### mkdir
it is make directory ... 
1. for creating one directory .

```
mkdir dir1
```
2. for creating  multiple directories.
```
 mkdir -vp a/b/c    
```
#### ls
to list out the contents.
```
ls
```
#### cd
to chhange the directory.

```
cd
```
to move to the parent directory.
```
 cd .. -
```
to move to the previous directory.
```
cd -  
```
#### touch
touch will create a new file or change time stamp of an existing file(updation).
```
touch 
```
#### dir
 it is used to list directory contents...(works equivalent to ls -C -b)
```
dir 
```
#### clear 
yayyy terminal screen is cleared!!!
```
clear
```
#### echo 
echo simply  displays the text on the screen .
```
echo "hello"
```
for inserting a text into a file:
```
echo "hello" >> hello.txt
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
bat only works if it is installed on your linux:
for installation :
```
sudo apt install bat
```
then run this command:
```
bat hello.txt
```
in debian the syntax is different 
```
batcat hello.txt
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
##### du 
du -> disk usage ... it will basically display disk usage
```
du
```
 to  make it into a human understandable output we can just run the below command   
 where h is to humanize and x is to switch and exclude other files

 ```
du -xh ~
```
sometimes du can take alot of time so we use max.depth

```
du --max-depth 3 ~
```
##### cp 
this command is used to copy the content from one file to another file 
```
cp dir1 dir2
```
the only thing which we should remember while running the command cp is  both the source and the destination should be present in the command line

##### md5sum
```
md5sum hello.txt
```
 this command will give a calculated checksum for a file.This helps with detecting accidental or deliberate file corruption.
 ##### mv
  this command   moves the file  form one dir to another dir
  ```
mv one two
```
##### ln
this command is used to create the link 
```
ln
```
##### rm -rf
this command is used to delete any directory  whether it is an empty one or non-empty one..
```
rm -r dir1
```
 for removing a directory there is also another  command.. 
 ```
rmdir dir1
```

##### tree
 tree command in linux basically gives you the  tree   for all the directories present...
 ```
tree
```
 #### ln 
 ln means link
 this command  gives a symbolic link...
 this specific command line is used to create a link for your directory..
 ```
ln -s dir1 softlink
```
now type the below command to access it and see the attributes
```
stat softlink
```


 






