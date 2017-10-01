# Lab Topology

This lab was built using [EVE-NG](http://www.eve-ng.net) network emulator.

## Network Devices

Lab enviroment constis of the following devices :

| Name  | IP | OS  | Image | 
| --- | --- | --- | --- |
| R1  | 10.0.0.201 | Cisco IOS    | c7200-adventerprisek9-mz.152-4.M11.bin |
| R2  | 10.0.0.202 | Cisco IOS    | c7200-adventerprisek9-mz.152-4.M11.bin |
| XR1 | 10.0.0.210 | Cisco IOS-XR | iosxrv-k9-demo-5.3.4.ova |
| NX1 | 10.0.0.220 | Cisco NX-OS  | nxosv-final.7.0.3.I7.1.ova |
| VM1 | 10.0.0.55  | Debian Linux | debian-8.6.0-amd64-netinst.iso |

VM1 has access to all network devices.

![Lab](https://github.com/netesc/ipspace/blob/master/lab/lab.PNG)
