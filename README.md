# subnetting_basic_info
Script in bash to obtain Network mask, network ID and broadcast address based on ip and mask.

It uses the web "https://jodies.de/ipcalc" to get all the information and then filter and present the information in the terminal.

To use the script, follow the steps below:
1) Copy the script, save it and give it execution permissions (chmod +x filename.sh)

2) from the terminal, run the script, followed by the ip and the mask, separated by commas:
-> filename.sh 192.168.0.1 24

All the information is presented in a user-friendly way in the terminal.

-> [+] Address: 192.168.0.1 | Mask: 24
    
    	[+] Network Mask: 255.255.255.0
    	[+] Network ID: 192.168.0.0
    	[+] Broadcast Address: 192.168.0.255

 
[!] The script does not consider any error or alert in case the ip or the port are not introduced in a correct way.
Feel free to update it.

Enjoy!
