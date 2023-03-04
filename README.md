# randomvpn

connect to a random public vpn
location data is contained on line 1 of each config file
to connect to a specific vpn, change this code on line 12 from this:

```python
for i in range(1, 45)
```

to this:

```python
for i in range(<num>, <num>)
```

delete
## requirements

- openvpn
- python3

## macOS/linux

```bash
git clone https://github.com/flinnthebin/vpn
chmod 755 randomvpn
sudo ./randomvpn
```   

## windows

download openvpn - https://openvpn.net/client-connect-vpn-for-windows/
run powershell as administrator

```bash
git clone https://github.com/flinnthebin/vpn 
python3 randomvpn
```   
