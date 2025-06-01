# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
# Name:kaushik k

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
# ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot (143)](https://github.com/user-attachments/assets/b553011b-dba5-4e18-bf42-e0c5d15014ae)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![Screenshot (144)](https://github.com/user-attachments/assets/c5223bbd-caba-42cd-b14c-fe1ae988e143)

#  dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot (145)](https://github.com/user-attachments/assets/b5ac3eac-6acd-4149-9906-227116ce86ee)


In Kali issue the following commands:
# sudo dsnifff
## OUTPUT:

![Screenshot (146)](https://github.com/user-attachments/assets/686da132-16b5-462c-894f-599e5216fa2d)


# Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot (147)](https://github.com/user-attachments/assets/d6ca76d4-35c8-4e41-8702-dcfa184c980c)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
