# DNS_Bind9

1. Edit `resolved.conf`
   `sudo nano /etc/systemd/resolved.conf`
2. Uncomment: `DNSStubListener=yes`
3. Change the value to `no`
4. Restart service `sudo systemctl restart systemd-resolved`
