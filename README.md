# CompTIA-Network-Learn-1.4.10-Lab-Troubleshooting-Methodology
## CompTIA CertMaster Learn v9.1

In this lab, you will be guided through a simple network-related troubleshooting scenario.

1. First, connect the two computers to the switch using the Create Link tool.  
  a. In the tools tray, select Create Link.  
  b. Select the Office1 computer and select Ethernet, then select the Switch and select any port.  
  c. Select the Home-Laptop computer and select Ethernet, then select the Switch and select any available port.  
  d. Select Create Link to end the link tool.  
2. Verify that Office1 can reach an external website.  
  a. Right-click Office1 and select Launch Windows.  
  b. Launch Chrome from the taskbar. Type in rmksupplies.com and press Enter.  
  c. The browser says, "This site can't be reached."  
  d. Something isn't working as expected. Let's identify the problem.  
3. Verify that Home-Laptop can reach an external website.  
  a. In the upper left, select Network Modeler.  
  b. Right-click Home-Laptop and select Launch Windows.  
  c. Launch Chrome from the taskbar. Type in rmksupplies.com and press Enter.  
  d. Notice that the website loads correctly. Internet access is working for this computer.  
  e. The connectivity problem seems to be localized to the Office1 computer.  
4. Let's theorize what might be causing the problem.  
  a. The IP configuration of Office1 might not be correct.  
  b. The cable might be bad that we plugged into Office1.  
  c. The NIC in Office1 might be bad.  
  d. The port on the switch might be bad.  
  Let's test our theories until we find one that appears to be the problem.  
5. Compare the IP configuration of the machine that is working to the one that is not working.  
  a. On Home-Laptop, right-click the network icon and select Network & Internet settings.  
  b. Select Ethernet and scroll down to view the IP assignment information.  
  c. Note that Home-Laptop is configured for DHCP (Automatic configuration).  
  d. On Office1, right-click the network icon and select Network & Internet settings.  
  e. Select Ethernet and scroll down to view the IP assignment information.  
  f. Note that Office1 has a manually assigned IP address.  
6. Implement a fix.  
  a. Let's try changing the IP configuration of Office1 to match Home-Laptop.  
  b. Under IP assignment, select Edit.  
  c. Under Edit IP settings, select Automatic (DHCP) and select Save.  
7. Test the fix.  
  a. On Office1, try browsing to rmksupplies.com.  
  b. Did that fix the problem?  

Required Actions
-[x] Office1 connected to Internet router
-[x] Changed to DHCP

Explanation
Complete this lab as follows:

1. First, connect the two computers to the switch using the Create Link tool.  
  a. In the tools tray, select Create Link.  
  b. Select the Office1 computer and select Ethernet, then select the Switch and select any port.  
  c. Select the Home-Laptop computer and select Ethernet, then select the Switch and select any available port.  
  d. Select Create Link to end the link tool.  
2. Verify that Office1 can reach an external website.  
  a. Right-click Office1 and select Launch Windows.  
  b. Launch Chrome from the taskbar. Type in rmksupplies.com and press Enter.  
  c. The browser says, "This site can't be reached."  
  d. Something isn't working as expected. Let's identify the problem.  
3. Verify that Home-Laptop can reach an external website.  
  a. In the upper left, select Network Modeler.  
  b. Right-click Home-Laptop and select Launch Windows.  
  c. Launch Chrome from the taskbar. Type in rmksupplies.com and press Enter.  
  d. Notice that the website loads correctly. Internet access is working for this computer.  
  e. The connectivity problem seems to be localized to the Office1 computer.  
4. Let's theorize what might be causing the problem.  
  a. The IP configuration of Office1 might not be correct.  
  b. The cable might be bad that we plugged into Office1.  
  c. The NIC in Office1 might be bad.  
  d. The port on the switch might be bad.  
  Let's test our theories until we find one that appears to be the problem.  
5. Compare the IP configuration of the machine that is working to the one that is not working.  
  a. On Home-Laptop, right-click the network icon and select Network & Internet settings.  
  b. Select Ethernet and scroll down to view the IP assignment information.  
  c. Note that Home-Laptop is configured for DHCP (Automatic configuration).  
  d. On Office1, right-click the network icon and select Network & Internet settings.  
  e. Select Ethernet and scroll down to view the IP assignment information.  
  f. Note that Office1 has a manually assigned IP address.  
6. Implement a fix.  
  a. Let's try changing the IP configuration of Office1 to match Home-Laptop.  
  b. Under IP assignment, select Edit.  
  c. Under Edit IP settings, select Automatic (DHCP) and select Save.  
7. Test the fix.  
  a. On Office1, try browsing to rmksupplies.com.  
  b. Did that fix the problem?
