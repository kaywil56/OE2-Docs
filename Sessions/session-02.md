## Session 2
27/02/2023 - 9:28am

### Actions Taken
- Changed labvm-1 hostname to Management
- Changed labvm-2 hostname to Database

### Lab 2.1
On the management VM we created hello.sh and copied the example bash script into that file.
Created hello.service unit file and copied the example file, changing the <your home dir> to home/group-f.
Copied that hello.service file from our home dir into /etc/systemd/system.
Ran the commands ```systemctl list-unit-files | grep hello.service``` ```systemctl start hello.service``` ```systemctl status hello.service``` ```journalctl -u hello -e``` We then changed the prompt on each VM to include a timestamp by editing the ~/.bashrc file
