# Day 2: Linux Commands

## Command History and Explanations

### Directory and File Management

- **Create a directory**:
  ```bash
  mkdir cloud
List directory contents in detail:

bash
Copy code
ls -l
Navigate into a directory:

bash
Copy code
cd devops/
Return to the previous directory:

bash
Copy code
cd ..
Print the current directory path:

bash
Copy code
pwd
Create an empty file:

bash
Copy code
touch devops_file.txt
Delete a file:

bash
Copy code
rm devops_file.txt
Delete a directory and its contents:

bash
Copy code
rm -r cloud/
Delete an empty directory:

bash
Copy code
rmdir devops/
Viewing and Editing Files
Create and view a file:

bash
Copy code
touch demoFile.txt
cat demoFile.txt
Write text to a file:

bash
Copy code
echo "This is a second demo file" > demoFile2.txt
View file contents:

bash
Copy code
cat demoFile2.txt
Display the first lines of a file:

bash
Copy code
head myFile.txt
File Copying and Moving
Copy a file to another directory:

bash
Copy code
cp myFile.txt devops/
Copy a file with recursive option (for directories):

bash
Copy code
cp -r cloud/ devops/
Move a file to another directory:

bash
Copy code
mv myFile.txt ../cloud/
Symbolic Links
Create a symbolic link:

bash
Copy code
ln -s /home/ubuntu/linux_for_devops/cloud/devopsFile.txt softlink-file
Remove a symbolic link:

bash
Copy code
rm softlink-file
Text Manipulation
Display selected bytes from each line:

bash
Copy code
cut -b 1-3 demoFile.txt
Compare contents of two files:

bash
Copy code
diff demoFile.txt demoFile2.txt
Miscellaneous
Count words in a file:

bash
Copy code
wc fruits.txt
View command history:

bash
Copy code
history

