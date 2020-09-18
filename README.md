# 2020-Hacking---Sandmap
🦑2020 Hacking 
simple CLI with the ability to run pure Nmap engine
predefined scans included in the modules
support Nmap Scripting Engine (NSE) with scripts arguments
TOR support (with proxychains)
multiple scans at one time
at this point: 31 modules with 459 scan profiles

🄸🄽🅂🅃🄰🄻🄻🄸🅂🄰🅃🄸🄾🄽 & 🅁🅄🄽 :

1) Clone this repository

git clone --recursive https://github.com/trimstray/sandmap

2) Go into the repository

cd sandmap

3) Install

./setup.sh install

4) Run the app

sandmap

🦑The etc/main.cfg configuration file has the following structure:

# shellcheck shell=bash

# Specifies the default destination.

# Examples:

#   - dest="127.0.0.1,8.8.8.8"

dest="127.0.0.1"

# Specifies the extended Nmap parameters.

# Examples:

#   - params="--script ssl-ccs-injection -p 443"

params=""

# Specifies the default output type and path.

# Examples:

#   - report="xml"

report=""

# Specifies the TOR connection.

# Examples:

#   - tor="true"

tor=""

# Specifies the terminal type.

# Examples:

#   - terminal="internal"

terminal="internal"
