# Week-9
Week 9 Assignment

![](https://i.imgur.com/7J7hVYo.png)

**Honeypot #1**

I included **sessions.json.zip** file with 88K+ records for Dinoaea honeypot.

Issues:
  - I had to update the rule for mhn-admin to accept connection on port 80 (as I forgot to append it during setup) with this command: `gcloud beta compute firewall-rules update mhn-allow-admin --rules=tcp:3000,tcp:10000,tcp:80`
  
Summary:
  - 88K+ records
  - Top countries: USA, Russia, China, Europe
  - Popular protocols used: pcap, httpd, mssqld, SipSession, mysqld, smbd, 
  - Popular ports: 5060, 445, 3306, 23, 80

**Honeypot #2**

Issues:
  - No issues encountered with this honeypot
  
Summary:
  - Top countries: USA, Russia
  - Popular protocols used: TCP 
