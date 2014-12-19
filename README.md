linux-cli-recipes
=================

Personal collection of command line tools I find useful. A mix of CentOS and Ubuntu, but many commands are distro agnostic

#Hardware#
##Power##
check battery rate
```
grep rate /proc/acpi/battery/BAT0/state
```


##Networking##
list networking hardware
```
sudo lshw -C network 
```

review and manage network device state
```
nmcli nm
nmcli nm wifi on
nmcli nm wifi off
```

review hardware and software network device blocking
```
sudo rfkill list
```

review wireless interface details 
```
sudo iwlist 
```

review and configure network interfaces
```
ifconfig
```

Network Manager Daemon
```
sudo nm-tool
```
