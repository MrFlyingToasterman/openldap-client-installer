# openldap-client-installer
A (testing) OpenLDAP Client installer designed for Fedora (25) <br>
Created by Pascal Peinecke and Darius Musiolik.

# Testing
Tested in a small business environment with Fedora 25. <br>
We are using a Firewall with the IP 192.168.88.1 and a running OpenLDAP Server. <br>
We are using a NAS with a NFS for our homefolders too. This is on 192.168.88.20. <br>
For the administration of OpenLDAP we recommend phpldapadmin. <br>
This script will ONLY setup the client part. <br>
<br>
Dont forget to cross fingers while running. <br>
# Beware!
If you are using the default GDM you need to create a local user. <br>
Otherwise the system will force you to create one before you can login to the domain. <br>
We found that out painfully by trying stuff for hours. <br>
# GPLv3
This is free (as in freedom) Software. <br>
