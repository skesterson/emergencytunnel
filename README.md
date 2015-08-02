# emergencytunnel
Simple TCP tunnel for overly restrictive networks

Requires: Ruby stdlib

# Usage
* Edit the constants at the top of the file to suit your environment
* Run the script on your unfriendly SSH server
* Connect to emergency tunnel with your SSH client. Ex: ssh -D 3128 -p 54321 user@unfriendly.sshhost.com
* Connect applications into your restricted environment via the SOCKS proxy on localhost:3128

# Disclaimer
I am not responsible if you get fired for using this
