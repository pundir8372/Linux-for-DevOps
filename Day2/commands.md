Day 2: Linux Commands
Create and List Directories
Create a directory:

bash
Copy code
mkdir cloud                # Creates 'cloud' directory
List files with details:

bash
Copy code
ls -l                      # Lists files with details
Navigating Directories
Change to 'devops' directory:

bash
Copy code
cd devops/                 # Changes to 'devops' directory
Print the current working directory:

bash
Copy code
pwd                        # Prints the current working directory
Move one directory up:

bash
Copy code
cd ..                      # Moves one directory up
Navigate to 'bin' directory:

bash
Copy code
cd bin                     # Navigates to 'bin' directory
Navigate to full path of 'devops':

bash
Copy code
cd /home/ubuntu/devops     # Navigates to full path of 'devops'
File Operations in Devops
Create an empty file named 'devops_file.txt':

bash
Copy code
touch devops_file.txt      # Creates an empty file named 'devops_file.txt'
Remove the file:

bash
Copy code
rm devops_file.txt         # Removes the file
Delete the 'cloud' directory:

bash
Copy code
rm -r cloud/               # Deletes the 'cloud' directory
Remove 'devops' directory if empty:

bash
Copy code
rmdir devops/              # Removes 'devops' directory if empty
Creating and Modifying Files
Create 'demoFile.txt':

bash
Copy code
touch demoFile.txt         # Creates 'demoFile.txt'
Display contents of 'demoFile.txt':

bash
Copy code
cat demoFile.txt           # Displays contents of 'demoFile.txt'
Add content to 'demoFile2.txt':

bash
Copy code
echo "This is a second demo file" > demoFile2.txt  # Adds content to 'demoFile2.txt'
Create 'myFile.txt':

bash
Copy code
touch myFile.txt           # Creates 'myFile.txt'
Add content to 'myFile.txt':

bash
Copy code
echo "This is my personal file" > myFile.txt       # Adds content to 'myFile.txt'
Copying and Moving Files Between Directories
Recreate 'devops' directory:

bash
Copy code
mkdir devops               # Recreates 'devops' directory
Copy 'myFile.txt' to 'devops':

bash
Copy code
cp myFile.txt devops/      # Copies 'myFile.txt' to 'devops'
Create 'devopsFile.txt' in 'devops':

bash
Copy code
touch devopsFile.txt       # Creates 'devopsFile.txt' in 'devops'
Copy 'cloud' directory into 'devops':

bash
Copy code
cp -r cloud/ devops/       # Copies 'cloud' directory into 'devops'
Rename Directory
Rename 'devops' to 'linux_for_devops':
bash
Copy code
mv devops/ linux_for_devops   # Renames 'devops' to 'linux_for_devops'
Word Count and Difference Check
Display contents of 'fruits.txt':

bash
Copy code
cat fruits.txt             # Displays contents of 'fruits.txt'
Count lines, words, and characters in 'fruits.txt':

bash
Copy code
wc fruits.txt              # Counts lines, words, and characters in 'fruits.txt'
Compare two files:

bash
Copy code
diff demoFile.txt demoFile2.txt   # Compares two files
Soft Link Operations
Create a symbolic link:

bash
Copy code
ln -s /home/ubuntu/linux_for_devops/cloud/devopsFile.txt softlink-file   # Creates a symbolic link
Display contents through soft link:

bash
Copy code
cat softlink-file          # Displays contents through soft link
Additional File Operations
Modify content of 'devopsFile.txt':

bash
Copy code
echo "This file was changed" > devopsFile.txt    # Modifies content of 'devopsFile.txt'
Display modified content:

bash
Copy code
cat devopsFile.txt         # Displays modified content
