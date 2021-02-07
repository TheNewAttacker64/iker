# iker
### iker.py
### 
### This tool can be used to analyse the security of a IPsec based VPN.
### 
### This script is under GPL v3 License:
### 
###                                http://www.gnu.org/licenses/gpl-3.0.html
### 
### From a IP address/range or a list of them, iker.py uses ike-scan to 
### look for common misconfiguration in VPN concentrators.
### 
### In this version, iker does:
### 
### * VPNs discovering
### * check for IKE v2 support
### * vendor IDs (VID) extraction
### * implementation guessing (backoff)
### * list supported transforms in Main Mode
### * check aggressive mode and list supported transforms in this mode
### * enumerate valid client/group IDs in aggressive mode
### * analyse results to extract actual issues
### * support 2 output formats
