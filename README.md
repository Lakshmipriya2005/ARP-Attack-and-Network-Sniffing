# EXP.NO:04
# DATE:

# ARP-Attack-and-Network-Sniffing
Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/Lakshmipriya2005/ARP-Attack-and-Network-Sniffing/assets/115525361/14212209-b51a-47ee-9ab3-e05009bb10c5)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/Lakshmipriya2005/ARP-Attack-and-Network-Sniffing/assets/115525361/a3ef8488-052e-45f4-b0d0-1abece0d9374)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Lakshmipriya2005/ARP-Attack-and-Network-Sniffing/assets/115525361/2c3be7e8-6f7b-4989-8b31-fdb1ca13cb91)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Lakshmipriya2005/ARP-Attack-and-Network-Sniffing/assets/115525361/f8586211-838c-44d2-8f5c-b5847dd508d7)




Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
