# devops-project

**************linux***********************

linux
kernel
shell
utilites 
file system
#kernel = using kernel process managment, serice management, package managment, device management,  
boot loading
grub : linux boot loader

#shell commands
#uname
ls - list of files in deyirectory
ls -a hidden files in dir
pwd - present dir
cd / dir name
/bin 
cd / usr
pwd
cd ..
touch file name
ls -l
mkdir  temp
rm filename
rm dir 
rm -r dir name will delete with files
#copy 
cp test temp
rsymc  same as cp
cp file name / dir
mv command we can user for rename 
for view #cat
VI for edit
line number cat -n file path 
#filter
based number
head top 10
tail last 10
head -n number line 5 file path
tail -n nuber line 5 file path
search in file 
grep command  
/etc /path 
grep word filename 
curl 
awk -- col base filter
free -  to check memory 
awk -F 'delimiter' '{print $column-number}' <filename>
root 
awk -F 'delimiter' '{print $column-number}' <filename>
awk -F : '{print $1}' /etc/passwd
aws -f : '{print $1,$2 }' /etc/passwd
*******Editors*********
we use in linux VI editor
Vi test.txt
inset  I
esc :q! - without save
wsc:wq! - save
SED editor - we will use for automation
serch and replace
add/modify line
delete line
-i to edit 
sed -i 's|WORD1|WORD2|' file
sed -i 's|root|ADMIN|g' passwd in single line search and replce
sed -i 's|root|ADMIN|i' passwd case senstive - in senstive
sed '1 i Hello World' passwd  to insert
sed '1 a Hello World' passwd  to add
sed '1 c Hello World' passwd  to change
 delete line 
 sed '10 d' passwd
sed -e '1 d' -e '10 a Hello' -e 's|root|ADMIN|' passwd
 sed '2,5d' filename | grep "pattern"
## tar command to tar the file
 tar -xf <filename>.tar.gz
 unzip format
 unzip filename
 cat filename | grep root
 xargs -- need to search 
*****************process mgt******************
pid - process 
ps command to know the process
ps -u  with username it will show th eprocess
ps -e 
process id and name
ps -ef
ts-f | grep ssh
how to kill process
kill command
kill processid
kill -9 processid - force kill
sudo user -
root user   - 
sso enabled normally for us
if we required all access we need to use sudo we will 
