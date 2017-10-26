# Adhosts
Hosts for blocking advert, adware and malware

# Install

## On Unix systems (iOS, Android, MacOS, Linux)
Copy file **hosts** with replacing
```/etc/hosts```

You also can do it via **bash**: ```yes | sudo cp -rf hosts /etc/hosts```

## On Windows
### Step 1
Before copy you **must remove this 4 lines** (it's hardcoded DNS Microsoft services):
```
127.0.0.1    localhost
255.255.255.255 broadcasthost
::1      localhost 
fe80::1%lo0  localhost
```
### Step 2
Copy file **hosts** with replacing
```%windir%\System32\drivers\etc\hosts``` OR ```C:\Windows\System32\drivers\etc\hosts```

You also can do it via **cmd with Admin rights**: ```xcopy /y hosts %windir%\System32\drivers\etc\hosts```

# Host sources
1. Personal russian ads
2. [Unified hosts = adware + malware](https://github.com/StevenBlack/hosts)

# How to join your hosts to this one?
Use my software: [HostsMerger](https://github.com/grandsilence/hostsmerger)