# Day 2: Linux Commands 🌟

## Command History and Explanations

### Directory and File Management 📂

- **Create a directory**:  
  `mkdir cloud`  
  (Creating a new directory feels like building a new room in your house! 🏠)

- **List directory contents in detail**:  
  `ls -l`  
  (Getting a detailed look at what's inside the folder, like peeking into your closet! 👀)

- **Navigate into a directory**:  
  `cd devops/`  
  (Diving into the 'devops' folder, like entering a new adventure! 🧭)

- **Return to the previous directory**:  
  `cd ..`  
  (Backtracking to the previous folder, kind of like retracing your steps! 🔄)

- **Print the current directory path**:  
  `pwd`  
  (Finding out where you are, like checking your location on a map! 🗺️)

- **Create an empty file**:  
  `touch devops_file.txt`  
  (Making a new file is like getting a fresh canvas to work on! 🎨)

- **Delete a file**:  
  `rm devops_file.txt`  
  (Saying goodbye to a file, like clearing out old papers! 🗑️)

- **Delete a directory and its contents**:  
  `rm -r cloud/`  
  (Clearing out a directory completely, like decluttering a room! 🚪)

- **Delete an empty directory**:  
  `rmdir devops/`  
  (Removing an empty space, like tidying up after yourself! ✨)

### Viewing and Editing Files 📄

- **Create and view a file**:  
  `touch demoFile.txt`  
  `cat demoFile.txt`  
  (Creating and checking out a new file, like writing and reading your journal! 📖)

- **Write text to a file**:  
  `echo "This is a second demo file" > demoFile2.txt`  
  (Writing something new feels empowering! ✍️)

- **View file contents**:  
  `cat demoFile2.txt`  
  (Reading what you just wrote, like reflecting on your thoughts! 💭)

- **Display the first lines of a file**:  
  `head myFile.txt`  
  (Peeking at the beginning of a file, like the first page of a book! 📚)

### File Copying and Moving 📦

- **Copy a file to another directory**:  
  `cp myFile.txt devops/`  
  (Making a duplicate file feels like having a backup buddy! 👯)

- **Copy a directory with the recursive option**:  
  `cp -r cloud/ devops/`  
  (Bringing everything along, like packing for a trip! 🧳)

- **Move a file to another directory**:  
  `mv myFile.txt ../cloud/`  
  (Relocating a file is like changing homes for your favorite belongings! 🏡)

### Symbolic Links 🔗

- **Create a symbolic link**:  
  `ln -s /home/ubuntu/linux_for_devops/cloud/devopsFile.txt softlink-file`  
  (Creating a shortcut feels like finding a secret passage! 🗝️)

- **Remove a symbolic link**:  
  `rm softlink-file`  
  (Clearing out a shortcut, like closing a door to an unused path! 🚪)

### Text Manipulation 🔤

- **Display selected bytes from each line**:  
  `cut -b 1-3 demoFile.txt`  
  (Extracting specific parts feels like highlighting important notes! 📌)

- **Compare contents of two files**:  
  `diff demoFile.txt demoFile2.txt`  
  (Spotting the differences is like finding the contrasts in two paintings! 🎨)

### System Monitoring and Management 🖥️

- **Check disk space usage**:  
  `df`  
  (Understanding disk space feels like checking your wallet! 💰)

- **Check disk space usage in human-readable format**:  
  `df -h`  
  (Seeing disk usage clearly is like reading a price tag! 🏷️)

- **Check disk usage of the current directory**:  
  `du .`  
  (Evaluating how much space you're using, like checking your storage box! 📦)

- **Clear the terminal screen**:  
  `clear`  
  (Refreshing the screen is like wiping the slate clean! 🧼)

- **Display real-time system processes**:  
  `top`  
  (Watching system activity in real-time is like observing a busy marketplace! 🏬)

- **Display current processes**:  
  `ps`  
  (Listing running processes feels like making a to-do list! 📝)

- **Identify which process is using a specific file**:  
  `fuser .`  
  (Finding out what's using a file is like detective work! 🕵️)

- **Kill a process by its ID**:  
  `kill -9 122`  
  (Terminating a process is like shutting down a malfunctioning machine! 🔌)

- **Check memory usage**:  
  `free`  
  (Getting a memory check is like evaluating your mental bandwidth! 🧠)

- **Check memory usage in human-readable format**:  
  `free -h`  
  (Understanding memory usage clearly feels refreshing! 💧)

- **Run a command and ignore hangup signals**:  
  `nohup free -h`  
  (Running in the background feels like multitasking! 🔄)

- **View the output of the last nohup command**:  
  `cat nohup.out`  
  (Checking past outputs is like looking back at your notes! 📒)

- **Run a command with nohup and display output**:  
  `nohup df -h`  
  (Running commands while you’re busy is like having an assistant! 🤖)

- **View the output of the last nohup command again**:  
  `cat nohup.out`  
  (Going back to read what happened before feels like revisiting a memory! 🕰️)

- **Display the first 5 lines of the nohup output**:  
  `head -n 5 nohup.out`  
  (Previewing outputs is like getting a sneak peek of a movie! 🎬)

- **Display virtual memory statistics**:  
  `vmstat`  
  (Monitoring system performance feels like checking your health stats! 🏥)

### Miscellaneous 🗂️

- **Count words in a file**:  
  `wc fruits.txt`  
  (Counting words feels like counting your blessings! 🙏)

- **View command history**:  
  `history`  
  (Reflecting on what you’ve done is like looking back at your journey! 🛤️)
