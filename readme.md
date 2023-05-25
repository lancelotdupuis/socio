**Script created by [Lancelot Dupuis] - [2023-05-25]**

**Disclaimer:**
Executing scripts and making network configuration changes can have significant consequences. 
Use these scripts at your own risk and exercise caution. It is essential to understand the 
implications of the changes you are making to your network configuration.

---

**STATIC/DHCP Toggle Script:**

1. Right-click the .bat file and select "Edit" or "Modifier".
2. Set the appropriate language for your operating system: English = 0, French = 1.
3. Change the adapterName to match your actual adapter name, most likely Wi-Fi or Ethernet.
4. Set the desired staticIP, subnetMask, defaultGateway, and dnsServer.
5. Save the .bat file.
6. From your desktop, create a new shortcut for the .bat file.
7. Right-click the shortcut and select "Properties" or "Propriété".
8. From there, you can change the icon if desired.
9. Then, click on "Advanced" and check the "Run as administrator" or 
"Exécuter en tant qu'administrateur" box.

Now, when you double-click the shortcut, it will automatically toggle between DHCP settings 
and the static configuration you set in step 4. After a short delay, it will display the new
IP configuration of the selected adapter.

In summary, if you are currently using DHCP on your Wi-Fi connection and execute the script,
it will set you to static mode. If you are in static mode and execute the script, 
it will switch you to DHCP mode.

If your static IP configuration is overwritten by IPv4 AutoConfiguration, 
it is likely because the static IP you set is already in use by another device on the subnet. 
After setting up your IP, you can use the IP Finder script to help your colleague find an unused IP.

---

**IP FINDER Script:**

1. Right-click the .bat file and select "Edit" or "Modifier".
2. Set the appropriate subnet you are on and specify the start range.
3. Set the maximum number of unused IPs you want it to find (default is 10).
4. You can also create a shortcut, but there is no need for admin rights.
5. Execute the script, and it will list the first 10 unused IP addresses in the subnet.

Please note that executing scripts and making network configuration changes can have 
consequences, so use these scripts with caution and ensure that you understand the 
implications of the changes you are making.
