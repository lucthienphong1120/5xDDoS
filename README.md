# precursor: MHDDoS by MH ProDev

36DDoS is only a tool for SECURITY TESTING PURPOSES!

36DDoS is a DDoS tool with great attack power, be careful when using it

Please Don't Attack '.gov'  and '.edu' Websites

## Method

 * Layer7
   * GET | GET Flood
   * POST | POST Flood
   * OVH | Bypass OVH
   * STRESS | Send HTTP Packet With High Byte 
   * OSTRESS | STRESS Without Proxy
   * DYN | A New Method With Random SubDomain
   * SLOW | Slowloris Old Method of DDoS
   * HEAD | HTTP HEAD method
   * HIT | POST Without PROXY
   * NULL | Null UserAgent 
   * COOKIE | Random Cookie PHP 'if (isset($_COOKIE))'
   * BRUST | A Method with more header
   * PPS |  Only 'GET / HTTP/1.1\r\n\r\n'
   * EVEN | GET Method with more header
   * GSB | Google Project Shield Bypass
   * DGB | DDoS Guard Bypass
   * AVB | Arvan Cloud Bypass
   * CFB | CloudFlare Bypass
   * BYPASS | Bypass Normal AntiDDoS


* Layer4: 
  * TCP | TCP Flood Bypass
  * UDP | UDP Flood Bypass
  * SYN | SYN Flood
  * VSE | VSE Flood Only Connection
  * MEM | Memcached Flood
  * NTP | NTP Flood OLD Method Of Layer4

* Layer3
  * ICMP | Flood ICMP Request
  * POD | Ping Of Death OLD Method Of DDoS

* Tools - Run With 'python3 start.py tools'
  * CFIP | Find Real IP address of Website Powered by Cloudflare
  * DNS | Show Site DNS Records
  * PING | PING server
  * CHECK | Check Website Die or no
  * DSTAT | a Method show Receive And Send Bytes Size

* Other
  * STOP | STOP All Attacks
  * TOOLS | Tools Console
  * HELP | Show Usge Script
  

## Usage

```console
    git clone https://github.com/lucthienphong1120/36DDoS
    cd 36DDoS
    pip3 install -r requirements.txt
    python3 start.py help
    
    python3 start.py <method> <url> <socks_type> <threads> <proxylist> <workers> <time>
    Example: python3 start.py CFB https://example.com 5 1000 socks5.txt 100 100
```

Check website monitoring in https://check-host.net/

## LEGAL NOTICE
THIS SOFTWARE IS PROVIDED FOR EDUCATIONAL USE ONLY! 
IF YOU ENGAGE IN ANY ILLEGAL ACTIVITY THE AUTHOR DOES NOT TAKE ANY RESPONSIBILITY FOR IT. 
BY USING THIS SOFTWARE YOU AGREE WITH THESE TERMS.
