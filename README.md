# MeshChat

Simple Primary Channel Chat client for Meshtastic

![node](images/meshchat.png)


## Preparing

Clone the repo from github with:
``` bash 
gh repo clone pablorevilla-meshtastic/MeshChat
```
Create a python virtual environment:
``` bash
cd IPchat
```
``` bash
python3 -m venv env
```
Install the environment requirements:
``` bash
./env/bin/pip install -r requirements.txt
```
 Edit `config.ini` and change the IP address of your Meshtasic node.
 ```bash
 nano config.ini
 ``` 
```ini
[node]
node_ip = 192.168.0.10  # Replace with your Meshtastic node's IP address
```

## Running Chat
Start the chat client.
``` bash
./env/bin/python chat.py
```
