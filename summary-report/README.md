# ARP Summary Report

The ansible playbook arp-summary.yml gathers the arp table using the command module for IOS, IOSXR and NXOS devices.  Output is simply dumped into a text file and emailed for each device group.

## TODO

Fix formating using a template or lineinfile module instead of sed to fix linebreak formatting.

