﻿---
title: CLOUDPANEL(UBUNTU-22.04 TLS)
sidebar_label: CLOUDPANEL
---

**Description:**

CloudPanel is a free and modern server control panel to configure and manage a server with an obsessive focus on simplicity. Run PHP, Node.js, Static Websites, Reverse Proxies, and Python Applications in no time on a High-Performance Technology Stack.

**Please note**: It can take up to 5 - 10 mins to complete the Installation.

[Click here to view the requirements...](https://www.cloudpanel.io/docs/v2/requirements/)

**Software Included:**

CLOUDPANEL + MYSQL - Latest

**Getting started after deploying CloudPanel:**

Allow the ports in the firewall only SSH (port 22, rate limited), and CloudPanel Web Interface (port 8443) access.

You will be logged out of the instance and displayed with the below message until the instance is deployed.  **DO NOT LOG IN TO THE INSTANCE FOR 2 MINUTES AFTER THE CREATION.**

```
Please wait until the installation is completed....
Connection to $IPADDRESS closed.
```

**Once the CloudPanel is deployed:**

You can log into the instance as ubuntu using either the password you set when you created the instance or with an SSH key if you added one during creation.

You can then switch the user to root without a password by entering the following command.  **< sudo su - >**

You can access the CloudPanel Web interface at http://IPADDRESS:8443

You can then set up the CloudPanel through Web interface.