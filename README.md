bash license BSD Linux Debian

Reconnaissance Real IP address for Cloudflare Bypass.

CloudUnflare

Preparation:
1. CompleteDNS API
Create an account at completedns.com and verify first.
Input your email and password on CompleteDNS_Login variable in cloudunflare.bash.
2. Dependencies Needed
curl
dig
whois
Debian Based

apt-get install curl dnsutils whois -y
Installation:
Clone this repo
git clone https://github.com/kodveblog/cf-bypass/
Command:
Go to cf-bypass
cd cf-bypass
Run
bash cf-bypass.bash
