# terminalcolours
Read and write terminal colours on xterm and xfce4-terminal and friends by escape sequences

# Example usage

The `terminalcolours` command prints out the current settings in the form of a shell script that generates the escape sequences to set colour shades for the 16 popular colours. 

     ./terminalcolours 
    osc(){ echo -ne "\\e]$1\\a"; }
    osc  "4;0;rgb:2020/2020/2020"
    osc  "4;1;rgb:aaaa/0000/0000"
    osc  "4;2;rgb:0000/aaaa/0000"
    osc  "4;3;rgb:aaaa/5555/0000"
    osc  "4;4;rgb:0000/0000/aaaa"
    osc  "4;5;rgb:aaaa/0000/aaaa"
    osc  "4;6;rgb:0000/aaaa/aaaa"
    osc  "4;7;rgb:aaaa/aaaa/aaaa"
    osc  "4;8;rgb:5555/5555/5555"
    osc  "4;9;rgb:ffff/5555/5555"
    osc "4;10;rgb:5555/ffff/5555"
    osc "4;11;rgb:ffff/ffff/5555"
    osc "4;12;rgb:5555/5555/ffff"
    osc "4;13;rgb:ffff/5555/ffff"
    osc "4;14;rgb:5555/ffff/ffff"
    osc "4;15;rgb:ffff/ffff/ffff"
    osc   "10;rgb:dddd/dddd/dddd"
    osc   "11;rgb:0000/0000/0000"

