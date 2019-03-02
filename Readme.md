# VCTUI - VMware vCenter Text User Interface

Basic holder `readme.me`

Inspired by the time wasted continualy right clicking in the Web UI...

## To get

`go get -u github.com/thebsdbox/vctui`

## To use

VMware vCenter credentials are required and can be specified in a number of ways:

*Flags*

`--address` - can either be https://Username:password@URL/sdk or omit the user/pass details

`--user` - used to specify a username

`--pass` - used to specify a password

`--insecure` - used to ignore a bad certificate

*Environment variables*

`VCURL` - same as --address

`VCUSER` / `VCPASS` - same as the credentials above

Then just start the application and you should see something similar below:

```
VMware vCenter
├──VMs
│  ├──server01
│  │  └──Details
│  │     ├──CPUs: 1
│  │     ├──Memory: 1024
│  │     ├──VMware Tools: guestToolsNotRunning
│  │     ├──VM IP Address:
│  │     └──MAC ADDRESS: 00:50:56:a3:64:a2
│  ├──server02
│  │  └──Details
│  │     ├──CPUs: 1
│  │     ├──Memory: 1024
│  │     ├──VMware Tools: 
│  │     ├──VM IP Address:
│  │     └──MAC ADDRESS: 00:50:56:a3:4c:da
│  ├──server03
│  ├──server04
│  ├──server05
│  └──server06
│     └──Details
│        ├──CPUs: 1
│        ├──Memory: 1024
│        ├──VMware Tools: guestToolsNotRunning
```

## Additional functionality

Pressing `ctrl+f` will allow a search option (regexp) allowing you to search for specific virtual machine names.

Feel free to use or get involved.

@thebsdbox