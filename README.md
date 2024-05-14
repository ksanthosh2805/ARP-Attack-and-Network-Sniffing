# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![1 (1)](https://github.com/JAYAVARTHAN-P/ARP-Attack-and-Network-Sniffing/assets/121369281/17813182-76da-4fee-b66d-9399bfdad933)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2 (1)](https://github.com/JAYAVARTHAN-P/ARP-Attack-and-Network-Sniffing/assets/121369281/62cce3b9-2360-4057-a1aa-9d84caeefe8c)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/JAYAVARTHAN-P/ARP-Attack-and-Network-Sniffing/assets/121369281/1d89a1a7-15b4-4138-b391-603d6b6b4126)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![4](https://github.com/JAYAVARTHAN-P/ARP-Attack-and-Network-Sniffing/assets/121369281/825f5c97-dd28-417a-8fce-13af64cd53ad)


Invoke the wireshark and examine the various menus  and controls of the tool:
![5](https://github.com/JAYAVARTHAN-P/ARP-Attack-and-Network-Sniffing/assets/121369281/97b5d83b-c9c6-4d4c-9ae2-29deb150069b)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
