## packet device create

Create a new device

### Synopsis


Create a new device

```
packet device create
```

### Options

```
      --billing string      Choose "hourly" or "monthly" billing. Default is "hourly". (default "hourly")
      --facility string     Location of the device. Available values are: 
      --hostname string     Hostname to assign to the created device.
      --os-type string      Operating system to deploy to the server. (default "centos_7")
      --plan string         Which server type to create the device. Default is "type_0" (default "type_0")
      --project-id string   The project ID.
```

### Options inherited from parent commands

```
  -k, --key string   Specify the api key
```

### SEE ALSO
* [packet device](packet_device.md)	 - Manage your devices

###### Auto generated by spf13/cobra on 29-May-2016