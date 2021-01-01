## Auto Install the Linux TeamSpeak 3 Server on Debian / Ubuntu | Working 2021
### What this script does:
- Creates a new user to run the TeamSpeak 3 Server
- Downloads and installs the latest server version
- Creates a systemd service
- Starts the server

### How to use:
Download or copy the script and paste it into a new file
```bash
wget https://raw.githubusercontent.com/rcguy/install_ts3-server/master/install_ts3-server.sh
```
Change the user variables if you want
```bash
nano install_ts3-server.sh
```
Make it executable
```bash
chmod a+x install_ts3-server.sh
```
Run the script
```bash
sudo ./install_ts3-server.sh
```
To start, stop, restart, or check the status of the ts3-server use
```bash
sudo systemctl {start|stop|restart|status} ts3server 
```

## If you need any help, you can open an issue or contact me on Discord: Vesk0#4059
