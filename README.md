# RHEL Study Guide Setup the Web Console

[RHEL Study Guide - Table of Contents](https://github.com/pslucas0212/RHEL-Study-Guide)


With RHEL 9 the web console should be already installed and we just need to enable it.
```
# systemctl enable --now cockpit.socket
```
Check to see if the firewall is configured for the web console
```
# firewall-cmd --list-all
```

Use the local browser to access the web consoel - https://localhost:9090

To add remote servers:
1. In the upper left corner click on the user@host.name.com drop down
2. Click the Add new host button
3. Fill in the host name and user name and click the Add button
