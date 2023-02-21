# systemd-sshtunnel
1. place '''sshtunnel@.service''' file in '''/etc/systemd/system''' and fill in the user to execute service.
2. place '''sshtunnel@example''' file in '''/etc/default''' and fill in ports, sshconfig and change/adjust name after @ sign
3. start service with '''systemctl start sshtunnel@example.service'''
4. profit!!
