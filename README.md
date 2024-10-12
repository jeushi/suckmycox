
# SuckMyCox ;)

Tiny script to spoof your MAC

Intended to extend the CoxWiFi free trial duration

#### ⚠️ THIS SCRIPT HAS ONLY BEEN TESTED WITH WIFI ⚠️
## Installation


Before installing ensure you have both OpenSSL and NMCLI before proceeding as the script does not work otherwise.

Make sure ```~/.local/bin``` has been added to your paths before installing or change it to a location in your path.

### curl
```bash
curl -o ~/.local/bin/suckmycox https://raw.githubusercontent.com/jeushi/suckmycox/refs/heads/main/suckmycox && chmod +x ~/.local/bin/suckmycox
```

### wget
```bash
wget -O ~/.local/bin/suckmycox https://raw.githubusercontent.com/jeushi/suckmycox/refs/heads/main/suckmycox && chmod +x ~/.local/bin/suckmycox
```
## Usage

You can find the list of available devices by running ```nmcli dev status```


### Normal
Command usage for when the targetted network is 'CoxWiFi'
```bash
suckmycox [Device Name]
```

### Optional
Command usage for when the targetted network is a network other than 'CoxWiFi'
```bash
suckmycox [Device Name] [SSID]
```



