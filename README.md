# NetConn
Open-source router and firewall software for Linux written in Go. Utilizes Linux's [XDP](https://www.iovisor.org/technology/xdp) hook through [(e)BPF](https://ebpf.io/) for fast packet processing.

## Prerequisites
* A Linux OS distro with XDP support implemented into kernel.
* At least 512 MBs of free RAM.
* Golang.

### Golang Packages
Additional packages for Golang are used in the following.

```bash
# Install Dropbox's GoeBPF module.
go get github.com/dropbox/goebpf
```

## Contributors
* [Christian Deacon](https://github.com/gamemann)
