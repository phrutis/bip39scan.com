# bip39scan v2.0.1 POOL - $500
To purchase, write to telegram @phrutis or buy from a bot in a group t.me/cuda8

<img width="1308" height="604" alt="Image" src="https://github.com/user-attachments/assets/774fea06-09ad-4213-921b-14c055978a20" />

Online Statistic https://bip39scan.xyz<br>
You can check how the client works (for test)<br>
### Linux:
wget https://github.com/phrutis/bip39scan_v2_POOL/releases/download/2.0.1/xx<br>
wget https://github.com/phrutis/bip39scan_v2_POOL/releases/download/2.0.1/precomp.bin<br>
wget https://github.com/phrutis/bip39scan_v2_POOL/releases/download/2.0.1/libcrypto-1_1-x64.dll (Needed if the library is not installed)<br>
```chmod +x xx```<br>
```./xx -u YourNickName```<br>
### Windows:
https://github.com/phrutis/bip39scan_v2_POOL/releases/download/2.0.1/xx.exe<br>
https://github.com/phrutis/bip39scan_v2_POOL/releases/download/2.0.1/precomp.bin<br>
https://github.com/phrutis/bip39scan_v2_POOL/releases/download/2.0.1/libcrypto-1_1-x64.dll (Needed if the library is not installed)<br>
```xx.exe -u Nick_Name```<br>

Pool for collective search of vulnerable passwords instead of mnemonic phrases.<br>
The pool has a page with general client statistics. (see screenshot above)<br>
The top clients are formed by the total number of passwords passed. Offline users become grey.<br>

# Admin panel
<img width="1437" height="498" alt="Image" src="https://github.com/user-attachments/assets/f02d53ea-19ec-42f6-9f6c-0efcd9144a14" />
<hr>
Tasks can be changed on the fly.<br>
<img width="1140" height="700" alt="Image" src="https://github.com/user-attachments/assets/0525fbd1-8b69-44f1-9ed6-9efbb84bdb4e" />                                  
Change patch.<br>
Specify alphabet.<br>
Specify task start position.<br>
Example, you need to start from length 9, in the specified alphabet there are 36 characters.<br>
36x36x36x36x36x36x36x36x36 = starting position.<br>
You need to start from the letter "s" + 8 generation.<br>
The letter "s" is located in the 19th position of the alphabet.<br>
19x36x36x36x36x36x36x36x36x36 = starting position.<br>
The search will start from saaaaaaaa<br>
Specify address base (there IS support for .bin bases).<br>
Specify coin type.<br>
Pause, start.<br>

# 2 Telegram groups

In the configuration file, specify the telegram bot and 2 chats IDs.<br>
The message public group:<br>

-============== FOUND ==============-<br>
User: Alex3322<br>
Adr: 0x8ba042c96f27f5012cf0e66114793b0b5b11bc24<br>
===================================<br>

Comes to the admin group<br>

<img width="393" height="621" alt="Image" src="https://github.com/user-attachments/assets/f0e8c9ae-8d53-4309-9493-bd31a1c8b5f0" />

# Clients MultiGPUs
All clients perform their part (chunk) of the overall task.<br>
Only CUDA cards support GTX, RTX, CMP<br>
Brute speed:<br>
RTX 4090 = 520k/s<br>
RTX 5090 = 800k/s<br>

To connect to the server, a short command<br>
linux:   ```./xx -u YourNick```<br>
win: ```xx.exe -u NameRigs```

The client automatically downloads the address database. <br>
If the database on the server has changed, it automatically updates it. <br>
After downloading, the client checks the checksum of the database, which excludes incompletely downloaded addresses.

After launching, the client displays only the speed.<br>
If the client finds an address, the window displays the found address.<br>
<img width="977" height="510" alt="Image" src="https://github.com/user-attachments/assets/29720e79-e401-4d2c-82e1-f134dc52858d" />

The search position is displayed in the admin client<br>
![Image](https://github.com/user-attachments/assets/5fa5e231-56c6-4845-afea-36483cf3f5c3)

If the server has a 7-16 GB address base, add --blom 2048M to the startup line<br>
For the alleth.bin database of 29 GB, add --blom 4096M<br>
ex. ```./xx -u Alex3322 --bloom 4096M```
<hr>
What is sold for $500 ?<br>
Files for the server + instructions for installation and configuration.<br>
Source code bip39scan v2 (client) + instructions on how to build for ubuntu, win.<br>
For any questions, contact @phrutis<br>

If you don't have the knowledge, run putty to install the server, configure, and build clients.<br> 
I'll give you the contact of a programmer, he will help you install, configure, and build clients if you need to make changes.<br> 
His services are paid.

