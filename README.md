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
![WhatsApp Image 2024-10-20 at 20 45 12_2934b9b4](https://github.com/user-attachments/assets/f1951f29-8d7b-4863-9b06-ceee2545a795)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![WhatsApp Image 2024-10-21 at 09 23 12_abc0f04e](https://github.com/user-attachments/assets/40550f1c-1412-4d81-9561-e48bf574e579)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![WhatsApp Image 2024-10-20 at 20 45 11_5af44955](https://github.com/user-attachments/assets/08b8759c-3393-4a4e-b132-9d344bcb40f6)
![WhatsApp Image 2024-10-21 at 09 23 12_f453377e](https://github.com/user-attachments/assets/32eed6bb-3d4e-4a92-90a6-39831e58b77e)






In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![WhatsApp Image 2024-10-20 at 20 45 12_ec2f8bff](https://github.com/user-attachments/assets/5908e85c-5f53-41bb-a766-76c457b96aae)




Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
