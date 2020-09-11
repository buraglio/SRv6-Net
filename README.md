# SRv6-ExampleNet

### SRv6 Routing topology testing
Included here are the Test configurations for SRv6 testing with FreeRTR and Cisco IOS-XR as well as the Topology and Eve-NG Lab XML File. This repo consists of a 4 Router Lab utilizing FreeRTR and IOS-XR nodes for testing. More information on freertr can be found [here](https://forwardingplane.net/2019/03/02/freertr-as-a-lab-environment/) and [here](http://freerouter.nop.hu/)
This is a work in progress and will change over time.  IOS-XR will be added once FreeRTR configurations are working.

### Files and such

1. rtr** FreeRTR OS configurations as stored in the flash. Usable in the "startup configuration" for Eve-NG
2. FreeRTR Lab.unl - the Eve-NG XML file that is the lab (To be added)
3. .txt files - various commands used to perform tasks on ephemeral linux boxes and the full table injection goBGP system.
4. gobgpd.conf - configuration for gobgp for peerings to inject an MRT based full DFZ..

### Diagrams and physical layout

The Physical layout of this test environment is detailed in this diagram. This was built on EVE-NG bare metal server with significant horsepower.
![Physical lab Topology](https://github.com/buraglio/SRv6-Net/blob/master/Network%20Diagram.png?raw=true "Physical Lab Topology")
