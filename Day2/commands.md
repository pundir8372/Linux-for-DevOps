# Day 2: Linux Commands

## Command History and Explanations

### Directory and File Management

- **Create a directory**:  
  `mkdir cloud`

- **List directory contents in detail**:  
  `ls -l`

- **Navigate into a directory**:  
  `cd devops/`

- **Return to the previous directory**:  
  `cd ..`

- **Print the current directory path**:  
  `pwd`

- **Create an empty file**:  
  `touch devops_file.txt`

- **Delete a file**:  
  `rm devops_file.txt`

- **Delete a directory and its contents**:  
  `rm -r cloud/`

- **Delete an empty directory**:  
  `rmdir devops/`

### Viewing and Editing Files

- **Create and view a file**:  
  `touch demoFile.txt`  
  `cat demoFile.txt`

- **Write text to a file**:  
  `echo "This is a second demo file" > demoFile2.txt`

- **View file contents**:  
  `cat demoFile2.txt`

- **Display the first lines of a file**:  
  `head myFile.txt`

### File Copying and Moving

- **Copy a file to another directory**:  
  `cp myFile.txt devops/`

- **Copy a directory with the recursive option**:  
  `cp -r cloud/ devops/`

- **Move a file to another directory**:  
  `mv myFile.txt ../cloud/`

### Symbolic Links

- **Create a symbolic link**:  
  `ln -s /home/ubuntu/linux_for_devops/cloud/devopsFile.txt softlink-file`

- **Remove a symbolic link**:  
  `rm softlink-file`

### Text Manipulation

- **Display selected bytes from each line**:  
  `cut -b 1-3 demoFile.txt`

- **Compare contents of two files**:  
  `diff demoFile.txt demoFile2.txt`

### Miscellaneous

- **Count words in a file**:  
  `wc fruits.txt`

- **View command history**:  
  `history`
