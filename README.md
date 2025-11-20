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
<img width="704" height="494" alt="image" src="https://github.com/user-attachments/assets/0f328397-9581-4c08-b3b5-3b4ccae2a7af" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="689" height="270" alt="image" src="https://github.com/user-attachments/assets/1f4709dc-06bd-4518-a1a9-0c7f3f4c132c" />


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="622" height="601" alt="image" src="https://github.com/user-attachments/assets/d186b130-c5de-4b77-8e40-b42f95d36939" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1918" height="871" alt="image" src="https://github.com/user-attachments/assets/db4abbbe-093b-4835-9c51-45378e350348" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
