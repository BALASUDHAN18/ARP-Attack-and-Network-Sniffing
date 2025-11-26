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

<img width="773" height="429" alt="Screenshot 2025-11-26 215752" src="https://github.com/user-attachments/assets/e6ae3bd8-0560-49d4-afab-80eab06bdab6" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="783" height="511" alt="Screenshot 2025-11-26 215805" src="https://github.com/user-attachments/assets/d6e54f41-91c4-4d7c-a2f9-484007171c87" />

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


<img width="805" height="135" alt="Screenshot 2025-11-26 215811" src="https://github.com/user-attachments/assets/4db55c8e-04c7-4ae9-8d3b-e47cbbf9bf79" />


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="829" height="408" alt="Screenshot 2025-11-26 215824" src="https://github.com/user-attachments/assets/e1be4e66-04ad-413e-bb86-bdffad1001dc" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
