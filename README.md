# Routersploit
This provides an overview tutorial of the RouterSploit tool

## Prerequisites
1. Download python3 requirements with:  ``python3 -m pip install pysnmp paramiko beautifulsoup4 requests pycrypto``
2. Download routersploit with: ``git clone https://github.com/threat9/routersploit``
3. ``cd routersploit`` and run ``sudo python3 ./rsf.py``

## Setting the Target
1. Set the module to be ``use scanners/autopwn``
2. Set the target to be router's IP address ( found by ``ip r``) with: ``set taget <Router IP>``
3. ``run`` to find the list of vulnerabilities associated with the router.
4. If the router is vulnerable to any exploits, run the payload to exploit the vulnerabilty
