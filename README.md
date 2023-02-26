# firewall-ubuntu
firewall ubuntu

```
 sudo apt install ufw
```

## Show firewall status
```
sudo ufw status
```


## Enable firewall
```
sudo ufw enable
sudo ufw allow 80
sudo ufw allow 443
```

## Delete rule
```
sudo ufw delete allow 80
```

## Disable firewall
```
sudo ufw disable
```




## centos
```
sudo systemctl stop firewalld.
sudo systemctl status firewalld
```
