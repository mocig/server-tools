encrypt-partition.sh
```
	Usage: ./encrypt-partition.sh: <dev> <mountpoint> <name>
	
	Setup a cryptfs on <dev>, zero it, format it, and mount it to <mountpoint>

	Expects to run as root. Places a mount-<name>.sh in ~/ for mount aswell
```
setup-lxc.sh
	Usage: ./setup-lxc.sh lxc-network
	
	Installs lxc and dnsmasq, configures bridge interface, network, nat
	and places a new-container command in /usr/local/sbin

	Asumes root, and a clean system (f.e. it will overwrite /etc/dnsmasq.conf)
```

