# fail2ban-pfsense-easyrule
How to use fail2ban behind a pfsense firewall.

From your server/host you are protecting with fail2ban, you need to setup a passwordless login into pfsense.
The action file then executes the easyrule command against an interface in ofsense, blocking the offending ip.

Sure needs polishing.
