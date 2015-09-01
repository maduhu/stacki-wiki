## config host interface

### Usage

`stack config host interface {host} [flag=string] [iface=string] [mac=string] [module=string]`

### Description

Adds host interfaces to the database.

	This command should only be called from a post section in a kickstart
	file.

### Arguments

* `{host}`

   Host name of machine


### Parameters
* `[flag=string]`

   Flags for the interfaces. If flags for multiple interfaces
	are supplied, then they must be comma-separated.
* `[iface=string]`

   Interface names (e.g., "eth0"). If multiple interfaces are supplied,
	then they must be comma-separated.
* `[mac=string]`

   MAC addresses for the interfaces. If multiple MACs are supplied,
	then they must be comma-separated.
* `[module=string]`

   Driver modules to be loaded for the interfaces. If multiple modules
	are supplied, then they must be comma-separated.

