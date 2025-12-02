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
<img width="720" height="400" alt="image" src="https://github.com/user-attachments/assets/6f001bf0-7d7f-4aca-b24f-83df29b38d8b" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="876" height="684" alt="image" src="https://github.com/user-attachments/assets/e4d1e216-61b8-4357-ad4b-549338263672" />

### dsniff:
<img width="853" height="840" alt="image" src="https://github.com/user-attachments/assets/9b9fcb37-d792-4da5-ad0c-5aff6013f597" />







In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="634" height="290" alt="image" src="https://github.com/user-attachments/assets/851279da-a2ce-4ae8-9ead-95a3571f5e7f" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="387" height="40" alt="image" src="https://github.com/user-attachments/assets/c9a921f7-7d43-4781-a9b6-dc59c39dc2d3" />



Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1501" height="773" alt="image" src="https://github.com/user-attachments/assets/6bd3422d-d1aa-40cb-b9cd-cbae9c94fd64" />


ettercap
<img width="818" height="476" alt="image" src="https://github.com/user-attachments/assets/e04afa4b-16fe-4850-affc-a7ef164d1104" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
