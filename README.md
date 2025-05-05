# Cyber
Class Activity for IT 250: pfSense Web Configurator
Start your pfsense VM on Proxmox
Login to pfSense VM using user:admin and password:pfsense
Once logged in, from the menu choose 3 to reset the web configurator password, and finally choose 11 to restart the web configurator
Open Kali Linux VM
Open browser and type 10.0.0.1
Login using user:admin and password:pfsense
Go to Firewall->Rules and add a LAN (outgoing) rule to block ping requests to machines outside the network, e.g., pinging google. Provide a screenshot
Open Windows 10 VM and then open its firewall. Add an outbound rule to drop outgoing DNS traffic. Check the rule by browsing web. Provide screenshot![Screenshot 2025-03-24 232814](https://github.com/user-attachments/assets/b9e7de74-9d21-4da5-b274-87481d957e16)
