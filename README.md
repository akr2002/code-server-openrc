# code-server-openrc

OpenRC script for code-server.

This script is pretty generic and should be able to run on any OpenRC-based distribution with minimal tweaks.

## Usage
Put `code-server` in `/etc/init.d` and make it executable with `chmod +x code-server`. Put your username in line 3.

Run on boot with default runlevel
```
rc-update add code-server default
```

Start the service immediately
```
rc-service code-server start
```
