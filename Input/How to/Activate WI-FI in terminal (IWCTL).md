#linux
#### iNET wireless [[Daemon]] for Linux. 
The idea with [[Arch Linux]] is to optimize the resources and use the kernel in most of the possible scenarios. that's why we're going to use the [[Daemon iwd]] 
Process to enable Wi-Fi:
1. Open the IWCTL terminal.
```console
IWCTL
```
2. Get the available Wi-Fi networks 
```console
station wlan0 get-networks
```
3. Exit and get back to the main console
4. Connect to the desired WI-FI network
```console
iwctl --passphrase <passphrase> station <interface> connect NetworkName
```
5. Verify if we have IP
```console
ip addr show
```