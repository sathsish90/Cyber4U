
# Sample Search Engines:
- [Search Engine](https://github.com/WADComs/WADComs.github.io)
- [Threat market maps](https://thedemoforum.com/page/cybersecuritymarketmaps/)
- [Cloudflare](https://radar.cloudflare.com/)
- [XDR](https://www.paloaltonetworks.com/cortex/cortex-xdr)
- [Shell](https://shellizm.com/)
- [News](https://www.internationalcybersecuritycentre.com/live-attack-maps-(16))
- [Github Terminal made up of Javascript](http://attackvector.org/)

Cyber Security Search Engines
===============
- Yet to add
- Social search: OSINT framework
- TraceLabs - https://www.tracelabs.org/

List of Search Queries: [SIEM/Splunk/Snort & IDS/IPS - Monitoring/Logging tools]
================
- Yet to Add
- Develop search queries and indicators of compromise to identify potential malicious activities.
- Leverage Threat Intelligence Feeds,
- Known Malware Signatures,
- Behavioral analytics.
- Firewall Rules/Configurations [Audit]
- Splunk/Snort Rules
- SIEM/SOAR queries
- Log files queries
- Network Traffic dumps
- Endpoint Logs [Client/Server Logs]

| S NO | Tool Name | Log file name | Example | Description |
|------|-----------|---------------|---------|-------------|
| 1    | Splunk    | splunkd.log   | `index=main sourcetype=splunkd` | Querying Splunk daemon logs for general Splunk server activity. |
| 2    | Snort     | alert.ids     | `alert tcp any any -> any 80 (msg:"Potential HTTP traffic"; sid:100001; rev:1;)` | Writing a Snort rule to detect potential HTTP traffic. |
| 3    | IDS/IPS   | intrusion.log | `signature_id=1234` | Searching IDS/IPS logs for a specific signature ID (1234 in this example). |
| 4    | SIEM      | security.log  | `event_id=4625` | Using a SIEM to look for Windows security events with event ID 4625 (failed login attempts). |
| 5    | Splunk    | firewall.log  | `index=firewall action=permit` | Querying firewall logs in Splunk to identify permitted actions. |
| 6    | Snort     | dns.log       | `alert dns any any -> any any (msg:"Potential DNS traffic"; sid:100002; rev:1;)` | Creating a Snort rule to detect potential DNS traffic. |
| 7    | IDS/IPS   | connection.log | `source_address=malicious_ip` | Searching IDS/IPS logs for connections from a specific source IP (malicious_ip in this example). |
| 8    | SIEM      | authentication.log | `user=admin` | Using a SIEM to search for authentication logs with a specific username (admin in this example). |
| 9    | Splunk    | application.log | `index=main sourcetype=application error` | Querying application logs in Splunk for errors. |
| 10   | Snort     | ftp.log       | `alert ftp any any -> any any (msg:"Potential FTP traffic"; sid:100003; rev:1;)` | Crafting a Snort rule to detect potential FTP traffic. |
| 11   | IDS/IPS   | malware.log   | `file_hash=abcdef123456` | Searching IDS/IPS logs for entries related to a specific file hash (abcdef123456 in this example). |
| 12   | SIEM      | system.log    | `event_type=system_shutdown` | Using a SIEM to find system logs related to a shutdown event. |


# Cyber Security Search Engines

| SNO | Name               | Description                                       | Link                                            |
| --- | ------------------ | ------------------------------------------------- | ----------------------------------------------- |
| 1   | Dehashed           | View leaked credentials.                         | [Dehashed](https://dehashed.com/)              |
| 2   | SecurityTrails     | Extensive DNS data.                              | [SecurityTrails](https://securitytrails.com/)  |
| 3   | DorkSearch         | Really fast Google dorking.                      | [DorkSearch](https://dorksearch.com/)          |
| 4   | ExploitDB          | Archive of various exploits.                     | [ExploitDB](https://www.exploit-db.com/)       |
| 5   | ZoomEye            | Gather information about targets.                | [ZoomEye](https://www.zoomeye.org/)            |
| 6   | Pulsedive          | Search for threat intelligence.                   | [Pulsedive](https://pulsedive.com/)            |
| 7   | GrayHatWarefare    | Search public S3 buckets.                        | [GrayHatWarefare](https://buckets.grayhatwarfare.com/) |
| 8   | PolySwarm          | Scan files and URLs for threats.                 | [PolySwarm](https://polyswarm.io/)             |
| 9   | Fofa               | Search for various threat intelligence.           | [Fofa](https://fofa.so/)                       |
| 10  | LeakIX             | Search publicly indexed information.              | [LeakIX](https://leakix.net/)                  |
| 11  | DNSDumpster        | Search for DNS records quickly.                  | [DNSDumpster](https://dnsdumpster.com/)        |
| 12  | FullHunt           | Search and discovery attack surfaces.            | [FullHunt](https://fullhunt.io/)               |
| 13  | AlienVault         | Extensive threat intelligence feed.               | [AlienVault](https://otx.alienvault.com/)      |
| 14  | ONYPHE             | Collects cyber-threat intelligence data.          | [ONYPHE](https://www.onyphe.io/)               |
| 15  | Grep App           | Search across a half million git repos.          | [Grep App](https://grep.app/)                  |
| 16  | Shodan             | Search for devices connected to the internet.    | [Shodan](https://www.shodan.io/)              |
| 17  | URL Scan           | Free service to scan and analyse websites.        | [URL Scan](https://urlscan.io/)                |
| 18  | Vulners            | Search vulnerabilities in a large database.      | [Vulners](https://vulners.com/)                |
| 19  | WayBackMachine     | View content from deleted websites.              | [WayBackMachine](https://archive.org/)         |
| 20  | Wigle              | Database of wireless networks, with statistics.  | [Wigle](https://wigle.net/)                    |
| 21  | Netlas             | Search and monitor internet connected assets.     | [Netlas](https://www.netlas.io/)               |
| 22  | CRT.sh             | Search for certs that have been logged by CT.    | [CRT.sh](https://crt.sh/)                      |
| 23  | PublicWWW          | Marketing and affiliate marketing research.      | [PublicWWW](https://publicwww.com/)            |
| 24  | Binary Edge        | Scans the internet for threat intelligence.      | [Binary Edge](https://www.binaryedge.io/)      |
| 25  | GreyNoise          | Search for devices connected to the internet.    | [GreyNoise](https://greynoise.io/)             |
| 26  | Hunter             | Search for email addresses belonging to a website. | [Hunter](https://hunter.io/)                  |
| 27  | Censys             | Assessing attack surface for internet connected devices. | [Censys](https://censys.io/)             |
| 28  | IntelligenceX      | Search Tor, I2P, data leaks, domains, and emails. | [IntelligenceX](https://intelx.io/)          |
| 29  | Packet Storm Security | Browse latest vulnerabilities and exploits.    | [Packet Storm Security](https://packetstormsecurity.com/) |
| 30  | SearchCode         | Search 75 billion lines of code from 40 million projects. | [SearchCode](https://searchcode.com/) |
