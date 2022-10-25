# Firewall
This project contains tasks for learning about how to configure a server's firewall.

## Tasks To Complete
 0. Block all incoming traffic but
0-block_all_incoming_traffic_but contains ufw commands for configuring the firewall to meet the following requirements.

Requirements:
Install the ufw firewall and setup a few rules on the web-01 server given to you.
The requirements below must be applied to web-01 (feel free to do it on lb-01 and web-02, but it won't be checked).
Configure ufw so that it blocks all incoming traffic, except the following TCP ports:
22 (SSH).
443 (HTTPS SSL).
80 (HTTP).
 1. Port forwarding
100-port_forwarding contains a ufw configuration file (/etc/ufw/before.rules) of a firewall that redirects port 8080/TCP to port 80/TCP. This configuration should be applied to the web-01 server given to you.