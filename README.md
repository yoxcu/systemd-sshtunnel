# systemd-sshtunnel
1. place ```sshtunnel@.service``` file in ```/etc/systemd/system``` and fill in the user to execute service.
2. place ```sshtunnel@example``` file in ```/etc/default``` and fill in ports, sshconfig and change/adjust name after @ sign
3. reload systemd daemon with ```systemctl daemon-reload```
4. start service with ```systemctl start sshtunnel@example.service```
5. profit!!
