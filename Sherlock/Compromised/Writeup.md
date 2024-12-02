## Challenge Name: Compromised
Category: Sherlock


Challenge Description: 
Our SOC team detected suspicious activity in Network Traffic, the machine has been compromised and company information that should not have been there has now been stolen – it’s up to you to figure out what has happened and what data has been taken.

Files:
* [PCAP File](./capture.pcap)

### Solutions

1. What is the IP address used for initial access?
* `162.252.172.54`
2. What is the SHA256 hash of the malware?
* `9b8ffdc8ba2b2caa485cca56a82b2dcbd251f65fb30bc88f0ac3da6704e4d3c6`
3. What is the Family label of the malware?
* `Pikabot`
4. When was the malware first seen in the wild (UTC)?
*. `2023-05-19 14:01:21`
5. The malware used HTTPS traffic with a self-signed certificate. What are the ports, from smallest to largest?
* `2078, 2222, 32999`
6. What is the id-at-localityName of the self-signed certificate associated with the first malicious IP?
* `Pyopneumopericardium`
7. What is the notBefore time(UTC) for this self-signed certificate?
* `2023-05-14 08:36:52`
8. What was the domain used for tunneling?
* `steasteel.net`