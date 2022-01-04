# securityonion-otx
Script to automatically configure [Stephen Hosom's](https://github.com/hosom/bro-otx) implementation of the Alienvault Bro OTX Connector for a Security Onion sensor.

You will need an API key for [Alienvault OTX](https://otx.alienvault.com/) to complete this install.
```
wget https://raw.githubusercontent.com/weslambert/securityonion-otx/master/securityonion-otx
sudo ./securityonion-otx
```
Please keep in mind we do not officially support use of this script, so installation is at your own risk. Also note that some users have reported issues with the OTX feeds causing Zeek to crash.
