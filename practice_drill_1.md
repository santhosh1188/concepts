# CLI practice drill1 

```bash ...
## Step 1: Create a directory and enter into it  
mkdir hello # making the directory 
cd hello # enter into the directory
## Step 2: creating the folders "-p" is used to create multiple folders
mkdir -p hello/{five/six/seven, one/two/three/four} 
## step 3: Creating filse inside folder
touch hello/five/six/c.txt
touch hello/five/six/seven/error.log
touch hello/one/a.txt hello/one/b.txt
touch hello/one/two/d.txt
touch hello/one/two/three/e.txt
touch hello/one/two/three/four/access.log

1. deleting all the files having .log extension
~/hello$ rm hello/five/six/seven/error.log
~/hello$ rm hello/one/two/three/four/access.log

2. Adding the content to a.txt using echo
~/hello$ echo "200~Unix is a family of multitasking, multiuser computer operating systems that derive from the original AT&T Unix, development starting in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, and others~"> a.txt

3. Delete the directory named five
~/hello$ rm -r hello/five

4. Rename the one directory to uno
~/hello$ mv hello/one hello/uno

5. move a.txt to the two directory 'here, we move from uno because we changed into uno and directly to two'
~/hello$ mv hello/uno/a.txt hello/two
