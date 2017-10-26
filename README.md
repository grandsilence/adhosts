# Adhosts
Hosts for blocking advert, adware and malware

# Install

## On Unix systems (Linux, MacOS)
Copy file **hosts** with replacing
```/etc/hosts```

## On Windows
### Step 1
Before copy you must remove this 4 lines:
```
127.0.0.1    localhost
255.255.255.255 broadcasthost
::1      localhost 
fe80::1%lo0  localhost
```
### Step 2
Copy file **hosts** with replacing
```%windir%\System32\drivers\etc\``` OR ```C:\Windows\System32\drivers\etc\```

# Host sources
1. Personal russian ads
2. [Unified hosts = adware + malware](https://github.com/StevenBlack/hosts)