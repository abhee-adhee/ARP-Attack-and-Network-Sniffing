# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

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
<img width="750" height="603" alt="image" src="https://github.com/user-attachments/assets/b3afe3ae-91af-4739-adcd-99ec40a42898" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="847" height="692" alt="image" src="https://github.com/user-attachments/assets/83454e09-7379-4548-9f21-f37b42b20032" />


 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="1914" height="807" alt="image" src="https://github.com/user-attachments/assets/360143de-6693-495f-a00e-f80cc7948715" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="322" height="122" alt="image" src="https://github.com/user-attachments/assets/a90d8c63-8205-441e-9a7e-ab08da87e268" />



Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1917" height="996" alt="image" src="https://github.com/user-attachments/assets/75789902-8baf-4f27-bba1-8745a179bf8c" />




## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
