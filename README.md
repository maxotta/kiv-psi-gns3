# ![PSI Logo](images/icon-64-net.png) Computer Networks Lab GNS Appliances
## Introduction

This repository holds prepared [GNS3](https://docs.gns3.com/docs/) appliances used in the course "Computer Networks" labs taught at the [Department of Computer Science and Engineering](http://www.kiv.zcu.cz/), University of West Bohemia, Czech Republic.

## Appliances

Currently available appliances:
* `Cisco 7200 Router` - running Cisco IOS Software, 7200 Software (C7200-ADVENTERPRISEK9-M), Version 15.0(1)M, RELEASE SOFTWARE (fc2) - [cisco-7200.gns3a](appliances/cisco-7200.gns3a)
* `VyOS Router` - running a [VyOS rolling release](https://vyos.net/get/nightly-builds/) - [vyos.gns3a](appliances/vyos.gns3a)
* `PSI Base Node` - running Ubuntu Linux in a Docker container with pre-installed basic networking utilities - [psi-base-node.gns3a](appliances/psi-base-node.gns3a)

## Using the appliances in GNS3

Download the appliance descriptor file *.gns3a and import it into GNS3 by choosing File/Import Appliance

