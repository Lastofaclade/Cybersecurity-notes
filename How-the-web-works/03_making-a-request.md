# What Happens During a DNS Request – Key Points
### 1️⃣ Local DNS Cache Check:
Your computer first checks its cache (memory) to see if it has visited the website before.
If it finds the IP address saved from a past visit, it uses that to connect quickly.

### 2️⃣ Recursive DNS Server:
If not in cache, the request is sent to a recursive DNS server (usually from your ISP or one you've set like Google DNS 8.8.8.8).
By default, your device uses the Recursive DNS Server provided by your ISP (like Vodacom, Telkom, MTN).
But you can change it if you want to just like i did i use dns.adguard.com to block ads and load site faster 

### 3️⃣ Root DNS Server:
The root servers act as the DNS backbone of the internet; their job is to redirect you to the correct Top Level Domain Server, depending on your request. If, for example, you request www.google.com , the root server will recognise the Top Level Domain of .com and refer you to the correct TLD server that deals with .com addresses.

### 4️⃣ TLD Server:
The TLD server provides the location of the Authoritative DNS Server for the domain.
#### From tryhackme
The TLD server holds records for where to find the authoritative server to answer the DNS request. The authoritative server is often also known as the nameserver for the domain. For example, the name server for tryhackme.com is kip.ns.cloudflare.com and uma.ns.cloudflare.com. You'll often find multiple nameservers for a domain name to act as a backup in case one goes down.

### 5️⃣ Authoritative DNS Server:
This server stores the actual DNS records (A, AAAA, CNAME, MX, etc.) for the domain and responds with the IP.
Then the recursive DNS server will cache the results with a **TTL** ( Time To Live ) and sends it back to the computer. The computer will use the IP to connect to the internet. 
