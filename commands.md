# Day 4 of Networking Commands for Linux

It was an exciting and insightful Day 4, where you delved deeper into understanding and mastering various Linux networking commands. Let’s walk through your journey together!

---

## 1. **Ping Commands**
To check if a website is reachable and how fast you can communicate with it:

- `ping trainwithshubham.com`  
- `ping sahyogdehradun.netlify.app`  
- `ping google.com`  

*Explanation*: These `ping` commands are like sending a "hello" to a website to check if it's around and how quickly it can say "hello" back. Perfect for connectivity tests!

---

## 2. **Network Tools Installation and Usage**
Sometimes, we need to arm our terminal with powerful networking tools. Here's where things get serious!

- `sudo apt install net-tools`  
- `netstat`  
- `ifconfig`  
- `sudo apt install inetutils-traceroute`  
- `traceroute youtube.com`  
- `tracepath trainwithshubham.com`  

*Explanation*: `net-tools` gives you tools like `ifconfig` and `netstat` to inspect your network interfaces and connections. `traceroute` and `tracepath` are used to see the path your packets take across the internet. Who knew packets had such adventures?

---

## 3. **MTR (My Traceroute)**
When you want a detailed network path analysis:

- `mtr trainwithshubham.com`  
- `watch mtr trainwithshubham.com`  

*Explanation*: `mtr` combines the functions of `ping` and `traceroute`. It's like putting on special glasses to see the whole journey of your network traffic in real-time!

---

## 4. **Domain and Network Info**
Getting detailed information about a domain:

- `nslookup trainwithshubham.com`  
- `telnet trainwithshubham.com 80`  
- `hostname`  
- `cat /etc/hosts`  
- `ip address show`  

*Explanation*: `nslookup` fetches DNS records, while `telnet` checks if a port is open on a server (like knocking on a door). `hostname` tells your computer's name, and `cat /etc/hosts` reveals your local DNS settings.

---

## 5. **Wireless Configuration Tools**
To check your wireless settings and install necessary tools:

- `sudo apt install wireless-tools`  
- `iwconfig`  

*Explanation*: `iwconfig` is like `ifconfig` but for your wireless network. You’re now officially a wizard of WiFi!

---

## 6. **WHOIS Lookup**
Find registration details of a domain:

- `sudo apt install whois`  
- `whois trainwithshubham.com`  
- `whois google.com`  

*Explanation*: `whois` reveals ownership details about a domain. Like being an internet detective!

---

## 7. **ARP and Network Status**
Check and display network interface status:

- `arp`  
- `ifplugstatus`  
- `sudo apt install ifplugd`  
- `ifplugstatus`  

*Explanation*: `arp` shows IP-to-MAC address mappings. `ifplugstatus` checks if a network cable is plugged into an interface. We’re down to the physical layer here!

---

## 8. **API Testing with CURL**
Make a GET request to test APIs:

- `curl -X GET https://fake-json-api.mock.beeceptor.com/companies`  
- `curl -X GET https://fake-json-api.mock.beeceptor.com/companies | jq`  

*Explanation*: `curl` is a handy tool to make HTTP requests. `jq` formats JSON data beautifully. Even your API responses deserve some elegance!

---

## 9. **Downloading Files with WGET**
To download files from the web:

- `mkdir Downloads`  
- `cd Downloads`  
- `wget https://file-examples.com/wp-content/storage/2017/02/file-sample_100kB.doc`  
- `ls`  

*Explanation*: `wget` grabs files from URLs, and `ls` lists files in your current directory. Organizing your files never felt this good!

---

## 10. **NMAP for Network Exploration**
Check for open ports and services:

- `nmap -v trainwithshubham.com`  

*Explanation*: `nmap` scans networks to discover open ports. The `-v` flag adds verbosity. A treasure hunter’s map to the digital realm!

---

## 11. **Checking Routing and IP Info**
Get details on your network’s route and configuration:

- `route`  
- `ip address show`  

*Explanation*: `route` shows the kernel’s IP routing table, and `ip address show` lists all network interfaces. Pure network magic!

---

## 12. **Reviewing Command History**
Finally, view your past commands:

- `history`  

*Explanation*: Your `history` is a diary of your terminal adventures, from network troubleshooting to API calls.

---

**Final Words**: Day 4 was all about digging deeper into network commands, exploring connections, and understanding how your computer communicates with the world. Keep pushing forward, and who knows what you’ll discover next!

