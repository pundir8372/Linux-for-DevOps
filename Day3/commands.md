# Commands Studied on Day 3 🎉

### `uname`
- Reveals the system information (e.g., OS type, kernel version) 🌐
- A quick check-up on which system you're working with!

### `uptime`
- Shows how long the system has been up and running 🕰️
- Great to see how long your machine has been active!

### `who`
- Lists all users currently logged into the system 👥
- Check out who else is hanging around in the system!

### `whoami`
- Displays the username of the current user 🙋‍♂️
- A simple way to confirm your identity in the system!

### `which bash`
- Locates the path to the bash executable 📍
- Useful to know where bash resides in your system!

### `id`
- Provides user ID (UID), group ID (GID), and group memberships of the current user 🆔
- Get the details on your user's role and privileges!

### `sudo`
- Executes a command as the superuser ⚙️
- The key to accessing administrative powers on Unix-like systems!

### `sudo apt-get update`
- Updates package lists for upgrades and installations 🔄
- Keeps your package database up-to-date for the latest versions!

### `sudo apt-get install docker.io`
- Installs Docker using apt-get 🐳
- One command away from containerization power!

### `which docker`
- Locates the Docker executable, if installed ✔️
- Confirms Docker's presence on the system.

### `sudo apt remove docker.io`
- Uninstalls Docker from the system 🗑️
- When it's time to say goodbye to Docker (for now)!

### `sudo useradd -m jethalal`
- Creates a new user named "jethalal" and generates a home directory 🏠
- Welcome, Jethalal!

### `sudo passwd jethalal`
- Sets a password for the "jethalal" user 🔑
- Secure Jethalal's login with a password.

### `su jethalal`
- Switches to the "jethalal" user account 🔄
- Feel what it’s like to be Jethalal for a while.

### `cat /etc/passwd`
- Displays the `/etc/passwd` file, listing all user accounts 🗂️
- A good place to check user information and IDs.

### `sudo userdel jethalal`
- Deletes the "jethalal" user 🚫
- Farewell, Jethalal...

### `sudo groupadd devops`
- Creates a new group named "devops" 👨‍💻
- Forming a new team!

### `sudo gpasswd -a jethalal devops`
- Adds "jethalal" to the "devops" group 🔗
- Jethalal is now a proud member of DevOps!

### `sudo gpasswd -m iyer,tapu,bhide`
- Modifies group membership to add multiple users (here, iyer, tapu, and bhide) 👥
- Joining forces!

### `sudo gpasswd -M iyer,tapu,bhide tester`
- Sets the group tester to have only these users 👤
- Giving them exclusive tester access.

### `sudo groupdel tester`
- Deletes the "tester" group 🗑️
- Disbanding the tester team.

### `history`
- Displays a list of all previous commands in the session 📜
- A handy way to revisit your past actions.

---

### `cd linux_for_devops`
- Changes the directory to `linux_for_devops`.

### `ls -l`
- Lists files in the current directory with detailed information, including permissions and ownership.

### `chmod 777 cloud`
- Changes permissions of the `cloud` directory to read, write, and execute for all users.

### `chmod 700 devopsFile.txt`
- Restricts `devopsFile.txt` permissions to read, write, and execute for the owner only.

### `umask`
- Displays the current default permission mask for newly created files.

### `sudo chown jethalal demoFile.txt`
- Changes the owner of `demoFile.txt` to user `jethalal`.

### `sudo chgrp devops demoFile.txt`
- Changes the group ownership of `demoFile.txt` to `devops`.

### `sudo apt install zip`
- Installs the `zip` utility if not already installed.

### `which zip`
- Locates the `zip` executable, confirming its installation.

### `zip -r ldf.zip linux_for_devops/`
- Compresses the `linux_for_devops` directory into a zip file named `ldf.zip`.

### `mkdir unzipped_files`
- Creates a directory named `unzipped_files`.

### `cp ldf.zip cloud/unzipped_files`
- Copies `ldf.zip` to the `cloud/unzipped_files` directory.

### `unzip ldf.zip`
- Extracts the contents of `ldf.zip` in the current directory.

### `scp`
- Securely copies files between the local machine and a remote server or between two remote servers.
  - Example: `scp file.txt user@remote_server:/path/to/destination`
  - Can be used to transfer files both from local to server and from server to local.

### `rsync`
- A powerful and efficient tool for syncing files and directories between two locations over SSH or on a local machine.
  - Example: `rsync -avz source_dir user@remote_server:/destination_dir`
  - Supports incremental sync, reducing data transfer by only copying changes.
