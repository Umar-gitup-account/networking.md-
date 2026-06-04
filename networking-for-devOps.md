# networking for devops - hands on practice

## Overview
this documents contains network concepts and commonds practiced during my devOps learning journey.

## topics covered

- OSI model
- TCP/IP model
- IP addressing
- Subnet mask
- DNS
- DHCP
- HTTP & HTTPS
- SSH
- Routing
- Network troubleshooting

## commonds practiced

### check IP address

```Bash
 IP Addr show
```


## check network interfaces

```Bash
IP link show


### display routing table


```bash
IP rout
```

### test connectivity

```Bash
Ping google.com
```

### DNS Lookup

```bash
nslookup google.com
```

### display DNS Information

```bash 
cat /etc/resolve.conf
```


### check active network connections

```bash
ss -tuln
```


### check listening ports

``` bash
netstat -tuln
```


### trace Route

 ```Bash
  traceroute google.com
```

### SSH connection Test

```Bash
ssh username@server-ip
```


### Download  web page 

```bash
curl https:// google.com
```



### check HTTP Header

```bash
curl -I https://google.com
```



## Learning Outcomes

- Learned networking fundamentals required for DevOps.
- Practiced troubleshooting network connectivity issues.
- Understood DNS resolution and routing concepts.
- Worked with HTTP/HTTPS and SSH protocols.
- Analyzed network interfaces and open ports.
- Gained hands-on experience using Linux networking tools.


## DevOps Relevance

Networking is essential in DevOps for:
- Server Management
- Cloud Infrastructure
- Container Communication
- CI/CD Pipelines
- Monitoring and Troubleshooting



