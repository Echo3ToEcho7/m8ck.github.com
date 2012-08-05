---
layout: post
title: "ThaKimHost VPS Review"
description: "VPS review of a VPS from ThaKimHost"
---
About two week ago I got a VPS24 from ThaKimHost. It is a OpenVZ VPS with the following specs:

	Disk space: 15GB
	Bandwidth: 500GB
	Dedicated RAM: 256MB
	Burstable RAM: 512MB
	Control Panel: SolusVM
	IP Addresses: 1
	Location: France
	
I've used the VPS mostly to host my websites with nginx+php5-fpm+mysql and a git server. I also run some sort of email server with courier-imap+postfix. It runs on a Ubuntu 11.10 template.

I tried installing a VNC server with Fluxbox, and it worked perfect. But what didn't work that great was that when I was trying to access speedtest.net with Firefox so I could post the results of it here, it totally wasn't possible to access it because Firefox run out of memory. I tried with Google Chrome also, but the same happened with Chrome also. So I thought I should give the lightweight browser Aurora a chance. And it actually worked! ...until halfway during the test, when the browser crashed totally.

But it is a decent VPS with good specs. *But over to the benchmarks:*

**Network tests**

	CPU model :  Intel(R) Xeon(R) CPU           W3520  @ 2.67GHz
	Number of cores : 4
	CPU frequency :  2666.754 MHz
	Total amount of ram : 512 MB
	Total amount of swap : 0 MB
	System uptime :   17 min,       
	Download speed from CacheFly: 60.9MB/s 
	Download speed from Linode, Atlanta GA: 3.10MB/s 
	Download speed from Linode, Dallas, TX: 3.33MB/s 
	Download speed from Linode, Tokyo, JP: 4.08MB/s 
	Download speed from Linode, London, UK: 50.6MB/s 
	Download speed from Leaseweb, Haarlem, NL: 21.0MB/s 
	Download speed from Softlayer, Singapore: 3.87MB/s 
	Download speed from Softlayer, Seattle, WA: 5.79MB/s 
	Download speed from Softlayer, San Jose, CA: 8.34MB/s 
	Download speed from Softlayer, Washington, DC: 1.62MB/s 
	I/O speed :  50.3 MB/s

**Disk I/O**

	65536+0 records in
	65536+0 records out
	1073741824 bytes (1.1 GB) copied, 19.944 s, 53.8 MB/s
	
**IOPing**

	4096 bytes from . (simfs /dev/simfs): request=1 time=0.1 ms
	4096 bytes from . (simfs /dev/simfs): request=2 time=0.4 ms
	4096 bytes from . (simfs /dev/simfs): request=3 time=0.3 ms
	4096 bytes from . (simfs /dev/simfs): request=4 time=0.4 ms
	4096 bytes from . (simfs /dev/simfs): request=5 time=0.7 ms
	4096 bytes from . (simfs /dev/simfs): request=6 time=0.5 ms
	4096 bytes from . (simfs /dev/simfs): request=7 time=0.1 ms
	4096 bytes from . (simfs /dev/simfs): request=8 time=0.4 ms
	4096 bytes from . (simfs /dev/simfs): request=9 time=0.4 ms
	4096 bytes from . (simfs /dev/simfs): request=10 time=0.5 ms

	--- . (simfs /dev/simfs) ioping statistics ---10 requests completed in 9009.6 ms, 2626 iops, 10.3 mb/s
	min/avg/max/mdev = 0.1/0.4/0.7/0.2 ms
	

Thank you so much [ThaKimHost](http://thakimhost.com) and [FreeVPS](http://freevps.us).