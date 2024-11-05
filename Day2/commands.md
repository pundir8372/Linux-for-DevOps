# Create and list directories
mkdir cloud                # Creates 'cloud' directory
ls -l                      # Lists files with details

# Navigating directories
cd devops/                 # Changes to 'devops' directory
pwd                        # Prints the current working directory
cd ..                      # Moves one directory up
cd bin                     # Navigates to 'bin' directory

# File operations in devops
cd /home/ubuntu/devops     # Navigates to full path of 'devops'
touch devops_file.txt      # Creates an empty file named 'devops_file.txt'
rm devops_file.txt         # Removes the file
rm -r cloud/               # Deletes the 'cloud' directory
rmdir devops/              # Removes 'devops' directory if empty

# Creating and modifying files
touch demoFile.txt         # Creates 'demoFile.txt'
cat demoFile.txt           # Displays contents of 'demoFile.txt'
echo "This is a second demo file" > demoFile2.txt  # Adds content to 'demoFile2.txt'
touch myFile.txt           # Creates 'myFile.txt'
echo "This is my personal file" > myFile.txt       # Adds content to 'myFile.txt'

# Copying and moving files between directories
mkdir devops               # Recreates 'devops' directory
cp myFile.txt devops/      # Copies 'myFile.txt' to 'devops'
touch devopsFile.txt       # Creates 'devopsFile.txt' in 'devops'
cp -r cloud/ devops/       # Copies 'cloud' directory into 'devops'

# Rename directory
mv devops/ linux_for_devops   # Renames 'devops' to 'linux_for_devops'

# Word count and difference check
cat fruits.txt             # Displays contents of 'fruits.txt'
wc fruits.txt              # Counts lines, words, and characters in 'fruits.txt'
diff demoFile.txt demoFile2.txt   # Compares two files

# Soft link operations
ln -s /home/ubuntu/linux_for_devops/cloud/devopsFile.txt softlink-file   # Creates a symbolic link
cat softlink-file          # Displays contents through soft link

# Additional file operations
echo "This file was changed" > devopsFile.txt    # Modifies content of 'devopsFile.txt'
cat devopsFile.txt         # Displays modified content
