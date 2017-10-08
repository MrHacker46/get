# Info
- Get is a bash script to fast retrieve an ip from hostname or vice-versa.

# Screenshots
<img src="https://s1.postimg.org/3t7rshkdbz/get.jpg" width="30%"></img><img src="https://s1.postimg.org/8tulqv6zfj/image.jpg" width="30%"></img><img src="https://s1.postimg.org/4pbrsx86f3/image.jpg" width="30%"></img>

# About
- Get tool is still in development , some bugs may appear

# Requirements
- dnsutils
- wget (for updates)

- apt-get install dnsutils wget -y

# How to Install
- git clone https://github.com/peterpt/get.git 
- cd get && ./get

- On the first run , the script will install itself on /usr/local/sbin directory
- After that point just write (get) anywhere in terminal to run it

# How to Use

* To get the ip from a hostname :
- get -i google.com

* To get the hostname from an ip

- get -h 216.58.214.174
