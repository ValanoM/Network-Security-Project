# Network-Security-Project



<h2>Background</h2>
Let's talk about what you will be doing as a security analyst. GoodCorp Inc. is 
currently experiencing serious network security challenges. For example, users can 
access resources they should not have access to, and some inbound traffic that should 
be blocked is still allowed. We also lack secure access to remote employees and need 
to heighten their understanding of what is going on. 
Your new manager has assigned you to a position in the SOC. From now on, all 
security-related requests will be sent to you. Your mission is to manage the service 
and security tickets. You must organize the tasks, configure services, customize rules, 
and perform any security measures required to resolve detected issues. 
Please keep in mind that, as a security analyst, you should make use of best practices 
and be prepared to provide evidence of your work and solutions. 
We wish you the best of luck in your new role. 
.
<br />

<h2>Description</h2>



<h2>Environments Used </h2>

- <b>VirtualBox for four VMs (Kali Linux, Debian, Ubuntu with Apache Webserver, 
and RedHat with pfSense) </b> (21H2)

<h2>Project Task 1:</h2> Blocking Unwanted Traffic 
A primary complaint of GoodCorp's HR is that some employees spend time with apps 
they should not use. For example, an employee was caught several times playing online 
games when he should have been placing orders on supplier websites. The HR manager 
has requested that you block the games and get the employee to focus more on his job. 
You know HTTP is important for GoodCorp's business and should be accessible. 
Web traffic is your company's most common communication with its customers and 
suppliers. It definitely should not be blocked.  walk-through:

<img src="Screenshot task1.2.png">
  
Firewall rules to block unwanted IPs: <br/>
<img src="Screenshot task1.3.png">
<br />
<h2><h2>Project task2</h2>: Quick Solution for Remote Access 
During the COVID-19 outbreak, some services needed to be performed remotely. An 
employee requires access to systems running on the web server at the HQ office and 
the ability to manage the web server that runs on the Ubuntu VM via SSH. 
The warehouse manager requested VPN access for the employees. Still, while the 
firewall is not licensed and configured to work as needed, he wants the employee to 
have temporary access via other means. He asks you to make the web server and SSH 
service available for connection from remote networks, and you need to come up with 
a logical solution for the issue.  walk-through:


<h2><h2>Access ssh to ubuntu web server:</h2>
<img src="Screenshot task 2.1 access ssh to ubuntu web server from debian.png">
Access web server from host VM
<img src="Screenshot task 2.1access web server from host vm.png">
<br />
Port Forwarding
<img src="Screenshot task2.2 port forwarding.png">
Http connection from physical host machine
<img src="Screenshot task2.3 http connection from physical host.png">
SSH connection from physical host machine to Ubuntu VM
<img src="Screenshot task2.3 ssh connection from physical host machine to Ubuntu vm.png">

<h2>Project Task 3: The All-Seeing Eye </h2>
The company's CISO decided to implement a detection and prevention system against 
potential known network attacks. She put you in charge of the implementation. You 
were asked to set up a mechanism capable of detecting DoS and Brute-Force attacks 
and verifying that they function correctly.
<br />

Installation of Suricata package required to accomplish the detection and prevention 
tasks

<img src="Screenshot task3.1.png">
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
