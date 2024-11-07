# Day 4 of Networking Commands for Linux 🎉

Wow, you've made it to Day 4! It's been an emotional rollercoaster of discovery, filled with powerful commands, troubleshooting victories, and just a bit of head-scratching confusion. Let's walk through the story of your day!

---

## 1. **Ping Commands** 🏓
Ah, the humble `ping`—your way of whispering into the void of the internet, hoping for a friendly "hello" back.

- `ping trainwithshubham.com`  
- `ping sahyogdehradun.netlify.app`  
- `ping google.com`  

*Explanation*: Using `ping` is like shouting across a canyon and hearing the echo. It helps you know that the connection is alive and how fast it can respond. Simple but oh-so-reassuring!

---

## 2. **Network Tools Installation and Usage** 🛠️
Suiting up your terminal with extra tools to conquer the world of networks!

- `sudo apt install net-tools`  
- `netstat`  
- `ifconfig`  
- `sudo apt install inetutils-traceroute`  
- `traceroute youtube.com`  
- `tracepath trainwithshubham.com`  

*Explanation*: Here, you were preparing for battle. `ifconfig` and `netstat` give you the power to see your computer's network setup. And `traceroute`? It’s like following a treasure map to your destination server, step by step. It’s thrilling to uncover the path your data takes! 🗺️

---

## 3. **MTR (My Traceroute)** 🚂
The high-tech way to visualize the wild journey of your packets across the web!

- `mtr trainwithshubham.com`  
- `watch mtr trainwithshubham.com`  

*Explanation*: Combining `ping` and `traceroute` into one mighty tool! Watching your packets’ journey unfold in real-time feels almost magical—like seeing the heartbeat of the internet itself. 💓

---

## 4. **Domain and Network Info** 🔍
Cracking open the mysteries of domains and digging deep into your network!

- `nslookup trainwithshubham.com`  
- `telnet trainwithshubham.com 80`  
- `hostname`  
- `cat /etc/hosts`  
- `ip address show`  

*Explanation*: `nslookup` is like lifting the hood of a car to understand how everything is connected. `telnet` is your old-school way of seeing if a door (port) is open. And finding your hostname? That's just your computer introducing itself with a proud "This is me!" 😌

---

## 5. **Wireless Configuration Tools** 📡
Time to handle your WiFi like a pro!

- `sudo apt install wireless-tools`  
- `iwconfig`  

*Explanation*: `iwconfig` tells you all about your wireless network setup. It’s like having x-ray vision into your WiFi world. Who knew configuring networks could feel so empowering? 💪

---

## 6. **WHOIS Lookup** 🕵️‍♂️
Become an internet detective and uncover hidden truths about domain ownership.

- `sudo apt install whois`  
- `whois trainwithshubham.com`  
- `whois google.com`  

*Explanation*: `whois` pulls back the curtain to reveal who owns a website. Sometimes, the internet feels like a big, mysterious place, but now you have the power to know exactly who's behind the domains! 🌐

---

## 7. **ARP and Network Status** 📈
Down to the nitty-gritty of IP and MAC addresses.

- `arp`  
- `ifplugstatus`  
- `sudo apt install ifplugd`  
- `ifplugstatus`  

*Explanation*: `arp` is like a backstage pass, showing how devices on your network talk to each other. And `ifplugstatus` checks if your network cable is happily connected. Because sometimes, even networks need a hug! 🤗

---

## 8. **API Testing with CURL** 🌐
Exploring APIs and fetching data with style.

- `curl -X GET https://fake-json-api.mock.beeceptor.com/companies`  
- `curl -X GET https://fake-json-api.mock.beeceptor.com/companies | jq`  

*Explanation*: Using `curl` is like sending a polite request to a server, asking for information. And `jq`? It's the cherry on top, making sure the data looks pretty. You’re now an API whisperer! 💬

---

## 9. **Downloading Files with WGET** 📥
The thrill of fetching files from the internet!

- `mkdir Downloads`  
- `cd Downloads`  
- `wget https://file-examples.com/wp-content/storage/2017/02/file-sample_100kB.doc`  
- `ls`  

*Explanation*: `wget` is your trusted friend for grabbing files. Creating a `Downloads` folder feels like tidying up your digital space—ah, the joy of being organized! 🗂️

---

## 10. **NMAP for Network Exploration** 🕵️‍♀️
Scanning the digital seas to discover open ports and services.

- `nmap -v trainwithshubham.com`  

*Explanation*: `nmap` is the ultimate tool for network exploration, like being a pirate with a treasure map, but instead of gold, you’re finding open ports. The `-v` flag makes sure every detail is captured. Exciting, isn't it? 🏴‍☠️

---

## 11. **Checking Routing and IP Info** 🚦
Get a glimpse into your network's route and IP configuration.

- `route`  
- `ip address show`  

*Explanation*: `route` shows the path your data takes, while `ip address show` lists all your network interfaces. It’s like understanding how traffic flows in your very own city! 🚗

---

## 12. **Reviewing Command History** 📜
Taking a moment to reflect on your journey.

- `history`  

*Explanation*: Ah, the `history` command. It’s your diary of everything you’ve accomplished, every hurdle you’ve crossed, and every victorious moment! 🎉

---

**Final Words**: Day 4 was packed with adventure, mystery, and some mind-blowing discoveries. You’ve come so far on your networking journey—keep going, and who knows what you'll conquer next? The internet has many secrets left for you to uncover! 🚀

