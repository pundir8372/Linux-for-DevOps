# Day 5 of Pro Linux Commands 🚀

Exploring awk, sed, and grep to efficiently handle and analyze log files!


Today was all about diving deep into log files and mastering data manipulation! 🕵️‍♂️ Let's explore the command adventure you embarked upon:

---

## 1. **Log File Viewing** 👀
Taking a peek inside the `app.log` file to start your log analysis journey.

- `vim app.log`  

*Explanation*: This command simply opens or inspects the `app.log` file. A humble but essential first step!

---

## 2. **Extracting Data with AWK** 🔍
AWK, the data extraction wizard, was in full force today!

- `awk '{print $1}' app.log`  
  *Extracting the first field from each line—like separating the wheat from the chaff!*

- `awk '{print $1 $3 $4}' app.log`  
  *Grabbing the 1st, 3rd, and 4th fields and joining them—data simplified!*

- `awk '/INFO/ {print $1,$3,$5}' app.log`  
  *Filtering lines with "INFO" and printing specific fields. You’re like a detective extracting clues!*

---

## 3. **Text Editing with SED** ✂️
SED, your stream editor friend, helping you slice, dice, and replace text.

- `sed '/INFO/p' app.log`  
  *Printing lines containing "INFO" twice (a playful duplication)!*

- `sed -n '/INFO/' app.log`  
  *A silent command that matches "INFO"—but does nothing unless you ask it nicely.*

- `sed -n '/INFO/p' app.log`  
  *Ah, now we’re printing only lines with "INFO," silently and efficiently!*

- `sed 's/INFO/LOG/g' app.log`  
  *Globally replacing "INFO" with "LOG"—a name change fit for a log entry!*

- `sed -n -e '/INFO/=' app.log`  
  *Showing line numbers for entries with "INFO"—like a table of contents for your clues.*

- `sed -n -e '/INFO/' -e '/INFO/p' app.log`  
  *Combining multiple conditions, really doubling down on "INFO"!*

- `sed -n -e '/INFO/=' -e '/INFO/p' app.log`  
  *Printing line numbers and the lines themselves—a true SED power move!*

- `sed '1,10 s/INFO/LOG/g' app.log`  
  *Replacing "INFO" with "LOG" only in the first 10 lines—because sometimes, less is more.*

---

## 4. **Searching with GREP** 🔦
GREP, your search-and-find hero, leaping through logs!

- `grep INFO app.log`  
  *Finding all lines containing "INFO." Straightforward and effective!*

- `grep -i info app.log`  
  *Case-insensitive search—because "INFO" doesn’t always shout in all caps.*

- `grep -i -c info app.log`  
  *Counting occurrences of "INFO," giving you the tally like a data scorekeeper.*

---

## 5. **Process Management with PS** ⚙️
Taking a peek at running processes and checking in on your friend, "ubuntu."

- `ps aux`  
  *Displaying all the running processes—like opening a window into your computer's soul.*

- `ps aux | grep ubuntu`  
  *Filtering for processes related to "ubuntu"—you’re a true process detective!*

---

## 6. **Reviewing Command History** 📜
Reflecting on your journey and triumphs.

- `history`  
  *A record of your successes and challenges—a true adventurer’s logbook!*

---

**Final Words**: You’ve leveled up your log parsing and text editing skills, all while battling the mysterious entries in `app.log`. Keep exploring and refining your command magic! 🌟

