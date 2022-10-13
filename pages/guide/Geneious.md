---
title: Geneious Software Guide
description: Geneious Software Use Guide
permalink: /guide/geneious
author: VRSC
layout: page
# sidenav:  is a side navigation bar is needed it can be specified in the _data/navigation.yml file
---


Ceres no longer has Geneious Server. The developer has discontinued that product.

Ceres does provide floating licenses for Geneious Prime which is the desktop client.  


Caveats:
* The floating license server will only work at USDA sites or via VPN due to firewall restrictions.
* The Geneious Prime license server should work through both the regular USDA VPN and the SCINet ocvpn vpn servers. 
* If you do encounter license server issues let us know at [scinet_vrsc@usda.gov](mailto:scinet_vrsc@usda.gov)


First download the Geneious client from [https://www.geneious.com/download/](https://www.geneious.com/download/)

Install it as usual and start it up.

Geneious will complain about not having a license. Click "Activate a License"

![screenshot of Geneious software No License for Geneious R11 popup](/assets/img/geneious/geneious_license_expired.png)

On the "Enter Your License Details" screen,
  - select "Use floating license server",
  - enter `geneious.scinet.usda.gov` in the "License Server" box, and
  - enter `27001` in the "Port" box.

![screenshot of Geneious software Enter Your License Details screen](/assets/img/geneious/geneious_floating_license_server.png)


Geneious Prime can also be accessed via [Ceres OpenOnDemand](https://scinet.usda.gov/guide/ceres_ood/)
which will allow you to run Geneious Prime directly on a cluster node.

![screenshot of Geneious in OOD menu](/assets/img/geneious/menu.png)
![screenshot of Geneious in OOD Options](/assets/img/geneious/options.png)
![screenshot of Geneious OOD launch](/assets/img/geneious/launch.png)

