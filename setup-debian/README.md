encrypt-partition.sh
	Usage: ./encrypt-partition.sh: <dev> <mountpoint> <name>
	
	Setup a cryptfs on <dev>, zero it, format it, and mount it to <mountpoint>

	Expects to run as root. Places a mount-<name>.sh in ~/ for mount aswell
