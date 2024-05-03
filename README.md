# OLIA-Linux-Kubuntu

## Time server

`sudo apt update`  
`sudo apt install chrony`  
`systemctl status chronyd`  
Add into /etc/chrony/chrony.conf: `allow 192.168.1.0/24`  
`systemctl restart chrony`

## DB

### DBeaver  
`sudo apt install snapd`  
`sudo snap install dbeaver-ce`  
