# System-Information-Network-Testing-Simple-Command
How to create system information &amp; network testing command
System Information & Network Testing
Part 1 — System Information
Deliverables — Step 1
➔ Screenshot showing the output of all three commands
 
➔ What username is shown by whoami? What is your machine's 
hostname? = mdtdairo 
➔ What directory are you currently in? = Home/mdtdairo
Deliverables — Step 2
➔ Screenshot of uname -a output 
 


➔ Screenshot of free -h and df -h output
 
➔ How much total RAM does your VM have? = The VM has 5.7 GiB of total RAM
➔ How much disk space is available on the main partition? = 1.1 GiB available
➔ What version of the Linux kernel is your Kali using? (Look at the uname -a output.) = Kali VM is using Linux kernel 7.1.5+kali-amd64 

Part 2 — Basic Network Connectivity Test
Deliverables — Step 1
➔ Screenshot of the full ping -c 2 8.8.8.8 output including the statistics summary
 
➔ What was the average round-trip time (ms) shown in your results? Was there any packet loss? = The average round-trip time was 19.491 ms. There was 0% packet loss (2 packets sent, 2 received)
Deliverables — Step 2
➔ Screenshot of the full ping -c 4 google.com output
 
➔ What IP address did google.com resolve to? Is the round-trip time similar to or different from pinging 8.8.8.8 directly and why do you think that is? = google.com resolved to 142.251.29.100. Its average round-trip time was 19.048 ms, which was very similar to pinging 8.8.8.8 directly at (19.491 ms). The small difference is normal network variation which is not really an issue. Also, the two pings reach different Google servers or services, even though both responses took about 19 ms.
➔ What does -c 4 mean? = -c 4 means tell ping to send 4 packets, then stop and show the results.

Conclusion
This assignment displayed the basic practice in reading system information, viewing user account details, and testing network connectivity using ping. 
These are foundational skills every Linux user and cybersecurity professional must be comfortable with.
Thank you
<img width="451" height="706" alt="image" src="https://github.com/user-attachments/assets/fd43e394-0c7b-4923-a74b-68bfb2b6e006" />
