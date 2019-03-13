# Installation

## Debian Installation
```
~ ❯❯❯ sudo apt-get update && sudo apt-get install nmap

~ ❯❯❯ git clone https://github.com/k4m4/kickthemout.git

~ ❯❯❯ cd kickthemout/

~/kickthemout ❯❯❯ sudo -H pip3 install -r requirements.txt

~/kickthemout ❯❯❯ sudo python3 kickthemout.py
```

## MacOS Installation
```

~ ❯❯❯ brew install libdnet nmap

~ ❯❯❯ git clone https://github.com/k4m4/kickthemout.git

~ ❯❯❯ cd kickthemout/

~/kickthemout ❯❯❯ sudo -H pip3 install -r requirements.txt

~/kickthemout ❯❯❯ sudo python3 kickthemout.py
```

**WICHTIG**: Du brauchst dafür Homebrew (http://brew.sh/) Installier das bevor du das programm installierst 

## ArchLinux Installation

```
~ ❯❯❯ git clone https://github.com/k4m4/kickthemout.git

~ ❯❯❯ cd kickthemout/

~/kickthemout ❯❯❯ sudo -H pip3 install -r requirements.txt

~/kickthemout ❯❯❯ sudo python3 kickthemout.py
```
####################################################################################################

# Verwendung
```
Usage: sudo python3 kickthemout.py [options]

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -p PACKETS, --packets=PACKETS
                        number of packets broadcasted per minute (default: 6)
  -s, --scan            perform a quick network scan and exit
  -t TARGETS, --target=TARGETS
                        specify target IP address(es) and perform attack

Examples:
  sudo python3 kickthemout.py --target 192.168.1.10 
  sudo python3 kickthemout.py -t 192.168.1.5,192.168.1.10 -p 30
  sudo python3 kickthemout.py (interactive mode)
```

# Um alle Optionen anzuzeigen:

```
~/kickthemout ❯❯❯ sudo python3 kickthemout.py -h
```
