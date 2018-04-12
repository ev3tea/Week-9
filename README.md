# Week-9
Week 9 Assignment

**Honeypot #1**

I included **sessions.json.zip** file with 88K+ records for Dinoaea honeypot.

Issues:
  - I had to update the rule for mhn-admin to accept connection on port 80 (as I forgot to append it during setup) with this command: `gcloud beta compute firewall-rules update mhn-allow-admin --rules=tcp:3000,tcp:10000,tcp:80`
  
Summary:
  - 88K+ records
  - Top countries: USA, China, Russia, Europe
  - Popular protocols used: pcap, httpd, mssqld, SipSession, mysqld, smbd, 
